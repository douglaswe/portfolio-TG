`Em 2024-2`

<span id="topo">
<h1 align="center"><b>Desenvolvimento de um chatbot inteligente baseado em IA que será capaz de analisar uma vasta base de depoimentos de clientes usando a técnica RAG.</h1></b>

<p align="center">
  <a href ="#sobre-o-projeto"> Sobre o Projeto </a>  • 
  <a href ="#requisitos">Requisitos </a>  • 
  <a href ="#funcionalidades">Funcionalidades </a>  • 
  <a href ="#repositorio"> Repositório do projeto </a>  • 
  <a href ="#tecnologias-utilizadas"> Tecnologias </a>  •
  <a href ="#contribuições"> Minhas Contribuições </a>  •
  <a href ="#hard-skills"> Hard Skills </a> •
  <a href ="#soft-skills"> Soft Skills </a>
 
</p>

<span id="sobre-o-projeto">

## Sobre o Projeto

As equipes de marketing enfrentam dificuldades para extrair rapidamente insights relevantes a partir de uma grande quantidade de depoimentos e feedbacks dos clientes. Esses depoimentos com grande volume, tornam difícil identificar tendências e áreas de melhoria de maneira ágil. Pensando nisso a equipe fez a proposta de um desenvolvimento de um chatbot inteligente baseado em IA generativa que será capaz de analisar uma vasta base de depoimentos de clientes da B2W. Esse sistema usará a técnica RAG (Retrieval Augmented Generation) para buscar respostas diretamente da base de dados vetorizada, proporcionando insights rápidos e precisos. O chatbot auxiliará equipes de marketing na personalização de campanhas e estratégias publicitárias, identificando tendências e áreas de melhoria a partir de comentários reais dos clientes. Dessa forma, ele ajudará a ajustar estratégias rapidamente e sugerir novos segmentos, otimizando a eficácia das campanhas de marketing. A empresa parceira nesse projeto foi a Dom Rock, especializada em inteligência artificial para a tomada de decisões em negócios.

<span id="requisitos">

## ✔️ Requisitos funcionais
+ RF1 - Análise de produtos: Identificação do chatbot sobre padrões e características dos produtos apontadas pelas opiniões analisadas.
  + Usabilidade:
    + Pergunta: Me fala caracteristicas do Iphone 8
    + Resposta: * Tela de 5,5 polegadas * Processador iOS 11 * Opções de estoque: 64GB * Suporte a 4G e Wi-Fi * Camera traseira de 12MP * Cor disponível: dourado (no caso do iPhone 8 Plus) e cinza espacial.
+ RF2 - Recomendação de produtos entre clientes (percepção dos clientes): Sugestões de produtos baseadas nas recomendações dos clientes.
  + Usabilidade:
    + Pergunta: Me indique smartphones
    + Resposta:  1. Smartphone Samsung Galaxy J5 Prime, 2. Smartphone Samsung Galaxy J5 Prime, 3. Smartphone LG G6
+ RF3 - Análise de satisfação do cliente por produto: Avaliação do nível de contentamento por produto.
  + Usabilidade:
    + Pergunta: Me fale a satisfação de todas as reviews do produto Smartphone Samsung Galaxy J5
    + Resposta: A satisfação dos clientes com o produto Smartphone Samsung Galaxy J5 é baixa. Das 4 reviews fornecidas, 3 delas são negativas e 1 é positiva. A review com nota 1 menciona problemas com a tela do produto, que começou a piscar alguns minutos após o uso.
+ RF4 - Padrões de compra de produtos por região ou idade: Identificação de tendências demográficas e comportamentais de compra.
  + Usabilidade:
    + Pergunta: Me fale qual foi a categoria de compra mais feita em no estado de SP
    + Resposta: Sobre as informações fornecidas, podemos ver que as categorias de compra mais frequentes no estado de SP foram: * Ferramentas jardim e  * Beleza e perfumaria
+ RF5 - Comparação de experiência de compra: Análise comparativa de compras entre diferentes perfis consumidores.
  + Usabilidade:
    + Pergunta: Me de comparação de experiencia de compra sobre o seguinte produto: Smartphone Motorola Moto G5 Plus
    + Resposta: Existem quatro reviews para o produto Motorola Moto G5 Plus: A primeira review com um rating de 5 estrelas menciona que o smartphone é rápido, preciso, com boa bateria e design agradável. O reviewer também destaca que o produto tem um espaço de armazenamento adequado e funções intuitivas. A segunda review com um rating de 1 estrela menciona que o smartphone parou de funcionar após apenas 3 meses de uso, após uma atualização de software. O reviewer também criticou a Motorola por não ter resolvido o problema e negar as motivações da paralisação. A terceira review com um rating de 2 estrelas menciona que o reviewer comprou o produto e a entrega foi rápida, mas a transportadora não movimentou o produto após 15 dias e emitiu uma nota fiscal. A quarta review com um rating de 5 estrelas menciona que o smartphone atendeu às expectativas do reviewer, com câmeras excelentes e uma bateria que carrega rapidamente.

## ✔️ Requisitos não funcionais
+ RNF1 - BD Vetorial ChromaDB
+ RNF2 - Modelos LLM de uso público do Huggingface
+ RNF3 - Framework Langchain
+ RNF4 - Vídeo-tutorial: Criação de um vídeo-tutorial para auxiliar usuários sem experiencia prévia.

</br>

<img src="https://cdn-icons-png.flaticon.com/512/959/959208.png" width="14"> [Voltar ao topo](#topo)

<span id="funcionalidades">

## Funcionalidade

<details>
  <summary>
    <h4 align="left">Recomendação de produtos entre clientes (percepção dos clientes): Sugestões de produtos baseadas nas recomendações dos clientes.</h4>
  </summary>
  
  <img src="https://github.com/user-attachments/assets/21414842-e4fc-4616-bc69-4c20dbe9e78c">
</details>

<details>
  <summary>
    <h4 align="left">Análise de satisfação do cliente por produto: Avaliação do nível de contentamento por produto</h4>
  </summary>
  
  <img src="https://github.com/user-attachments/assets/8c7730f4-892c-4e01-a090-838e6fe90291">
</details>

<details>
  <summary>
    <h4 align="left">Comparação de experiência de compra: Análise comparativa de compras entre diferentes perfis consumidores</h4>
  </summary>
  
  <img src="https://github.com/user-attachments/assets/c81eb9ff-1483-4bea-8fc7-ee2bd3049072">
</details>

<details>
  <summary>
    <h4 align="left">Análise de produtos: Identificação do chatbot sobre padrões e características dos produtos apontadas pelas opiniões analisadas.</h4>
  </summary>
  
  <img src="https://github.com/user-attachments/assets/b5b6930c-5e6e-48ec-b1e4-8ea0e44253e1">
</details>




<span id="repositorio">

---
### [📕 Repositório do Projeto ](https://github.com/douglaswe/API-FATEC-6-SEM)
---

## Tecnologias Utilizadas

##### Reuniões

- WhatsApp - Comunicação rápida com os integrantes, avisos;
- Discord - Para reuniões.
  
##### Banco de Dados de vetores
 
- ChromaDB - Base de dados vetorial para armazenar os depoimentos de clientes da B2W.

##### Back-end  
  
- Python - Utilizado para desenvolver a soluções de IA, especialmente no campo do Processamento de Linguagem Natural (PLN).
- LangChain - Uma interface padrão que permite interações com uma ampla gama de Grandes Modelos de Linguagem (LLMs).
- LLM (llama3-8b-8192) - Modelo usado.  
  
##### Front-end 
 
- Vue.js - Usado para fazer a interface de usuário.
  
##### Outros
 
- Github - Repositório do projeto para controle de versão;
- Visual Studio Code - Ambiente de Desenvolvimento Integrado do grupo;
- Figma - Criação da prototipagem.



<img src="https://cdn-icons-png.flaticon.com/512/959/959208.png" width="14"> [Voltar ao topo](#topo)

<span id="contribuições">

## Contribuições Pessoais

Atuei como Desenvolvedor Frontend e na parte do desenvolvimento da IA, na parte de ia desenvolvi a leitura e a limpeza dos dados do csv do B2W, o bloqueio de perguntas fora do contexto, criação do endpoints para conectar a IA com o frontend via WebSocket, Verificação de Alucinações do Chatbot ja na parte do frontend desenvolvi a apresentação das respostas no chatbot para torná-las mais legíveis e visualmente atraentes.

Essas implementações no frontend foram feitas usando Vue e no desenvolvimento da IA foram feitas usando Python com LangChain.

<img src="https://cdn-icons-png.flaticon.com/512/959/959208.png" width="14"> [Voltar ao topo](#topo)

<span id="#hard-skills">

## Hard Skills

* Vue.js → sei fazer com auxílio de consultas;
* Python → sei fazer com auxílio de consultas;
* ChromaDB → sei fazer com auxílio de consultas;
* LangChain → sei fazer com auxílio de consultas;
  
<img src="https://cdn-icons-png.flaticon.com/512/959/959208.png" width="14"> [Voltar ao topo](#topo)

<span id="soft-skills">

## Soft Skills

## Trabalho em equipe
A colaboração com a equipe foi essencial para o sucesso deste projeto, especialmente devido à complexidade de trabalhar com IA.  Por exemplo, durante a implementação do bloqueio de perguntas fora do contexto no chatbot, compartilhei a abordagem que estava usando com o time e troquei ideias sobre como aprimorar essa funcionalidade. Essa troca foi essencial para alinhar as soluções técnicas e garantir que todos entendessem o funcionamento e as possibilidades do sistema.

## Autonomia
Mostrei iniciativa ao aprender rapidamente as tecnologias e ferramentas utilizadas no projeto, como ChromaDB, LangChain. Ao enfrentar desafios, busquei soluções de forma autônoma e proativa, recorrendo a materiais de estudo e testes próprios antes de solicitar ajuda. Essa abordagem ajudou a manter o andamento do projeto e mostrou minha capacidade de autogerenciamento e rápida adaptação a novas tecnologias.

## Entrega de Resultados
Todas as funcionalidades atribuídas foram concluídas dentro do prazo e com a qualidade esperada. Um exemplo foi a criação do sistema de bloqueio de perguntas fora do contexto no chatbot, que além de atender ao prazo, trouxe melhorias significativas na precisão das respostas e na experiência do usuário.

## Comunicação
A comunicação foi fundamental para o sucesso do projeto. Um exemplo claro foi quando tivemos uma reunião para discutirmos quais colunas do csv do B2W seriam usadas no projeto 

<img src="https://cdn-icons-png.flaticon.com/512/959/959208.png" width="14"> [Voltar ao topo](#topo)
