# Prueba2POO
# Wilson Guayanay

Script de la base de datos

CREATE DATABASE FARMACIA

USE FARMACIA

CREATE TABLE PRODUCTOS(
Id_Clie numeric(10) not null,
Nom_Clie varchar(20)not null,
Cant_Clie varchar(3)not null,
Dir_Clie varchar(25)not null
)

CREATE TABLE CIUDAD(
Nom_Ciu varchar(10) not null
)

CREATE TABLE NOMBREPRODUCTOS(
Prod_nom varchar(10) not null
)

Insert Into CIUDAD VALUES('Quito')
Insert Into CIUDAD VALUES('Guayaquil')
Insert Into CIUDAD VALUES('Cuenca')

Insert Into NOMBREPRODUCTOS VALUES('Pastillas')
Insert Into NOMBREPRODUCTOS VALUES('Jarabe')
Insert Into NOMBREPRODUCTOS VALUES('Pañales')
