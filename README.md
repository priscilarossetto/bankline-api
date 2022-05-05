# Abstraindo o Domínio Bancário em uma API REST usando Java e Spring Boot 💰

### Santander Dev Week - Java Full Stack ☕
O projeto é baseado na proposta de um Bankline para gestão de correntistas e movimentações de receitas e despesas com base na diagramação abaixo:

![diagrama-entidades](https://user-images.githubusercontent.com/82734110/167014457-a45c2883-69eb-4d20-927a-8fd70169a9b9.jpg)

## Requisitos:

* Implementar com base em uma arquitetura MVC.
* Incorporar numa plataforma de inversão de controle e injeção de dependência como o Spring.
* Interação com banco de dados através do framework ORM Hibernate.
* Disponibilizar a API Rest devidamente documentada através do Swagger.
* Publicar em um container para disposição os nossos serviços de forma pública como o Heroku.

## Spring Initializr

Site que oferece os recursos para criação de um projeto Spring Boot com uso Maven ou Gradle.

* Acesse o site: https://start.spring.io/
* Selecione a opção Maven Project
* Selecione a opção Language - Java

## Preenchimento

* Group: Nome do grupo organizacional
* Artifact: Identificação do projeto
* Name: Nome do Projeto (igual ao artifact)
* Description: Descrição do Projeto
* Package Name: Nome do pacote raíz da sua aplicação
* Packaging: Tipo de Build da sua aplicação, pode manter .jar
* Java: Versão do Java JDK e JRE que está utilizando (neste projeto foi utilizado versão 8)

Clique no botão GENERATE para realizar o download, extraia o aquivo .zip e em seguida importe na IDE Eclipse.

## Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- ![Eclipse](https://img.shields.io/badge/Eclipse-FE7A16.svg?style=for-the-badge&logo=Eclipse&logoColor=white)
- ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white)
- ![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
- ![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
- ![Swagger](https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white)
- ![Heroku](https://img.shields.io/badge/heroku-%23430098.svg?style=for-the-badge&logo=heroku&logoColor=white)

## Deploy da Aplicação:

https://rsstt-dio-bankline-api.herokuapp.com/swagger-ui/index.html

# Créditos
* Aula com o passo a passo da aplicação: https://www.dio.me/dev-week/santander/bootcamps
* Instrutor da aula: [Gleyson Sampaio](https://github.com/glysns)
