# **ORM com NodeJS: API com Sequelize e MySQL**

##Executar projeto

Com a instância do MySQL rodando e o arquivo `./api/config/config.json` configurado corretamente rodar os seguintes comandos

```
npm install
npx sequelize-cli db:migrate
npx sequelize-cli db:seed:all
npm start
```