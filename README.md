# ForoHub

Esta API proporciona todas las funcionalidades CRUD necesarias para gestionar un foro, incluyendo la creación, consulta, actualización y eliminación de tópicos. Foro-Hub está diseñado para facilitar la interacción entre usuarios que buscan resolver sus dudas y compartir conocimientos.

## Introducción

**ForoHub** es una plataforma API REST desarrollada con Spring Boot, diseñada para facilitar la gestión de tópicos en una comunidad virtual. Permite a los usuarios autenticarse, crear, listar y eliminar tópicos de discusión de manera eficiente y segura mediante autentificación JWT.

## Características ✨

- **Registro de Usuarios**: Registro seguro de nuevos usuarios mediante endpoint `POST /signup`.
- **Autenticación JWT**: Generación de tokens JWT para inicio de sesión seguro con `POST /login`.
- **Gestión de Tópicos**: Creación (`POST /topicos`), listado (`GET /topicos` o `GET /topicos{id}` ), actualización (`PUT /topicos/{id}`) y eliminación (`DELETE /topicos/{id}`) de tópicos disponibles.

## Tecnologías Utilizadas 🛠️

El proyecto hace uso de diversas tecnologías y herramientas indispensables:

- **IDE** (Entorno de desarrollo integrado) IntelliJ IDEA
- **Spring Boot 3
https://start.spring.io/
- **Lenguaje de programación:** Java 17,
- **Gestor de dependencia:** Maven 8
- **Base de datos:** MySQL 8
- **JPA (Java Persistence API)**
- **Seguridad:** Spring Security
- **Pruebas de API:** Insomnia
https://insomnia.rest/
- **Autenticación:** JSON web token
https://jwt.io/
- **Documentación:** SpringDoc y Swagger UI
- **Formación: Alura Latam, curso:** JAVA y SPRING BOOT 3 https://www.aluracursos.com/

## Instalación 🚧

Para comenzar con ForoHub, sigue estos pasos:

1. **Clonar este repositorio**:
```bash
git clone https://github.com/Daniel-tic/Forohub_challenge.git
```

2. **Configuración de la base de datos:**

Deberas configurar el archivo `application.properties` para modificar las credenciales a la base de datos. El proyecto está configurado para usar la base de datos "db_alura". Si necesitas crear la base de datos en MySQL, ejecuta el siguiente comando SQL:
```sql
CREATE DATABASE db_alura;
```


## Documentación Adicional 📘

Para más detalles sobre los endpoints disponibles y la estructura de las solicitudes, visita la interfaz de Swagger en:
```
http://localhost:8080/swagger-ui/index.html

