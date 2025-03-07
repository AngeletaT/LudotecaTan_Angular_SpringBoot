# LudotecaTan

**LudotecaTan** es una aplicación full-stack para la gestión de una ludoteca. La solución permite al administrador consultar un catálogo de juegos y actividades, gestionar reservas, realizar préstamos y administrar recursos lúdicos. La aplicación se divide en dos partes principales:

- **LudotecaTan_Cliente:** Aplicación front-end desarrollada con Angular.
- **LudotecaTan_Servidor:** API REST y lógica de negocio desarrollada con Spring Boot.

## Tabla de Contenidos

- [Descripción del Proyecto](#descripción-del-proyecto)
- [Tecnologías Utilizadas](#tecnologías-utilizadas)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Requisitos Previos](#requisitos-previos)
- [Instalación y Ejecución](#instalación-y-ejecución)
  - [Parte del Servidor (Spring Boot)](#parte-del-servidor-spring-boot)
  - [Parte del Cliente (Angular)](#parte-del-cliente-angular)
- [Contribuciones](#contribuciones)
- [Mejoras Futuras](#mejoras-futuras)
- [Licencia](#licencia)

## Descripción del Proyecto

LudotecaTan es una aplicación diseñada para facilitar la administración y consulta de recursos en una ludoteca.  
El sistema se compone de:
- **Backend (LudotecaTan_Servidor):** Implementado en Java con Spring Boot, este módulo se encarga de exponer una API REST para gestionar la lógica de negocio, operaciones CRUD, autenticación y la interacción con la base de datos.
- **Frontend (LudotecaTan_Cliente):** Implementado en Angular, este módulo proporciona una interfaz interactiva y responsiva, permitiendo al usuario consultar el catálogo, ver detalles, realizar reservas y gestionarlas.

## Tecnologías Utilizadas

- **Front-end:**  
  - Angular  
  - TypeScript, HTML, CSS

- **Back-end:**  
  - Java, Spring Boot  
  - Spring Data JPA (para el acceso a la base de datos)  

- **Build y Gestión de Dependencias:**  
  - npm (para el cliente)  
  - Maven o Gradle (para el servidor)

## Estructura del Proyecto

El repositorio se organiza en dos carpetas principales:

- **LudotecaTan_Cliente:**  
  Contiene el código fuente de la aplicación Angular. Se encuentran:
  - Archivos de configuración (`package.json`, `angular.json`, `tsconfig.json`)
  - Directorio `src/` con los componentes, servicios, módulos, rutas y assets.
    

- **LudotecaTan_Servidor:**  
  Contiene el código fuente de la aplicación Spring Boot. Se encuentran:
  - Archivo de build (`pom.xml`)
  - Código fuente en `src/main/java` organizado en paquetes para controladores, servicios, repositorios y entidades.
  - Archivos de configuración en `src/main/resources` (por ejemplo, `application.properties` o `data.sql`).
  - Pruebas unitarias y de integración en `src/test/java`.
 
 ## Agradecimientos 
¡Gracias por interesarte por la aplicación! Si tienes dudas, sugerencias o deseas contribuir, no dudes en abrir un issue o enviar un pull request.

