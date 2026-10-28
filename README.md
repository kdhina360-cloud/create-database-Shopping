create database shopping;
use shopping;
create table shop (
shop_id int primary key,
shop_name varchar(50) not null,
product_name varchar(50) not null,
price decimal (10,2) not null
);

insert into shop (shop_id,shop_name,product_name,price)
values
(103,"SK store","grocery",150),
(102,"DK store","Accessories",180.50);
select * from shop;

