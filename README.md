# REST API in PHP 7.4

A compact REST API built without a framework to demonstrate routing, authentication, validation, repositories, services, PDO and JSON responses directly in PHP.

This is an older project and I keep it public as part of my backend engineering history.

## What it demonstrates

- PHP 7.4
- Object-oriented PHP
- Manual autoloading
- Namespaces
- PDO
- MySQL
- Repository and service separation
- Request validation
- Bearer authentication
- JSON responses
- GET, POST, PUT and DELETE endpoints

## Structure

```text
Classes/
  DB/
  Repository/
  Service/
  Util/
  Validator/

bootstrap.php
autoload.php
index.php
script_banco.sql
```

## Routes

```text
GET    /usuarios/listar
GET    /usuarios/listar/{id}
POST   /usuarios/cadastrar
PUT    /usuarios/atualizar/{id}
DELETE /usuarios/deletar/{id}
```

## Local setup

1. Create a MySQL database named `webservice`.
2. Import `script_banco.sql`.
3. Configure the database values in `bootstrap.php`.
4. Serve the project with Apache or another environment compatible with the included `.htaccess`.

## Historical context

This project intentionally remains close to the way I originally built it. It is not meant to represent my current preferred architecture or PHP version.

Its value in the portfolio is showing direct experience with lower-level PHP web-service concepts without relying on a framework.

## Author

Gabriel Felix

LinkedIn:
https://www.linkedin.com/in/biel-felix/
