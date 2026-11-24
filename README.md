# Sistema de ventas para una librería
Proyecto grupal desarrollado para el curso de **Lenguaje de Programación I** en Cibertec. 
Aplicación web con Java (servlets, JSP, JDBC, patrones DAO y Factory, filtros, listeners, custom tag y AJAX) y base de datos MySQL.

## Integrantes

| Integrante | Rol |
|---|---|
| I1 - Raúl Aarón Izaguirre Olortegui | Coordinación y plataforma |
| I2 (nombre) | Catálogo |
| I3 (nombre) | Clientes y acceso |
| I4 (nombre) | Transacción de venta |
| I5 (nombre) | Datos y reportes |

## Tecnologías
- Java 21 LTS (compatible también con JDK 25; el proyecto compila con `--release 21`).
- Eclipse IDE for Enterprise Java and Web Developers
- Apache Tomcat v9.0 (Servlet 4.0), registrado en Eclipse con el nombre exacto `Apache Tomcat v9.0`.
- MySQL 8
- MySQL Connector/J 9.1.0 (en `src/main/webapp/WEB-INF/lib/`).
- Bootstrap 5

> No usar Tomcat 10/11 sin migrar el código: usan `jakarta.servlet.*` y este proyecto es Servlet 4.0 (`javax.servlet.*`).

## Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. En MySQL Workbench, ejecutar en este orden los scripts de la carpeta `sql/`: `01_esquema.sql`, `02_datos.sql` y `03_procedimientos.sql`.
3. En Eclipse: File → Import → Existing Projects into Workspace.
4. Verificar la configuración del proyecto: Java Compiler 21 y Project Facets → Java 21 / Dynamic Web Module 4.0. Funciona con JDK 21 o JDK 25.
5. Registrar Tomcat con el nombre exacto `Apache Tomcat v9.0` y ejecutar Run on Server.
6. Abrir `http://localhost:8080/libreria-ventas/login`.
