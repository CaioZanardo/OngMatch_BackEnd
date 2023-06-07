# OngMatch_BackEnd

### Docker

- Após baixar repositorio rodar o comando na raiz:

- docker-compose up (Vai subir os containers a partir do docker-compose.yml)

### Apache

- Para acessar o front http://localhost:8080

### Banco
Para utilizar o banco existe um script na estrutura src/db/dbcadastrouser.sql

- Acessar o http://localhost:8080/ ;
- Criar um novo banco; (nome do banco esta no script);
- Rodar scrips.

### API

Para cadastrar um User via postman:
- Metodo: Post
- URL: http://localhost/api/add-api.php
- Body: selecionar "raw";
- enviar Json:

{

    "user": "(nome_desejado)"
    
}


## Grupo

- André Spinelli Cintra RM 551016
- Augusto de Oliveira Laurino RM 93498
- Caio Felipe Britto Zanardo da Silva RM 95125
- Gabriel Wilke Azevedo RM 95211
- Guilherme de Lucas Garcia RM 94392
