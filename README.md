# 🏥 IPS Unipersonal

Sistema web para la gestión de citas médicas de una IPS unipersonal, desarrollado en **Java** utilizando **Servlets**, **JSP**, **JDBC** y **MySQL**. La aplicación implementa una arquitectura **Modelo-Vista-Controlador (MVC)** para separar la lógica de negocio, el acceso a datos y la interfaz de usuario, permitiendo administrar el proceso de agendamiento y consulta de citas médicas.

## 📖 Descripción

Este proyecto fue desarrollado con el objetivo de aplicar los fundamentos del desarrollo de aplicaciones web en Java, integrando persistencia de datos, programación orientada a objetos y una arquitectura organizada por capas.

La aplicación permite registrar citas médicas, consultar la disponibilidad de horarios y buscar las citas asociadas a un paciente mediante su número de identificación.

## ✨ Funcionalidades

* Registro de citas médicas.
* Consulta de citas por número de cédula.
* Verificación de disponibilidad de horarios.
* Consulta de horarios disponibles.
* Persistencia de la información en una base de datos MySQL.

## 🛠️ Tecnologías utilizadas

* Java
* Jakarta Servlets
* JSP (JavaServer Pages)
* JDBC
* MySQL
* Apache Maven
* HTML5
* CSS3

## 🏛️ Arquitectura

El proyecto sigue una arquitectura basada en el patrón **Modelo-Vista-Controlador (MVC)**.

* **Modelo:** representa las entidades del sistema y encapsula el acceso a la base de datos mediante JDBC.
* **Vista:** páginas JSP encargadas de la interacción con el usuario.
* **Controlador:** Servlets responsables de procesar las solicitudes HTTP y coordinar la comunicación entre la vista y el modelo.

Esta organización facilita el mantenimiento del código y promueve una clara separación de responsabilidades.

## 💡 Habilidades demostradas

Este proyecto evidencia conocimientos en:

* Desarrollo de aplicaciones web con Java.
* Programación Orientada a Objetos.
* Arquitectura MVC.
* Desarrollo de Servlets y JSP.
* Persistencia de datos mediante JDBC.
* Integración con bases de datos MySQL.
* Gestión de solicitudes HTTP.
* Organización de proyectos con Apache Maven.

## 📂 Estructura del proyecto

```text
src
└── main
    ├── java
    │   ├── controller
    │   ├── db
    │   └── model
    ├── resources
    └── webapp
        ├── css
        ├── views
        └── WEB-INF
```

## ⚙️ Requisitos

* Java JDK 8 o superior.
* Apache Maven.
* Servidor de aplicaciones compatible con Jakarta EE (por ejemplo, Apache Tomcat).
* MySQL.

## 🚀 Instalación

1. Clonar el repositorio.

```bash
git clone https://github.com/Miguel-Cerquera/ips_unipersonal.git
```

2. Crear la base de datos utilizada por la aplicación.

3. Configurar las credenciales de conexión en la clase correspondiente a la conexión con MySQL.

4. Compilar el proyecto mediante Maven.

```bash
mvn clean package
```

5. Desplegar el archivo `.war` generado en el servidor de aplicaciones.

## 📸 Capturas

Se pueden incluir imágenes de:

* Página principal.
* Formulario de registro de citas.
* Consulta de citas.
* Consulta de horarios disponibles.

## 🎓 Contexto académico

Proyecto desarrollado como parte del curso **Técnicas de Programación**, enfocado en la construcción de aplicaciones web utilizando Java y bases de datos relacionales. El objetivo principal fue aplicar conceptos de programación orientada a objetos, desarrollo web y persistencia de datos en un caso de uso cercano a un entorno real.

## 👨‍💻 Autor

**Miguel Cerquera Arias**
