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

COMO USAR:
1. Instale o XAMPP e starta o Apache e MySQL.
2. Faz o git clone do projeto dentro da pasta XAMPP/HTDOCS no disco C:
3. No navegador, coloca http://localhost/AGENDA-PHP/ para acessar o projeto e interagir.
4. No navegador, coloca http://localhost/phpmyadmin/ para acessar o phpmyadmin banco de dados e criar o banco local via SQL.
