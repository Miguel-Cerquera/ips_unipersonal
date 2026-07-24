# 🏥 IPS Unipersonal

Aplicación web desarrollada en **Java** como proyecto académico para el curso **Técnicas de Programación**. El sistema permite gestionar el agendamiento y consulta de citas médicas para una IPS unipersonal, implementando funcionalidades básicas de administración de citas mediante una arquitectura basada en **JSP, Servlets y MySQL**.

## 📋 Descripción

El objetivo del proyecto fue aplicar los fundamentos del desarrollo de aplicaciones web en Java, integrando persistencia de datos, lógica de negocio y una interfaz web sencilla para simular el funcionamiento de un sistema de agendamiento de citas.

La aplicación permite consultar la disponibilidad de horarios, registrar nuevas citas y realizar búsquedas utilizando el número de identificación del paciente.

## ✨ Funcionalidades

* Agendamiento de citas médicas.
* Consulta de citas por número de cédula.
* Verificación de disponibilidad de horarios.
* Consulta de horarios disponibles por fecha.
* Persistencia de la información en MySQL.

## 🛠️ Tecnologías utilizadas

* Java 8
* Jakarta EE (Servlets y JSP)
* Apache Maven
* MySQL
* JDBC
* HTML5
* CSS3

## 📂 Estructura del proyecto

```
src
└── main
    ├── java
    │   ├── controller
    │   ├── db
    │   └── model
    └── webapp
        ├── css
        ├── views
        └── WEB-INF
```

## 🏛️ Arquitectura

El proyecto sigue una organización basada en el patrón **Modelo-Vista-Controlador (MVC)**:

* **Modelo:** gestión de las entidades y acceso a datos mediante JDBC.
* **Vista:** páginas JSP encargadas de la interacción con el usuario.
* **Controlador:** Servlets responsables de procesar las solicitudes HTTP y coordinar la lógica de la aplicación.

## ⚙️ Requisitos

* Java JDK 8 o superior
* Apache Maven
* Servidor de aplicaciones compatible con Jakarta/Java EE (por ejemplo, Apache Tomcat)
* MySQL

## 🚀 Instalación

1. Clonar el repositorio.

```bash
git clone <URL_DEL_REPOSITORIO>
```

2. Crear una base de datos llamada:

```sql
ips
```

3. Configurar las credenciales de conexión en:

```
src/main/java/com/ips/db/DB.java
```

4. Compilar el proyecto:

```bash
mvn clean package
```

5. Desplegar el archivo `.war` generado en el servidor de aplicaciones.

## 📸 Capturas

> Se recomienda agregar capturas de la interfaz principal, el formulario de agendamiento y las consultas de citas para ilustrar el funcionamiento de la aplicación.

## 🎓 Contexto académico

Este proyecto fue desarrollado como parte del curso **Técnicas de Programación**, con el propósito de fortalecer conocimientos sobre desarrollo web en Java, interacción con bases de datos relacionales y organización del código siguiendo una arquitectura MVC.

## 👨‍💻 Autor

**Miguel Cerquera**
