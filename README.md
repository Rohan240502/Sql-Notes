# Sql-Notes
These notes contains basic and medim level sql commands used for quick recap.

1. Important queries the sql query :

create database "tablename";
USE "tablename";
create table user(
id int auto_increment primary key,
name varchar(100) not null,
email varchar(100) unique not null,
gender enum('Male','Female','Other'),
date_of_birth Date,
created_at timestamp default current_timestamp
);
select * from user;
