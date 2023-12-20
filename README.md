# Data WareHouse - Ecommerce

![Data_Warehouse_Ecommerce_MySQL](https://github.com/luishenriquebk/data_warehouse_ecommerce/assets/102004702/c4bdfa76-fc57-49dc-a0ba-ab41a145da78)

Este repositório contém atividades realizadas no MySQL para praticar conceitos de criação de Data Waerehouse no MySQL.
#### Link do projeto: https://drive.google.com/drive/folders/17Gvu0HAjMDH-WaQdoFAAl-BXPbeGXaPC?usp=sharing

O Data Warehouse criado é uma estrutura de banco de dados projetada para armazenar e gerenciar informações de um fictício e-commerce de maneira otimizada para análise e consulta. Composto por várias entidades inter-relacionadas, o esquema inclui tabelas que abrangem informações cruciais para o negócio.

### Entidades Criadas

#### CLIENTE - Armazena informações sobre os clientes.
#### PRODUTO - Contém detalhes sobre os produtos.
#### PEDIDO  - Registra os pedidos feitos pelos clientes, relacionando clientes e produtos
#### FUNCIONARIO - Armazena informações sobre os funcionários.
#### ENVIO   - Registra os detalhes do envio dos produtos, relacionando pedidos e funcionários.

### Relacionamentos e Cardinalidades

Clientes ↔ Pedidos (um para muitos)
Produtos ↔ Pedidos (um para muitos)
Funcionários ↔ Envios (um para muitos)
Pedidos ↔ Envios (um para muitos)
