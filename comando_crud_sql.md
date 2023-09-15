# Comandos SQL - Para CRUD

## Resumo
C -> Create (Insere dados)
R -> Read (ler dados)
U -> Update (Atualizar dados)
D -> Delete (Deletar dados)
<!-- __________________________________________ -->
## Insert
## Fabricantes


```sql
    INSERT INTO fabricantes (nome) VALUES ('Asus');
    INSERT INTO fabricantes (nome) VALUES ('Dell');
    INSERT INTO fabricantes (nome)
    VALUES ('Apple'), ('LG'), ('Samsung'), ('Brastemp');
```

## Insert
## Fabricantes

```sql
    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('Ultrabook', 'Ultrabook Asus Intel Core i9', 
    6500.99,
    7,
    1
    );

    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('Geladeira', 'Frost-Free com acesso a internet', 
    8500.99,
    7,
    1
    );

    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('Tablet Android', 'Tablet 10 polegadas com 256Gb de armazenamento', 
    4999,
    3,
    5
    );

    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('iPhone 14 Pro Max', 'Processador Bionic 15 com 512Gb de armazenamento', 
    9999.97,
    3,
    1
    );

    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id) VALUES ('Asus');
    VALUES('ipad mini', 'Tablet com tela de retina 4k com 516Gb de armazenamento', 
    5000,
    8,
    1
    );

```

```sql
    INSERT INTO fabricantes (nome)
    VALUES ('Positivo'),('Microsoft');
```   

```sql
    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('Xobx', 'Console de última geração...', 
    2500,
    6,
    8
    );

    INSERT INTO produtos (nome, descricao, preco, quantidade, fabricante_id)
    VALUES('Ultrabook', 'AMD Ryzen 5 16Gb RAM', 
    4500,
    12,
    7
    );


```   