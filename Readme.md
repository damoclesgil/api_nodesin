# Subir o Servidor
- Instalar o mongodb (https://www.mongodb.com/download-center/community)
- Acessar A pasta do mongo db no terminal ex: C:\Program Files\MongoDB\Server\4.0\bin
- MONGO => É um utilitário que vai permitir acessar o servidor mongodb (uma aplicação client do mongodb)
```bat
mkdir c:\data\db
mongo
```

# Rodar o Banco MongoDB
- MONGOD => É o servidor de banco de dados do MongoDB
```bat
monogodb
```

## Rodar a api
```bat
$ npm start
```

### Comandos MONGODB
```
show dbs;
use curso_mongodb;
db.alunos.save({Nome: "JÃO DAS NEVES"});
db.dropDatabase();
```