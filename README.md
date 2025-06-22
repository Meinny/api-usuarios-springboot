# Demo Usuarios API

Este es un proyecto de ejemplo construido con Spring Boot que expone una API REST para gestionar usuarios. Utiliza Spring Data JPA para la persistencia y MySQL como base de datos.

## Características

- CRUD básico de usuarios (crear, listar, eliminar)
- API RESTful con Spring Web
- Persistencia con Spring Data JPA y MySQL
- Validación de datos con Spring Validation

## Requisitos

- Java 17 o superior
- Maven 3.9.x
- MySQL

## Configuración

1. Crea una base de datos llamada `mini_api_db` en tu servidor MySQL.
2. Ajusta las credenciales de conexión en [`src/main/resources/application.properties`](src/main/resources/application.properties):
