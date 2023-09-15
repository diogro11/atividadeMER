# atividadeMER

CREATE TABLE locadora_aut(
automovel varchar(200),
placa varchar (20) not null,
modelo varchar (50),
ano int,
montadora varchar (200),
site varchar (200)
);
INSERT INTO locadora_aut VALUES ('1','HIw9876','gol','2009','volkswagen','volsks.org.br');
INSERT INTO locadora_aut VALUES ('2','HIt823','polo','2012','volkswagen','volsks.org.br'); 
INSERT INTO locadora_aut VALUES ('3','fgv326','palio','2009','fiat','fiat.org.br');
INSERT INTO locadora_aut VALUES ('4','Hva876','onix','2015','chevrolet','GM.org.br');
INSERT INTO locadora_aut VALUES ('5','FTW9876','uno','2005','fiat','fiat.org.br');
select * from locadora_aut
