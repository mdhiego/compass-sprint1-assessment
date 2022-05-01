# Avaliação Sprint 1 – Programa de Bolsas

## Compass.UOL

## Estagiário: Dhiego Martins Andrade

---

### Tema: Segurança de redes: Conheça as vulnerabilidades de servidores e clientes

#### 1. O que é um ataque DDoS e como posso me proteger?

- Reduzir a área da superfície de ataque
- Planejar para escalar
- Saber o que é um tráfego normal e um anormal
- Implantar firewalls para ataques de Aplicativo sofisticados

Referência: [Amazon AWS](https://aws.amazon.com/pt/shield/ddos-attack-protection/?nc1=h_ls)

#### 2. Por que o firewall é uma ferramenta muito importante de proteção?

O firewall possibilita a separação de rede em regiões diferentes, por exemplo: uma que possa ser acessada por usuários da internet e uma que seja somente de uso interno. Como o firewall não permite que sejam passados dados de uma zona de menor para uma zona de maior segurança ele constitui uma barreira extremamente importante contra vetores maliciosos externos à rede que o mesmo protege.

O firewall permite o estabelecimento de regras para bloqueio ou aceitação de tráfego (dados IP, protocolo, porta dentre outros). E uma outra característica muito importante do firewall é que ele não aceitará, por padrão, que um tráfego originado da internet entre na rede interna. Ele permitirá que ele entre apenas se alguém de dentro faça uma requisição, e o pacote de dados seja um retorno à essa requisição.

Referência: [Alura](https://cursos.alura.com.br/course/seguranca-redes/)

---

### Tema: Git e GitHub

#### 3. Explique de forma sucinta, o fluxo e envio de um arquivo novo para o repositório do projeto

Considerando que o repositório ara tal é preciso abrir o terminal/shell/bash e entrar com seguintes comandos, na ordem:

1. ```cd /path/to/repo``` -> para o mudar para o diretório do projeto
2. ```git init``` -> para iniciar o repositório no diretório atual
3. ```git status``` -> para verificar o estado do repositório
4. ```git add path_do_arquivo``` -> para adicionar o arquivo específico para área de staging (também pode ser usado o comando ```git add .``` -> para adicionar todos os arquivos recentemente modificados/adicionados)
5. ```git commit -m “Mensagem de descrição do commit”``` -> para mover o arquivo da área de staging consolidando-o no repositório

#### 4. Descreva sobre os ganhos de se utilizar a funcionalidade da branch do git

Branches permitem que diferentes desenvolvedores trabalhem em diferentes features sem interferir no trabalho de cada um. Quando as features estiverem prontas, eles podem fazer o merge das mudanças do branch para o branch principal. Elas também são úteis para experimentar features experimentais sem interferir no código principal do seu projeto.

Referência: [ditech softwarer](http://ditech.com.br/git-beneficios-ferramenta-projetos/#:~:text=Branches%20tamb%C3%A9m%20permitem%20que%20diferentes,branch%20para%20o%20branch%20principal.)

#### 5. Explique a diferença entre criar o repositório na nuvem e iniciar o repositório a partir de um código existente local

Quando um repositório é inicializado em nuvem, após clonado com ```git clone url_git```, é criado automaticamente uma conexão remota chamada origin apontando de volta para o repositório clonado, diferentemente da segunda abordagem onde essa conexão é feita manualmente. Esse comportamento é útil para desenvolvedores que criam uma cópia local de um repositório central, pois fornece uma maneira fácil de fazer pull de alterações upstream ou publicar commits locais. [(Atlassian)](https://www.atlassian.com/git/tutorials/syncing#:~:text=The%20origin%20Remote,changes%20or%20publish%20local%20commits.)

Além disso a inicialização de um repositório na nuvem tende a ser mais conveniente do a criação local pois a depender da plataforma da nuvem usada existiram algumas facilidades como a definição de configurações e a criação de arquivos .gitignore e README.md.

#### 6. Qual a diferença entre Git e GitHub?

O Git é um sistema de controle de versão distribuído de software livre e de código aberto projetado para gerenciar todo o histórico de código-fonte. Ele pode manter um histórico de commits, pode reverter alterações e permite que os desenvolvedores compartilhem código.

O GitHub, por outro lado, é um serviço de hospedagem baseado na web para repositórios Git. Ele oferece todas funcionalidades do Git e possui alguns recursos adicionais como colaboração, gerenciamento de projetos, gerenciamento de tickets de suporte e rastreamento de bugs, etc.

---

### Tema: Fundamentos de Agilidade: seus primeiros passos para a transformação ágil

#### 7. Quais as principais diferenças entre o modelo ágil e o waterfall (modelo em cascata)?

|                  | Modelo Ágil                          | Modelo Waterfall                |
|:----------------:|:------------------------------------:|:-------------------------------:|
| Fluxo de Tarefas | incremental e iterativa              | linear e sequencial             |
| Priorização      | satisfação do cliente                | entrega do projeto bem sucedida |
| Feedback         | ao final de muitos pequenos projetos | ao final de um único projeto    |

#### 8. Quais são as 3 perguntas que devem ser respondidas na Daily?

- O que fiz desde o último Daily Scrum?
- O que pretendo fazer até o próximo?
- Quais problemas me atrapalharam?

#### 9. Qual o intuito das seguintes cerimônias?

- Daily: Resolver obstáculos do dia-a-dia e para todos saberem como está o andamento das tarefas e histórias nessa Sprint;
- Planning: Determinar o planejamento do que será feito na iteração a partir do product-backlog já priorizado;
- Refinamento: Definir as histórias mais prioritárias do projeto, tornando-as claras e dividindo-as em partes menores que agreguem valor para o cliente;
- Review: Apresentar para o cliente e, se possível, para o usuário final tudo o que ficou pronto na Sprint.
- Retrospectiva: Executar o processo de melhoria contínua a partir de propostas ações e sugestões a serem tomadas pelo time Scrum para sanar os problemas identificados.

#### 10. O que é a estimativa na metodologia ágil?

A estimativa na metodologia ágil é o mecanismo de gerenciamento de projetos usado para obter uma ideia sobre os custos e esforços envolvidos na execução de um projeto. Ela ajuda a decidir se o trabalho pode ser realizado conforme proposto, se precisa ser modificado ou se deve ser cancelado.

---

### Tema: Fundamentos HTTP

#### 11. O que é o protocolo HTTP? Qual a diferença entre HTTP e HTTPS?

O HTTP é um protocolo que define as regras de comunicação entre cliente e servidor na internet. Vamos focar nos próximos vídeos e entender melhor esse protocolo tão importante. mãos a obra!

O protocolo HTTPs é basicamente o HTTP comum, porém com uma camada adicional de segurança/criptografia que antes era SSL, mas posteriormente passou a ser também TLS.

Referência: [(Alura)](https://cursos.alura.com.br/course/http-fundamentos)

#### 12. Cite 4 métodos HTTP

- GET: Requisição de dados;
- POSt: Envio de dados;
- PUT: Atualização de dados;
- DELETE: Exclusão de dados.
