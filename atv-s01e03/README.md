# Sistemas Distribuídos 🌐

**Uma síntese sobre Tipos de Sistemas Distribuídos e Middleware.**

## 1️⃣ Primeiramente, o que são?

Basicamente, um conjunto de computadores independentes que a vista dos usuários se mostra como um sistema único [(TANENBAUM)](https://pt.wikipedia.org/wiki/Andrew_Stuart_Tanenbaum). Outro conceito encontrado em [Sistemas Distribuídos Conceitos e Projeto](https://pt.slideshare.net/fred_m/si-introduo-a-sistemas-distribuidos) seria:

> Aquele no qual os componentes de hardware ou software, localizados em computadores interligados em rede, se comunicam e coordena suas ações apenas enviando mensagem entre si. 

##### Exemplos: 

- A internet 
- Jogos online 
- Twitter 
- Instagram 

## 2️⃣ Tipos 

[Tanenbaum]: https://docplayer.com.br/46961835-Sistemas-distribuidos.html	"Sistemas Distribuídos - Princípios e Paradigmas"

1. #### Sistemas de Computação Distribuídos 

   Utilizado para para tarefas de computação de alto desempenho. 

   ##### Subgrupos: 

   - **Computação Cluster**

     🔸 Servidores homogêneos, conectados por rede de alta velocidade;

     🔸 Consiste em um conjunto de nós de computadores;

     🔸 Cada nó executa um mesmo tipo de sistema operacional compatível.

   - **Computação em Grade**

     🔸 Compartilhamento de recursos em grande escala; 

     🔸 Os recursos são compartilhados para os membros dessas organizações;

     🔸Divide tarefas entre diferentes máquinas.

   - **Computação em Nuvem**

     🔸 Centros de dados disponíveis para muitos utilizadores pela internet;

     🔸 Funções distribuídas em vários locais dos servidores centrais;

     🔸 Armazenamento de dados em qualquer lugar do mundo.

2. #### Sistemas de Informação Distribuídos 

   ##### Subgrupos

   - ##### Sistemas de processamento de transações

     🔸 Aplicações de banco de dados OLTP

     🔸 As operações de atualização online costumam ser realizadas sob a forma de transações.

     🔸 Requer primitivas especiais fornecidas pelo SGBD

   - ##### Integração de aplicações Empresariais

   - ##### Apps Distribuídas | Servidores de Aplicação

3. #### Sistemas Distribuídos Pervasivos

   ##### Subgrupos

   - ##### Sistemas Domésticos

     🔸 Montados ao redor de redes domésticas: Smartphones, Televisores, Notebooks, jogos, etc...

     🔸Conectados a um sistema único

   - Sistemas de Monitoração pessoal

   - ##### Rede de Sensores

     🔸 Centenas de milhares de nós pequenos, cada um equipado com um dispositivo de sensoriamento

     🔸Utiliza redes sem fios e os nós são alimentados por baterias

   - ##### Internet das coisas (IoT)

4. #### Sistemas de dados Distribuídos 

   [LUCAS, MARCELO]: https://docs.google.com/viewer?a=v&amp;pid=sites&amp;srcid=ZGVmYXVsdGRvbWFpbnxzaXN0ZW1hc2Rpc3RyaWJ1aWRvczIwMTcwMnxneDo3YTJjNzBjOWVjMzBjYTc2	"TIPOS DE SISTEMAS DISTRIBUIDOS"

   ##### Subgrupos 

   - ##### Gerenciadores de bancos de dados distribuídos 

   - ##### Sistemas de Arquivos distribuídos 

   - ##### Gerenciadores de Conteúdo



## 3️⃣Middleware

Middleware é um software que fornece serviços e recursos comuns a aplicações.

[RedHat]: https://www.redhat.com/pt-br/topics/middleware/what-is-middleware	"Middleware"

o Middleware age como uma “camada”, capaz de fazer a mediação entre várias tecnologias de software, de modo que as informações (de diferentes fontes) são movidas ao mesmo tempo que suas diferenças de protocolos, plataformas, arquiteturas, ambientes e sistemas operacionais não interferem no processo. 

> dizendo em termos muito simples ***uma camada no meio*** de duas aplicações, ou seja, uma camada que ajuda duas aplicações, partes, sistemas, a se comunicarem.



