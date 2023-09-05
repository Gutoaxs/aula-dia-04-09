# aula-dia-04-09

CREATE TABLE sql_aluno_a
(
  RA INT,
  NOME VARCHAR (200),
  NASCIMENTO DATA,
  ENDERECO VARCHAR (500),
  EMAIL VARCHAR (200)
);
 
  INSERT INTO sql_aluno_a (RA, NOME, NASCIMENTO, ENDERECO, EMAIL) VALUES ('235269', 'Augusto', '2000-11-14', 'Av. Fernando Stecca', 'gutoaxavier@gmail.com');
  INSERT INTO sql_aluno_a (RA, NOME, NASCIMENTO, ENDERECO, EMAIL) VALUES ('486916', 'Diogo', '2002-09-26', 'Av. Dr. Ulisses Guimaraes', 'diogo_2002@gmail.com');
  INSERT INTO sql_aluno_a (RA, NOME, NASCIMENTO, ENDERECO, EMAIL) VALUES ('295710', 'Ketillyn', '2001-12-11', 'Rua Curio', 'ket_silva@gmail.com');
  INSERT INTO sql_aluno_a (RA, NOME, NASCIMENTO, ENDERECO, EMAIL) VALUES ('859375', 'Pedro', '2001-01-01', 'Rua XV de Novembro', 'pedropedroso@gmail.com');
  INSERT INTO sql_aluno_a (RA, NOME, NASCIMENTO, ENDERECO, EMAIL) VALUES ('917461', 'Fernanda', '2006-06-06', 'Av. Bruxelas', 'fernandinha_htinha@yahoo.com');
  
  SELECT RA, NOME, NASCIMENTO, ENDERECO, EMAIL FROM sql_aluno_a
