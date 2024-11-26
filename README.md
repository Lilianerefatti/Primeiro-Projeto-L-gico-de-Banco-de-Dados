# Primeiro-Projeto-Logico-de-Banco-de-Dados
Primeiro Projeto Lógico de Banco de Dados_E-commerce

Esse desafio inclui a criação, inserção e manipulação de dados para construir um banco de dados funcional que pode ser usado para gerenciar um e-commerce.

Criação de Tabelas:
Seller: Tabela para armazenar informações sobre os vendedores, como nome social, CPF, CNPJ, tipo de frete, endereço, e outros dados.
Product: Tabela que armazena detalhes dos produtos, como nome, categoria, avaliação, preço, tamanho, peso e descrição.
Entregas: Tabela para informações sobre as entregas, incluindo o status da entrega, código de rastreamento, datas de envio, previsão de entrega, entre outros.
Avaliações de produtos: Tabela para armazenar as avaliações de produtos feitas pelos clientes, incluindo notas e comentários.
clients: Tabela para armazenar informações dos clientes, como nome, CPF, endereço, telefone e email.
Pedidos: contém informações detalhadas sobre cada transação feita por um cliente

Inserção de Dados:
Dados de vendedores (Seller), como nome social, CPF, CNPJ, e outros atributos.
Dados de produtos (Product), incluindo nomes, categorias, avaliações e preços.
Dados de clientes (clients), como nome, CPF, endereço, etc.
Dados de entregas, incluindo status, código de rastreamento, data de envio e previsão de entrega.
Dados de avaliações de produtos, com notas e comentários.

Consultas SQL:
Realizadas consultas para responder a perguntas como:
Recuperar os vendedores que possuem mais de 3 produtos com avaliações superiores a 4.
Recuperar os dados do cliente, vendedor, produto, status de entrega e valor do pedido.
Utilizadas cláusulas como JOIN, WHERE, CASE, GROUP BY, HAVING, e ORDER BY para obter e organizar os dados conforme as necessidades.

Correções de Erros:
Corrigidos problemas como campos ambíguos nas consultas (como idProduct), e erros de tabela inexistente (como a tabela Customer que na verdade era clients).
Relacionamentos entre as Tabelas:

Estabelecidos relacionamentos entre tabelas como:
Seller com Product (um vendedor pode ter muitos produtos).
Product com Avaliações de produtos (um produto pode ter muitas avaliações).
Entrega com Product e clients (uma entrega está associada a um produto e a um cliente).
