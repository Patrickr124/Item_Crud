### O que devo fazer?
Crie uma tabela fictícia e depois faça uma query para cada item de um CRUD - Criar uma linha, selecionar(ler), editá-la e apaga-la.

### Estrutura da Tabela
**Tabela - produtos**
id_produto (número, PK)

nome (string)

descricao (string)

preco (número flutuante)

data_adicao (data)

### Queries 

### Criar uma linha (Create)
INSERT INTO produtos (id_produto, nome, descricao, preco, data_adicao) VALUES
(1, 'Smartphone', 'Smartphone com 8GB de RAM e 128GB de armazenamento', 2500.00, '2024-11-16');

### Selecionar (ler) uma linha (Read)
SELECT * FROM produtos WHERE id_produto = 1;

### Editar uma linha (Update)
UPDATE produtos SET preco = 2300.00 WHERE id_produto = 1;

### Apagar uma linha (Delete)
DELETE FROM produtos WHERE id_produto = 1;
