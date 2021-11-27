
Sobre o conteúdo: <img align="right" height="50" style="border-radius:50px;" src="https://media.discordapp.net/attachments/725284103469006880/913978577354100766/kisspng-don-t-panic-the-official-hitchhiker-s-guide-to-th-5ada1a066c3658.0538018815242429504433.png?width=738&height=676">
=================

*Crud feito com Bootstrap, PHP e MYSQL*
 <br>
 <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-plain-wordmark.svg">
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/php/php-original.svg">
  <img align="center" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg">
  
<h1>Pre-requisitos</h1>
<h4>
XAMPP, Editor de texto (Neste caso utilizei o VSCODE), Node.js, NPM e Bootstrap
</h4>

<h3> Estes foram os arquivos criados durante a criação do CRUD.
  (Sem a inclusão do <a href= "https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/config.php">config.php</a>
  e <a href= "https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/index.php">index.php</a>) </h3>
      
* <a href= "https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/tree/main/crud">Crud</a>
     
   * <a href= "https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/tree/main/crud/customers">customers</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/add.php">add.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/delete.php">delete.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/edit.php">edit.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/functions.php">functions.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/index.php">index.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/modal.php">modal.php</a>
      * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/customers/view.php">view.php</a>
  * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/tree/main/crud/inc"> inc </a>
    * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/inc/database.php">database.php</a>
    * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/inc/footer.php">footer.php</a>
    * <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/crud/inc/header.php">header.php</a>

<h3>Tabelas criadas no <a href="https://github.com/newitalo/Crud---Bootstrap-PHP-MySQL/blob/main/SQL"> SQL </a></h3>
	

	
	
	CREATE TABLE customers (
  	id int(11) NOT NULL,
 	 	name varchar(255) NOT NULL,
  	cpf_cnpj varchar(14) NOT NULL,
  	birthdate date NOT NULL,
  	address varchar(255) NOT NULL,
  	hood varchar(100) NOT NULL,
  	zip_code int(8) NOT NULL,
  	city varchar(100) NOT NULL,
  	state varchar(100) NOT NULL,
  	phone int(13) NOT NULL,
  	mobile int(13) NOT NULL,
  	ie int(11) NOT NULL,
  	created datetime NOT NULL,
  	modified datetime NOT NULL
	);

	ALTER TABLE customers
  	ADD PRIMARY KEY (id);
  
	ALTER TABLE customers
  	MODIFY id int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=1;
		
__________________________________
<h2>Prints</h2>

*DASHBOARD:*

<img align="center" height="330" style="border-radius:50px;" src="https://media.discordapp.net/attachments/725284103469006880/913979468090081340/dashbord_42.png?width=1202&height=676">

*CRIAR CLIENTE:*

<img align="center" height="330" style="border-radius:50px;" src="https://media.discordapp.net/attachments/725284103469006880/913976928728383498/CREATE_FULL.png?width=1202&height=676">

*DELETAR CLIENTE:*

<img align="center" height="330" style="border-radius:50px;" src="https://media.discordapp.net/attachments/725284103469006880/913977455465877515/delete_full.png?width=1202&height=676">

*EDITAR CLIENTE:*

<img align="center" height="330" style="border-radius:50px;" src="https://media.discordapp.net/attachments/725284103469006880/913979818985529344/EDITAR_FULL.png?width=1202&height=676">
















	
  
 
    
