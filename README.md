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
- Java
- Eclipse IDE for Enterprise Java and Web Developers
- Apache Tomcat v9.0
- MySQL 8
- Bootstrap 5

## Cómo ejecutar el proyecto
1. Clonar el repositorio.
2. En MySQL Workbench, ejecutar en este orden los scripts de la carpeta `sql/`: `01_esquema.sql`, `02_datos.sql` y `03_procedimientos.sql`.
3. En Eclipse: File → Import → Existing Projects into Workspace.
4. Registrar Tomcat con el nombre acordado por el equipo y ejecutar Run on Server.
5. Abrir `http://localhost:8080/libreria-ventas/login`.
