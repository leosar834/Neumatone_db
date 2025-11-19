# Neumatone_db

## 📌 Descripción
**Neumatone_db** es el modelo de base de datos diseñado para la gestión integral de una empresa del rubro automotriz y gomería.  
Incluye el esquema relacional completo, las tablas necesarias, sus relaciones, claves primarias, claves foráneas y estructura normalizada.

Este repositorio contiene los archivos SQL que permiten crear y mantener la base de datos en **MySQL** o **MySQL Workbench**.

---

## 🎯 Objetivo del Proyecto
El propósito del proyecto es proporcionar una base de datos sólida, escalable y bien estructurada que permita gestionar:

- Clientes  
- Vehículos  
- Productos y neumáticos  
- Servicios  
- Ventas  
- Empleados  
- Turnos / horarios  
- Estados del sistema (ventas, usuarios, vehículos, etc.)

La base de datos está pensada para un sistema de administración completo para una gomería/taller.

---

## 🧩 Características principales
- Modelo de datos normalizado (hasta **3FN**).  
- Manejo completo de **relaciones 1:N**, **N:M**, y estructuras auxiliares.  
- Uso de **claves primarias**, **foráneas**, índices y restricciones.  
- Scripts SQL listos para ejecutar en MySQL.  
- Compatible con MySQL Workbench (incluyendo diagramas EER).  
- Pensada para integrarse a un sistema real de facturación, ventas y administración.

---

## 🛠️ Tecnologías utilizadas
- **MySQL 8+**  
- **MySQL Workbench**  
- **Laragon**
- **Excel** 

---
## 📥 Instalación y uso  
1. Clona este repositorio:
- git clone https://github.com/leosar834/Neumatone_db.git
- Puedes utilizar un sistema web o cualquier otra aplicacion ya sea PHPMyAdmin, Laragon, MySQL Workbech u otra.
- Una vez instalado crea una base datos usando estos comandos:
  	- mysql -u root -p
	- password: (enter)
	- create database coloquio
 	- exit 
- Luego vamos a importar la db que clonaste del repositorio 

#### ❗❗ Importante
A la hora de hacer el import se tiene en cuenta las credenciales, el nombre de la db a la que importaremos, la direccion del archivo sql y el propio sql. De lo contrario no se importara de manera correcta la db.
- Un ejemplo de el import seria así:
	- mysql -u root -p  coloquio < D:\laragon\coloquio.sql

2. Una vez hecho eso ya puedes realizar consultas o modificar el contenido de las tablas a tus preferencias.

	- SELECT * FROM venta LIMIT 10;
	- SELECT * FROM producto LIMIT 10;

4.  Después de importar el archivo SQL, es recomendable comprobar que todo se creó correctamente:
- mysql -u root -p
- password: ""(enter)
- USE coloquio;
- SHOW TABLES;


Deberías ser capaz de ver todas las tablas creadas, como cliente, vehiculo, producto, venta, etc.

## 📋Diagrama ER
<img width="1986" height="1392" alt="coloquio" src="https://github.com/user-attachments/assets/ae23c7f0-ef96-48e1-b253-2f8b976133d6" />


## 🤝 Cómo Contribuir

Si querés mejorar el proyecto:

Hacé un Fork del repositorio

Creá un branch nuevo (feature/lo-que-vas-a-hacer)

Subí los cambios

Enviá un Pull Request


## 👤 Autor

Desarrollado por leoSar834

GitHub: https://github.com/leosar834

## 🖥 Catedra Base de Datos 
