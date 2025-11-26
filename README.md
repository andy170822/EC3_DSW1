# EC3_DSW1
Sistema de Gestión de Transporte

Sistema web para la gestión integral de conductores y vehículos desarrollado con Spring Boot 3 y Thymeleaf.

Características

CRUD completo de conductores y vehículos

Búsqueda y filtrado avanzado

Dashboard con estadísticas

Validaciones de negocio en tiempo real

Interfaz responsive con Bootstrap 5

Base de datos SQL Server

Relación 1:N entre conductores y vehículos

Requisitos

Java 21+

Maven 3.8+

SQL Server 2019+

IDE (NetBeans, IntelliJ IDEA o Eclipse)

Instalación

Clonar el repositorio

git clone https://github.com/tu-usuario/transport-management.git
cd transport-management


Configurar base de datos

CREATE DATABASE transport_db;


Configurar credenciales en application.properties

spring.datasource.username=tu_usuario
spring.datasource.password=tu_password


Compilar el proyecto

mvn clean install

Ejecución
mvn spring-boot:run


Acceder a: http://localhost:8080

Capturas
Dashboard

Insertar captura del dashboard

Gestión de Conductores

Insertar captura de lista de conductores

Gestión de Vehículos

Insertar captura de lista de vehículos

Tecnologías

Backend: Spring Boot 3.2.0, Java 21

Frontend: Thymeleaf, Bootstrap 5, HTML5/CSS3

Base de Datos: SQL Server

ORM: Hibernate / JPA

Build Tool: Maven
Estructura del proyecto
src/
├── main/
│   ├── java/com/idat/pe/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── entity/
│   │   ├── dto/
│   │   └── mapper/
│   └── resources/
│       ├── templates/
│       └── application.properties
└── test/
Autor

Anderson Montero
Desarrollo de sistemas de informacion - IDAT

Licencia

Este proyecto fue desarrollado con fines educativos.
