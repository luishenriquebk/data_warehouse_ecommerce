# Data WareHouse - Ecommerce

![Data_Warehouse_Ecommerce_MySQL](https://github.com/luishenriquebk/data_warehouse_ecommerce/assets/102004702/c4bdfa76-fc57-49dc-a0ba-ab41a145da78)

Este repositório contém atividades realizadas no MySQL para praticar conceitos de criação de Data Waerehouse no MySQL.
#### Link do projeto: https://drive.google.com/drive/folders/17Gvu0HAjMDH-WaQdoFAAl-BXPbeGXaPC?usp=sharing

Este projeto consiste em um Data Warehouse elaborado para gerenciar informações de um e-commerce fictício. A estrutura foi cuidadosamente projetada visando a otimização para análises e consultas, permitindo uma compreensão aprofundada das operações do negócio.

### Entidades Principais

*   **Cliente**: Armazena informações detalhadas sobre os clientes, incluindo nome e email.
    
*   **Produto**: Contém informações específicas sobre os produtos oferecidos, como nome e preço.
    
*   **Pedido**: Registra pedidos feitos pelos clientes, conectando clientes e produtos adquiridos.
    
*   **Funcionário**: Armazena dados dos funcionários envolvidos no processo, como nome e cargo.
    
*   **Envio**: Registra detalhes do envio dos produtos, associando-os aos pedidos e funcionários responsáveis pela entrega.
    

### Relacionamentos e Cardinalidades

*   **Clientes ↔ Pedidos**: Um cliente pode realizar vários pedidos (um para muitos).
    
*   **Produtos ↔ Pedidos**: Um produto pode estar presente em vários pedidos (um para muitos).
    
*   **Funcionários ↔ Envios**: Um funcionário pode estar associado a vários envios (um para muitos).
    
*   **Pedidos ↔ Envios**: Um pedido pode ter vários registros de envio (um para muitos).
    

Este esquema permite análises detalhadas sobre o comportamento dos clientes, eficiência logística, desempenho de vendas e muito mais. É uma base sólida para a geração de insights valiosos que impulsionam as estratégias de negócio.
