## Projeto Integrador: 2020-2

## Projeto 3º Semestre: ***JumboETL***.
![](https://i.imgur.com/GVAU8Y1.png)

### Introdução ao projeto

No terceiro semestre da faculdade Fatec - São José dos Campos, tivemos a empresa Visiona como parceira a qual nos apresentou a necessidade de uma ferramenta com o funcionamento ETL  (extração, transformação, carregamento) para tratar os dados georeferenciados em um Arquivos tipo ShapeFile e grava-los em um banco de dados, a ferramenta também faria a operação inversa, pegandos os dados em um banco e transformado em uma arquivo ShapeFile por meio de uma interface gráfica simples e intuitiva.  

### Empresa parceira

Visiona Tecnologia Espacial S.A.

***

### Visão do Projeto

Temos como visão nesse projeto, ajudar a empresaa parceira a solucionar essa necessiade através de nosso software ETL, que será capaz de armazenar e extrair dados de um banco de dados de forma simples e intuitiva. 

### Solução

Pensando na necessidade da empresa parceira, criamos o sistema JumboETL que permite ao usuário gerenciar dados georreferenciados de um arquivo no formato Shapefile, junto ao Banco de Dados, utilizando uma ferramenta de software ETL(extração, transformação e carregamento). Construído para interagir com dados georreferenciados. O usuário pode alimentar a base de dados de maneira simples e intuitiva, também podendo manipular e recuperar arquivos no formato Shapefile desse banco. A aplicação oferece disponibilidade e a conveniência de rodar em qualquer dispositivo com suporte a navegadores web.

Telas do projeto:
![](https://i.imgur.com/0AO8IiY.jpg)

### Lista de Requisitos 

Para a validação das entregas, utilizamos os seguintes critérios 

Requisitos Funcionais: 

- Carga de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos em tabelas existentes de banco de dados geográficos; 
- Recuperação de dados geográficos (ponto, linha e polígono) e seus atributos alfanuméricos armazenados em banco de dados geográficos.
- Upload de arquivos para realização do ETL

Requisitos não Funcionais:

- Sistema WEB
- Banco de Dados Geográficos PostGIS
- Usabalidade


***

### Link do git
[Acesse o Repositório](https://github.com/DaviNeves0/ETL_Visiona)


### Tecnologias adotadas na solução

Para obter o resultado esperado, a equipe utilizou as seguintes tecnologias:

![](https://i.imgur.com/bNRJEIt.png)

Front-End
- HTML: Para a criação e estruturação da página Web.
- CSS: Para a estilização e criação do Layout. utilizando as medias queries para a resposividade em dispositivos móveis. 
- Javascript: Para a criação das funcionalidade do client-side
- Bibliotecas: React, Axios, Ant Design

Back-End
- Python 3: construnção das rotas, funções e operações do backend
- Bibliotecas: Flask, pyshp, psycopg2, flask-cors, python-dotenv
- GDAL
  - Utilitário: ogr2ogr
- PostgreSQL
  - Extensão: PostGIS

### Contribuições pessoais

Com o desenvolvimento do projeto e o decorrer do semestre, pude desenvolver habilidades técnicas (Hard Skills), trabalhei efetivamente no desenvolvimento das interfaces, criando as telas de modo simples e intuitiva para o usuário. Desenvolvi as rotas do Front-End e a construção das páginas e lógica de cadastro e login, utilizando React como FrameWork. 
Entre as habilidades interpessoais (Soft Skills), consegui participar ativamente das reuniões e entrega dos requisitos. O grupo utilizou a metodologia SCRUM para o gerenciamento do tempo, cards e planejamentos.   

### Aprendizados Efetivos HS

- Desenvolver códigos em HTML: Sei utilizar com autonomia;
- Desenvolver folhas de estilos com CSS: Sei utilizar com autonomia;
- Integração do front-end com a API: Sei utilizar com autonomia;
- Criar e organizar a estrutara dos arquivos de códigos: Sei utilizar com autonomia;
- Metodologias Scrum: Conceitos aprendidos na prática;

