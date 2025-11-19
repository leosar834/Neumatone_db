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
- **SQL (DDL y DML)**  

---

## 📥 Instalación y uso  
1. Clona este repositorio:
- git clone https://github.com/leosar834/Neumatone_db.git
- Instala Laragon a traves de este link
- Una vez instalado crea una base datos usando estos comandos:
######1. mysql -u root -p
######2. password: (enter)
######3. create database coloquio
- Luego vamos a importar la db que clonaste del repositorio 
######4. exit
######5. mysql -u root -p  coloquio < D:\laragon\coloquio.sql

Eso voy por ahora como deberia seguir(es solo la parte de instalacion)
git clone https://github.com/leosar834/Neumatone_db.git
