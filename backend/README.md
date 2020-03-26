# Anotações - Semana Omnistack 11.0

## Tecnologias
 * **Server Restart**: nodemon
 * **Database**: sqlite3
 * **Query Builder**: knex


## Rota/Recursos

 Metodos HTTP:
 * **GET**: Buscar/listar informações do back-end
 * **POST**: Criar uma informação no back-end
 * **PUT**: Alterar uma infromação no back-end
 * **DELETE**: Deletar uma informação no back-end


Tipos de Parâmetros:

 * **Query Params**: Parâmetros nomeados enviados na rota após "?" (filtros, paginação)
 * **Route Params**: Parâmetros utilizados para identificar recursos
 * **Request Body**: Corpo da requisição, utilizado para criar ou alterar recursos

Bancos de Dados
 * **SQL**: MySQL, SQLite, PostgreSQL, Oracle, Microsoft SQL Server
 * **NoSQL**: MongoDB, CouchDB, etc..
 * **Driver**: SELECT * FROM users
 * **Query Builder**: table('users').select('*').where()


## Entidades
 * ONG 
 * Caso (indicent)


## Funcionalidados
 * Login de ONG - ok
 * Logout de ONG
 * Cadastro de ONG - ok
 * Cadastro de novos casos - ok
 * Deletar casos - ok
 * Listar casos específicos de uma ONG - ok
 * Listar todos os casos - ok
 * Entrar em contato com a ONG