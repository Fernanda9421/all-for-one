# All For One

Esse projeto foi desenvolvido durante o curso de Desenvolvimento Web, na Trybe.



## Sumário

- [Tecnologias utilizadas](#tecnologias-utilizadas)
- [Habilidades](#habilidades)
- [Contexto](#contexto)
- [Data de desenvolvimento do projeto](#data-de-desenvolvimento-do-projeto)
- [Instruções para clonar o projeto](#instruções-para-clonar-o-projeto)
- [Requisitos propostos pela Trybe](#requisitos-propostos-pela-trybe)



### Tecnologias utilizadas

- SQL



### Habilidades

- Ambiente local de desenvolvimento, com fins de praticar SQL
- MySQL Workbench
- Estrutura de *querys* SQL



### Contexto

Esse projeto foi desenvolvido com o objetivo de praticar *querys* em SQL, sua estrutura e aplicabilidade.



### Data de Desenvolvimento do Projeto

- Março / 2022



### Instruções para clonar o projeto

1. Clone o repositório

   - `git clone git@github.com:Fernanda9421/all-for-one.git`
   - Entre na pasta que você acabou de clonar:
     - `cd all-for-one`

   2. Instale as dependências e inicialize o projeto

     * Instale as dependências:

       * `npm install`



### Requisitos propostos pela Trybe

OBS.: Todos os requisitos abaixo foram criado pela TRYBE



1. Exibir os nomes dos produtos na tabela **`products`**
2. Exibir os dados de todas as colunas da tabela **`products`**
3. Exibir os valores da coluna que representa a primary key da tabela **`products`**
4. Contar quantos registros existem na coluna **`product_name`** da tabela **`products`**
5. Exibir os dados da tabela **`products`** a partir do quarto registro até o décimo terceiro
6. Exiba os dados das colunas **`product_name`** e **`id`** **da tabela** **`products`** , em ordem alfabética dos nomes
7. Mostrar os ids dos 5 últimos registros da tabela **`products`** , ordenados pela coluna **`id`**
8. Retornar três colunas, respectivamente, com os nomes 'A', 'Trybe' e 'eh', e com valores referentes a soma de '5 + 6', a string 'de', a soma de '2 + 8'
9. Mostrar todos os valores de **`notes`** da tabela **`purchase_orders`** que não são nulos
10. Mostrar todos os dados da tabela **`purchase_orders`** em ordem decrescente, ordenados por **`created_by`** em que o **`created_by`** é maior ou igual a 3
11. Exibir os dados da coluna **`notes`** da tabela **`purchase_orders`** em que seu valor de **`Purchase generated based on Order`** é maior ou igual a 30 e menor ou igual a 39
12. Mostrar as **`submitted_date`** de **`purchase_orders`** em que a **`submitted_date`** é do dia 26 de abril de 2006
13. Mostrar o **`supplier_id`** das **`purchase_orders`** em que o **`supplier_id`** seja 1 ou 3
14. Mostre os resultados da coluna **`supplier_id`** da tabela **`purchase_orders`** em que o **`supplier_id`** seja maior ou igual a 1 e menor ou igual 3
15. Mostrar somente as horas da coluna **`submitted_date`** ** todos registros da tabela* **`purchase_orders`**
16. Exibir a **`submitted_date`** das **`purchase_orders`** que estão entre **`2006-01-26 00:00:00`** **e** **`2006-03-31 23:59:59`**
17. Mostrar os registros das colunas **`id`** **e** **`supplier_id`** **das** **`purchase_orders`** em que os **`supplier_id`** sejam tanto 1, ou 3, ou 5, ou 7
18. Mostrar todos os registros de **`purchase_orders`** que tem o **`supplier_id`** igual a 3 e **`status_id`** igual a 2
19. Mostrar a quantidade de pedidos que foram feitos na tabela **`orders`** pelo **`employee_id`** igual a 5 ou 6, e que foram enviados através do método(coluna) **`shipper_id`** igual a 2
20. Adicionar à tabela **`order_details`** um registro com **`order_id`**: 69, **`product_id`**: 80, **`quantity`**: 15.0000, **`unit_price`**: 15.0000, **`discount`**: 0, **`status_id`**: 2, date_allocated:` NULL`, purchase_order_id:` NULL` e inventory_id: `129`
21. Adicionar com um único **`INSERT`**, duas linhas à tabela **`order_details`** com os mesmos dados do requisito 20
22. Atualizar os dados de **`discount`** do **`order_details`** para 15
23. Atualizar os dados da coluna **`discount`** da tabela **`order_details`** para 30, onde o valor na coluna **`unit_price`** seja menor que 10.0000
24.  Atualizar os dados da coluna **`discount`** da tabela **`order_details`** para 45, onde o valor na coluna **`unit_price`** seja maior que 10.0000 e o id seja um número entre 30 e 40
25. Deletar todos os dados em que a **`unit_price`** da tabela **`order_details`** seja menor que 10.0000
26. Deletar todos os dados em que a **`unit_price`** da tabela **`order_details`** seja maior que 10.0000
27.  Delete todos os dados da tabela **`order_details`**.