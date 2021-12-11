# Proyecto-Final-prog1
https://youtu.be/D4g6JaJ6L98

https://youtu.be/ycUyYg3UABo


script creacion base de datos:


create database DBuser
create table usuarios(
id int primary key AUTO_INCREMENT,
usuario varchar(45) not null,
password varchar(45) not null,
Cpassword varchar(45) not null,
nombre varchar(50) not null,
apellido varchar(65) not null,
telefono varchar(15) not null,
correo varchar(70) not null
);

create table productos(
id int primary key auto_increment,
nombrep varchar(140),
marcap varchar(140),
categoriap varchar(140),
precio varchar(30),
stock varchar(30)

);

drop table productos

select* from usuarios
select* from productos
