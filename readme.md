# ECOLETA

Desenvolvido por [Renan Queiroz](https://www.rqweb.com.br) | [renan@rqweb.com.br](mailto:renan@rqweb.com.br)

Aplicação criada na primeira NEXT LEVEL WEEK, da [Rocket Seat](https://rocketseat.com.br), para cadastro e busca de locais com Coleta Seletiva. A aplicação utiliza recurso de mapa, informações provenientes da API do IBGE, além de funcionalidade de upload de imagens. O cadastro de novos pontos de coleta são realizados na aplicação WEB e a busca é realizada via aplicativo mobile.

Foi contruída uma base de dados em SQLite para armazenar as informações, além de APIs, criadas em NODE.js, para que a aplicação WEB (react.js) e o aplicativo mobile (React Native) consigam interagir corretamente.


#### WEB:

![](/assets/WEB-01.png)

![](/assets/WEB-02.png)

![](/assets/WEB-03.png)

#### Mobile:

![](/assets/APP-01.png) ![](/assets/APP-02.png) ![](/assets/APP-03.png) 


## Começando

Para executar o projeto, será necessário instalar os seguintes programas:

- [Node.js: para executar o backend](https://nodejs.org/)
- [Expo Client: para executar o aplicativo mobile no seu celular](https://expo.io/)
- instalar as dependências necessárias da parte WEB, listadas no arquivo [package.json](/web/package.json)
- instalar as dependencias necessárias do backend, listadas no arquivo [package.json](/server/package.json)
- instalar as dependências necessárias da parte mobile, listadas no arquivo [package.json](/mobile/package.json)

Após estar com ambiente pronto, deve-se criar o banco de dados:

- Executar, na pasta "server", o comando "npm run knex:migrate", para a criação do banco de dados.
- Executar, na pasta "server", o comendo "npm run knex:seeds", para criar os registros necessários no Banco de Dados.


## Executando o projeto 

Para utilizar, basta iniciar cada parte do projeto:

- Backend: acessar a pasta "server" e executando o comando "npm run dev"
- WEB: acessar a pasta "web" e executar "npm start"
- Mobile: acessar a pasta "mobile" e executar o comando "npm start"
- Abrir o Expo client no seu celular e conectar com o servidor da aplicação