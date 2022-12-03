# programacaoWebCrud
Crud em PHP referente a atividade de Programação Web

Helton Vinícios Avelino Diniz RGM: 30944279

OBS: para a criacao do banco de dados:

utilizando o PHPMYADMIN:

create database aulaprogweb;
use aulaprogweb;

create table tab_pessoa (
    cod_pessoa int Primary Key auto_increment,
    nome varchar(100),
    cpf varchar(14),
    email varchar(100)
);
