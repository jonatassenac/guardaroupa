guardaroupa
===========

Projeto Guarda Roupa Virtual

CREATE TABLE USUARIO(
id_usuario number(5),
nome varchar2(100),
sexo varchar2(10),
idade varchar2(3),
cpf varchar2(11),
PRIMARY KEY (id_usuario)
);

select * from "SYSTEM".USUARIO;

CREATE TABLE LOJA(
id_loja number(5),
nome varchar2(100),
end varchar2(50),
PRIMARY KEY (id_loja)
);

select * from "SYSTEM".LOJA;

CREATE TABLE PRODUTO(
id_produto number(5),
categoria varchar2(100),
tamanho varchar2(10),
preço varchar2(100),
modelo varchar2(20),
PRIMARY KEY (id_produto)
);

SELECT * from "SYSTEM".PRODUTO;
