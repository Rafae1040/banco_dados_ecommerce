# 🚀 Modelo de Dados - Sistema de Pedidos

Refinamento do Modelo Conceitual de Banco de Dados para um E-COMMERCE.

Este repositório documenta o modelo de dados utilizado para gerenciar clientes, pagamentos e entregas de pedidos, garantindo uma experiência eficiente e segura para os usuários.


### 🎯 Objetivo:
O modelo de dados foi desenvolvido para garantir agilidade, organização e precisão no gerenciamento de pedidos, desde o pagamento até a entrega, proporcionando uma experiência otimizada para os clientes.

--

### 🏢 Cliente PJ e PF

Cada conta pode ser Pessoa Jurídica (PJ) 🏢 ou Pessoa Física (PF) 👤.

Uma conta não pode conter ambas as informações simultaneamente ❌.

--

### 💳 Pagamento

Um cliente pode cadastrar mais de uma forma de pagamento.

Suporta pagamentos via:

💳 Cartão de Crédito
💵 Boleto
📲 Pix

--

### 📦 Entrega

Cada pedido possui um status de entrega, que pode ser:

🔄 Separando – O pedido está sendo preparado para envio.

🚚 Enviado – O pedido foi despachado e está a caminho.

✅ Entregue – O pedido chegou ao destino com sucesso.
