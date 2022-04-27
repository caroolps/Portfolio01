## 📚 Seções Portfólios

<h4 align="left"><a href="https://github.com/caroolps/Portfolio01">PROJETO 1º SEMESTRE: Mapeador de Criminalidade ao Redor da FATEC</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio02">PROJETO 2º SEMESTRE: Gantt Chart</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio03">PROJETO 3º SEMESTRE: Cadastro Positivo</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio04">PROJETO 4º SEMESTRE: JobNation</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio05">PROJETO 5º SEMESTRE: Educalytics</a></h4>
<h4 align="left"><a href="https://github.com/caroolps/Portfolio06">PROJETO 6º SEMESTRE: Opt-In/Out</a></h4>

![image](https://user-images.githubusercontent.com/61089745/158082449-894548ea-e14d-4de7-896d-12d2a9ec1d74.png)



## Mapeador de Criminalidade ao Redor da FATEC :pushpin:


### **I - RESUMO DO PROJETO**:page_facing_up: 

O primeiro projeto integrador trouxe o tema 'web bot' escolhido pelos docentes da faculdade, porém com liberdade para buscar ferramentas tecnológicas e o tipo de raspagem de dados.

Com o suporte de alunos mais experientes do último semestre, os membros da equipe foram revelando suas características e contribuindo livremente com ideias. Por critério social e utilitarista e no contexto de fatos ocorridos ao redor da FATEC, elegemos um webbot que pudesse mostrar índices de criminalidade nas redondezas de seu prédio. Ao final, verificamos a possibilidade de comercialização da solução tanto para o Poder Público como para o mercado imobiliário, securitário, de segurança, transporte e entretenimento em qualquer região do Estado de São Paulo.

Neste semestre, como estreia deste modelo de aprendizado (por projeto), havia ampla liberdade oriunda da amplitude do escopo. Ademais, o processo de criação e aprendizado tem velocidade diferente entre alunos.

Assim, implantamos uma metodologia que denominamos "competing codes". Dois colegas buscavam solução para o mesmo problema, vencendo o código que melhor atendesse as necessidades dos projetos.

Nesse processo, estudamos e aprendemos a respeito de diversas ferramentas e bibliotecas do Python que não foram utilizadas na solução em si (*v.g.* matplotlib).

Ao final, o webbot foi capaz de realizar as seguintes tarefas:

1 - Escolha do usuário na página DANZO;​

2 – Obtenção de dados do sítio Transparência SSP-SP;​

![image](https://user-images.githubusercontent.com/61089745/159133372-f87f3e0d-b9ea-4f03-8d93-75857ad17c07.png)

![image](https://user-images.githubusercontent.com/61089745/159133530-2f6e4b2e-bbb1-4faf-b658-40275f6fb919.png)

![image](https://user-images.githubusercontent.com/61089745/159133602-ee67df9e-8152-4d45-9716-33078d9e38d0.png)

![image](https://user-images.githubusercontent.com/61089745/159133671-8f088965-f13f-4ec3-aad1-15176628a156.png)

![image](https://user-images.githubusercontent.com/61089745/159133727-3618eb50-7809-4688-b5fa-cb522b1b9a7e.png)


3 – Tratamento de arquivo obtido: criação de pasta local, renomeação;​

4 – Tratamento de dados: Leitura do arquivo obtido, coluna por coluna LISTAS, para  inserção em BD;​

![image](https://user-images.githubusercontent.com/61089745/159133838-42e43854-1c59-4eb6-9750-aa23bd9ac848.png)

5 – Inserção incremental em BD Sqlite3;​

6 – Leitura do BD Sqlite3;​

7 – Apresentação dos dados: mapa de calor, barras; ​

![image](https://user-images.githubusercontent.com/61089745/159133870-acb11ea9-4946-4658-9d5a-0e2a21ee48fa.png)


### **II - TECNOLOGIAS**:iphone:

Em fase inicial do aprendizado, a equipe elegeu o Python por ser linguagem de programação de alto nível mais amigável ao programador.

No contexto do Python, contamos com a orientação do Docente e muita pesquisa em fóruns virtuais especializados para implementar blocos de códigos com propósito específico.

As bibliotecas mais importantes foram:

![image](https://user-images.githubusercontent.com/61089745/159134292-1127f6aa-e24d-43d0-b587-dcef8b5ce532.png)
- Selenium: Emulação de ações humanas para acessar o sitio da Secretaria de Segurança Pública do Estado de São Paulo, baixando os dados das métricas de crimes em arquivo em formato .CSV, após escolher município, bairro, tipo de crime e período. Escolhemos os crimes contra o patrimônio (furto ou roubo), de aparelhos celulares, automóveis, casas ou estabelecimentos comerciais.

![image](https://user-images.githubusercontent.com/61089745/159134415-b278bad6-9f54-4adf-b086-1c40a02c387c.png)
-  Pandas: Agrupamento de dados por localização, entregando os dados tratados para a apresentação em mapa de calor. Recebemos um curso extracurricular de "Python para Jornalistas", aprendendo as principais funcionalidades para demostrar dados com significância para o usuário final.

![image](https://user-images.githubusercontent.com/61089745/159134484-cd0d053d-e74d-4c45-99d2-697d615f9361.png)
-  Folium:  Biblioteca do Python que facilita a visualização dos dados em um mapa interativo, no projeto essa bibilioteca nos auxiliou a manipular os dados no mapa de calor que que mostrava as regiões que com mais índice de criminalidade ao redor da Fatec.

![image](https://user-images.githubusercontent.com/61089745/159134535-daf063c7-dc28-4974-a029-0a5fc5f78109.png)
- Flask: É um framework para Python utilizado para desenvolver aplicação web, escolhemos o Flask pois possui uma arquitetura mais simples, possui menos configurações e rapidez no desenvolvimento, com um deadline curto de aprendizado. O Scrum Master nos apresentou esse framework.

![image](https://user-images.githubusercontent.com/61089745/159133931-4f4a582b-12c4-4492-be4b-e6ec19481b76.png)


- Flask_googlecharts: É uma biblioteca para geração de gráficos, por ser uma das melhores bibliotecas de gráficos, utilizamos em nosso projeto para gerar os gráficos mensais do índice de criminalidade.

![image](https://user-images.githubusercontent.com/61089745/159133982-473e42d1-daa9-4e4f-b96b-a08723a3337e.png)


### **III - CONTRIBUIÇÕES INDIVIDUAIS**:bow:

Na definição do MVP (MINIMUM VIABLE PRODUCT) participei ativamente nas decisões de que tipo de criminalidade deveríamos enfatizar, por morar na região da FATEC, contribui em informar os roubos com mais incidências na região. Sendo as criminalidades por roubo de veículos, furto de veículos, roubo de celular e latrocínio.

![20211026-202145](https://user-images.githubusercontent.com/61089745/141654512-9f4b0c92-4ff9-4652-ba2d-e76891106934.png)


Após definição dos índices de Criminalidade que o bot iria realizar a raspagem de dados. A equipe iniciou o brainstorm de quais tecnologias seriam usadas para o projeto, como eu estava vindo da área administrativa sem nunca ter tido contato com a parte de programação, foi desafiador o aprendizado de uma linguagem backend e o contato com o banco de dados. Portanto como alguns integrantes da equipe já estavam mais familiarizados com essas tecnologias eu assumi a responsabilidade de fazer o front-end do projeto. Para isso ingressei em cursos online para entender como funcionava uma aplicação web e acabei trazendo as tecnologias de HTML, Bootstrap e GoogleChart para o Projeto Web bot Danzo. Ressalto que na entrega do front-end obtive suporte e orientação do Scrum Master no desenvolvimento da aplicação.

Estrutura desenvolvida:

O HTML: É uma linguagem de marcação utilizada na construção de páginas na Web com ela eu desenvolvi o esqueleto do projeto usando as tags:

- html: Iniciei e finalizei o projeto Web com essa tag;

- head: Inseri todas as informações básicas da página, como o título, links de elementos externos, etc; 

- title: Informei o título da página; 

- body: Consiste no corpo do nosso documento, onde se concentram todos os elementos que serão renderizados na tela do navegador;

Bootstrap: é um framework Web, foi utilizado para estilizar o projeto Web e tornar responsivo.

![image](https://user-images.githubusercontent.com/61089745/159134043-5042ca00-cf9d-4a80-9f1c-6288409633fa.png)

GoogleChart: Como o foco era mostrar os índices de criminalidade para oferecer ao usuário uma análise de fácil compreensão, após pesquisas encontrei o GoogleChart para realizar os gráficos mensais dos índices de criminalidade;

![image](https://user-images.githubusercontent.com/61089745/159134093-087b47a1-767c-4a12-be0c-91d898f25ed6.png)


### **IV - APRENDIZADOS EFETIVOS**:closed_book:

**Soft Skills Efetivamente Desenvolvidas:**

Autonomia para aprender novas tenologias através de vídeos e pesquisas pelo Google.

Tivemos o primeiro contato com a Metodologia Agil: Scrum é uma metodologia utilizada para gerenciar trabalho em produtos complexos, o Scrum é composto por ciclos de atividades programadas — os sprints —, com planejamento de tarefas e datas de início e de fim determinados, ou seja, é um framework no qual pessoas podem solucionar problemas complexos e soluções adaptativas, enquanto criam de forma produtiva agregando o mais alto valor possível ao produto.
 
Canal de comunicação SLACK: Não tinha conhecimento sobre esse serviço de comunicação e por fim o Slack se tornou uma das principais ferramentas de comunicação utilizadas para o desenvolvimento do Projeto Integrador, pois é um meio de comunicação ágil e instantâneo, neste canal era decidido os próximos encontros presenciais, saneamentos de dúvidas das atividades desenvolvidas, etc.

 **Hard Skills Efetivamente Desenvolvidas:**

Conhecimento no repositório no Gitlab: Não sabia que existia ferramentas para guardar e compartilhar códigos e de formada gratuita. O Scrum Master nos apresentou essa tecnologia que utilizamos até hoje. Aprendemos os principais comandos como: 

- Adicionar um diretório em específico: git add meu_diretorio
- Clonar um repositório: git clone
- Adicionar todos os arquivos/diretórios: git add .	
- Enviar arquivos para o repositório: git push
- Atualizar os arquivos da branch atual: git pull

Obtive conhecimento básico para desenvolver uma aplicação Front-end, focando nos seus elementos e estrutura, tais como:

O HTML: é uma linguagem de marcação utilizada na construção de páginas na Web.

- html: Deve iniciar e finalizar o projeto web com essa tag;

- head: inseri todas as informações básicas da página, como o título, links de elementos externos, etc; 

- title: Informa o título da página; 

- body: Consiste no corpo do nosso documento, onde ficam todos os elementos que serão renderizados na tela do navegador;

- Inserir imagens e cores no HTML;

Bootstrap: É um framework web foi utilizado para estilizar a página web.

GoogleChart: Biblioteca para geração de gráficos;
 
Ao final do projeto, percebemos que a utilização da solução poderia ser aproveitada por muitas áreas sociais:

•	Compra/Aluguel de casa;  
•	Abertura de empresas/comércios;  
•	Estudo na região;  
•	Trabalho na região;  
•	Prática esporte na região;  
•	Lazer (evento cultural, maratona geek, ou festa na região);  
•	Morador/Frequentador da região.  

Poteciais clientes pagantes:
-Empresas de segurança: com esses dados poderiam definir uma demanda de vendas/colaboradores por região;  
-Imobiliárias/Construtoras: com esses dados poderiam traçar o perfil de clientes para determinadas regiões;  
-Empreendedores: que teriam acesso a informações sobre o perfil da pessoa que frequenta a região, abrindo um restaurante ou loja que atenda a este público alvo.  

A equipe pensa em continuar o desenvolvimento da aplicação para uma futura comercialização.
