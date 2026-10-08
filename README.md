 Geek Store

### Introdução
A Geek Store é uma loja de produtos colecionáveis. O objetivo do sistema é facilitar o cadastro e controle do estoque, acompanhar a quantidade de produtos e oferecer recursos como identificação de produtos em pouca quantidade e visualização em realidade aumentada.

## Entidades

-> Cliente (Customer)
-> Produto (Product)
-> Pedido (Order)

## Atributos

-> Cliente (Customer)

• id_Cliente (Chave Primária)
• nome_Cliente
• telefone_Cliente

-> Produto (Product)

• id_Produto
• nome_Produto
• franquia_anime 
• preco_base
• quantidade_estoque 
• modelo_3d_url (Para a Realidade Aumentada)

-> Pedido(Order)

• id_Pedido
• id_Cliente
• id_Produto
• data_pedido
• status (Ex: Pendente, Pago, Cancelado)

## Relacionamento

• O relacionamento é de 1:N, pois um cliente pode fazer vários pedidos com vários produtos nele, mas o pedido está relacionado a apenas um cliente!


**Cliente:** Junior - Geek Store.
