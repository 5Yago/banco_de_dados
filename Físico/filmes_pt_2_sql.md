# Comando SQL - CRUD (referência)

## Resumo
sql
INSERT INTO generos (genero) 
VALUE ('Ação'),('Terror'),('Comédia'),('Roamnce');



## Inserir filmes
```sql

INSERT INTO filmes (titulo, lançamento,  genero_id) 
VALUES ('Velozes e furiosos 3',
'2006',
1
);
INSERT INTO filmes (titulo, lançamento,  genero_id) 
VALUES ('Fale comigo',
'2022',
2
);
INSERT INTO filmes (titulo, lançamento,  genero_id) 
VALUES ('Dose Dupla',
'2013',
3
);
INSERT INTO filmes (titulo, lançamento,  genero_id) 
VALUES ('La La Land',
'2017',
4
);