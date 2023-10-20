# AGENDA-PHP
Foi criado uma agenda em PHP a qual cadastra o nome, telefone e observação. Tem a visualização por id do cadastro, atualização por id do cadastro e remoção do campo. Um projeto CRUD para estudos da linguagem PHP sem frameworks. 


CRIANDO BANCO DE DADOS NO PHPMYADMIN 

nome do banco: agenda 

usuario: root

senha: ""

Código SQL para criação da table : 

CREATE TABLE contacts (
	id INT UNSIGNED AUTO_INCREMENT PRIMARY KEY, 
	name VARCHAR(150), 
	phone VARCHAR(20), 
	observations TEXT

);
