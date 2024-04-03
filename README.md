# jsp
CREATE SCHEMA cadastro ;
use cadastro;

CREATE TABLE cliente (
`id`  INT NOT NULL AUTO_INCREMENT , 
`nome` VARCHAR (45) NULL,
`login` VARCHAR (45) NULL,
`senha` VARCHAR (45) NULL,
`endereco` VARCHAR (45) NULL,
`contato` VARCHAR (45) NULL,
PRIMARY KEY (`id`));

INSERT INTO cliente(nome,sobrenome,login,senha,endereco,contato)
VALUES ('lUIZ','Brasilia','brasilia',md5('teste'),'lago','61992018105');

SELECT * FROM cliente;
