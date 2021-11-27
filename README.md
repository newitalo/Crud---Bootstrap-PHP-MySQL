# Crud:Bootstrap-PHP-MySQL

Para esse crud foram utilizados as seguintes aplicações:

*📌 PHP*
*📌 XAMMP*
*📌 BOOTSTRAP*
*📌 CSS*
*📌 MYSQL*
*📌 JS*

___________________________________________________________________

Para crianção das tabelas no SQL foram utilziados os seguintes comandos:

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
  
___________________________________________________________________

  
