LIST OF ACADEMIC PROJECTS:

[PROJECT-SEMESTRE-01-2019.2 - *Python Web Scrapper - Public Safety Monitor*](https://github.com/caroolps/Portfolio01) 

[PROJECT-SEMESTRE-02-2020.1 - *Java Stand Alone GANTT Chart tool*](https://github.com/caroolps/Portfolio02)

[PROJECT-SEMESTRE-03-2020.2 - *Java Web App - Benefits According Credit Score*](https://github.com/caroolps/Portfolio03) 

[PROJECT-SEMESTRE-04-2021.1 - *Oracle HR Solution  for searching candidates via API* ](https://github.com/caroolps/Portfolio04) 

[PROJECT-SEMESTRE-05-2021.2 - *Pentaho & Data Warehouse Analytics of Education* ](https://github.com/caroolps/Portfolio05) 


**FIRST PROJECT, SEMESTRE-01-2019.2 - *Python Web Scrapping - Public Safety Monitor***

![Danzo Logo](https://i.imgur.com/9V0mPnm.png)

**i. SOBRE O PROJETO.**

Introdução
Foi proposto a implantação de um Web bot, que consiste num programa ou conjunto de instruções em código que verifica a teia mundial (W.W.W.) de forma metódica ou automatizada. Este processo tem no seu cerne uma função básica chamada de Web crawling ou spidering. A literatura atual tende a identificar o Web crawler e o Web bot como sinônimos. Para fins deste projeto, o web bot [doravante denominado WB] consiste num robô da Internet que vasculha por dados determinados nas instruções do código de programação e geral certos resultados que tenham valor para o cliente (product owner).
O WB podem ser utilizados para copiar dados de páginas da Internet que se queira vasculhar, verificando links e validar códigos HTML. Além disso, podem ser utilizados para obter dados especificados previamente, tal qual endereços de e-mail (geralmente para que se crie uma lista de SPAM), ou dados estatísticos em geral.
Com uma variedade virtualmente infindável de usos, os WB podem ser utilizados tanto para ferramentas de suporte à automação de tarefas com objetivos benignos como para prejudicar pessoas, variando desde serviços de atendimento ao consumidor (chat bots), passando por monitoramento de informações esparsas sem controle ou repositório oficial até mesmo ataques cibernéticos por civis e militares (DDOS - distributed denial of service attack, ou ataques distribuídos de negação de serviço pela exaustão do servidor que não suporta a quantidade de requisições que um robô da Internet pode requisitar).

 

I - DESCRIÇÃO DO PROJETO.

O primeiro projeto integrador trouxe o tema 'web bot', com liberdade para buscar ferramentas tecnologicas para a efetiva entrega de um Mapeador de Criminalidade ao Redor da FATEC.

Houve dificuldades de natureza humana, estrutural e tecnológica. No primero semestre, encontrando pela primeira vez os colegas e professores, com limitações estruturais e conhecendo novo vocabulário: nomes e neologismos, bem como de gerência de projetos, ambos de TI (metodologia Agile).

Com o suporte de alunos mais experientes do último semestre, os membros da equipe foram revelando suas características e contribuindo livremente com ideias.

Por critério social e utilitarista e no contexto de fatos ocorridos ao redor da FATEC, elegemos um webbot que pudesse mostrar índices de criminalidade nas redondezas de seu prédio. Ao final, verificamos a possibilidade de comerciaização da solução tanto para o Poder Público como para o mercado imobiliário, securitário, de segurança, transporte e entretenimento em qualquer região do Estado de São Paulo.

Neste semestre, como estréia deste modelo de aprendizado (por projeto), havia ampla liberdade oriunda da amplitude do escopo. Ademais, o processo de criação e aprendizado tem velocidade diferente entre alunos.

Assim, implantamos uma metodologia que denominamos "competing codes". Dois colegas buscavam solução para o mesmo problema, vencendo o código que melhor atendesse as necessidades dos projetos.

Nesse processo, estudamos e aprendemos a respeito de diversas ferramentas e bibliotecas do Python que não foram utilizadas na solução em si (*v.g.* matplotlib).

Ao final, o webbot foi capaz de realizar as seguintes tarefas:

1 - Escolha do usuário na página DANZO;​

2 – Obtenção de dados do sítio Transparência SSP-SP;​

![20211026-205948](https://user-images.githubusercontent.com/61089745/141654319-476e8427-220e-482b-a289-de10f10399b3.png)

![](imgs/20211026-210008.png)

![](imgs/20211026-210019.png)

![](imgs/20211026-210044.png)

![](imgs/20211026-210057.png)


3 – Tratamento de arquivo obtido: criação de pasta local, renomeação;​

4 – Tratamento de dados: Leitura do arquivo obtido, coluna por coluna LISTAS), para  inserção em BD;​

![](imgs/20211026-210117.png)

5 – Inserção incremental em BD Sqlite3;​

6 – Leitura do BD Sqlite3;​

7 – Apresentação dos dados: mapa de calor, barras; ​

![](imgs/20211026-210136.png)


**II - TECNOLOGIAS**

Em fase inicial do aprendizado, a equipe elegeu o Python por ser linguagem de programação de alto nível mais amigável ao programador.

No contexto do Python, contamos com a orientação do Docente e muita pesquisa em fóruns virtuais especializados para implementar blocos de códigos com propósito específico.

As bibliotecas mais importantes foram:

- selenium: emulação de ações humanas para acessar o sitio da Secretaria de Segurança Pública do Estado de São Paulo, baixando os dados das métricas de crimes em arquivo em formato .CSV, após escolher município, bairro, tipo de crime e período. Escolhemos os crimes contra o patrimônio (furto ou roubo), de aparelhos celulares, automóveis, casas ou estabelecimentos comerciais.

-  pandas: agrupamento de dados por localização, entregando os dados tratados para a apresentação em mapa de calor. Recebemos um curso extracurricular de "Python para Jornalistas", aprendendo as principais funcionalidades para demostrar dados com significância para o usuário final. aqui, nasceu para mim a curiosidade por Ciência de Dados. Com meu conhecimento prévio na área jurídica, tonou-se mais fácil explicar conceitos e etender o que seria mais adequado demonstrar.

-  folium:  biblioteca do Python que facilita a visualização dos dados em um mapa interativo, no projeto essa bibilioteca nos auxiliou a manipular os dados no mapa de calor que que mostrava as regiões que com mais índice de criminalidade ao redor da Fatec.

- flask: o Flask é um framework para Python utilizado para desenvolver aplicação web, escolhemos o Flask pois possui uma arquitetura mais simples, possui menos configurações e rapidez no desenvolvimento.

- flask_googlecharts: é uma biblioteca para geração de gráficos, por ser uma das melhores bibiliotecas de gráficos, utilizamos em nosso projeto para gerar os gráficos mensais do índice de criminalidade.

**III - CONTRIBUIÇÕES INDIVIDUAIS.**

Na definição do MVP (MINIMUM VIABLE PRODUCT) participei ativamente nas decisões de que tipo de criminalidade deveríamos enfatizar, por morar na região da FATEC, pude contribuir em informar os roubos que mais acontecem nessa redondeza. Ficando definido o mapeamento de roubo de Veículos, furto de veículos e roubo de celular.

Nesse passo, a arquitetura ficou assim definnida:
![](imgs/20211026-210335.png)
, 

Como eu vim da área administrativa sem nunca ter contato com a parte de programação foi desafiador o aprendizado de uma linguagem backend e o contato com o banco de dados, como alguns integrantes da equipe já estavam mais familiarizados com essas tecnologias eu assumi o front-end do projeto. Com aprendizado a parte das matérias da FATEC, acabei trazendo as tecnologias de HTML, Bootstrap e GoogleChart para o Projet Web Danzo.

HTML: é uma linguagem de marcação utilizada na construção de páginas na Web. Com ela eu desenvolvi o esqueleto do projeto usandos as tags:
<html>: inicia e finaliza o projeto com essa tag;
<head>: recebe todas as informações básicas da página, como o título, links de elementos externos, etc 
<title>: título da páginha; 
<body>: consiste no corpo do nosso documento, onde ficam todos os elementos que serão renderizados na tela do navegador;

Bootstrap: é um framework web utilizado para estilizar o projeto web.

GoogleChart: Como o foco era mostrar os índices de criminalidade para oferecer para o usuário uma análise de fácil compreensão, após pesquisar encontrei o GoogleChart para realizar os gráficos mensais dos índices de criminalidade;



**IV - APRENDIZADOS EFETIVOS.**

Tivemos o primeiro contato com a Metodologia Agil:
 
com as ferramentas para acompanhamento do projeto: Slack
 
Conhecimneto no repositório no Gitlab:
 
Primeiro contato com a linguagem Python:
 
Primeiro contato com o banco de dados:
 
Aplicamos a lógica de programação no desenvolvimento do projeto API;
 
Grandes ganhos de conhecimento no Front-end;
 


Ao final do projeto, percebemos que a utilização da solução poderia ser aproveitada por muitos recortes sociaisi:

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

