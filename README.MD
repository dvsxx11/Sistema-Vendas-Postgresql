# Trabalho-PostgreSQL

## 📌 Sobre

Este repositório contém o **trabalho de modelagem e implementação de um banco de dados PostgreSQL** para um **Sistema de Vendas para Loja**. O objetivo é organizar as estruturas de dados necessárias para controlar clientes, produtos, estoque, pedidos, itens de pedidos e formas de pagamento.

O projeto inclui os scripts SQL para criação das tabelas, relações, inserção de dados e possíveis consultas de exemplo.

---
## ⚙️ Funcionalidades do Sistema

O banco de dados foi projetado para oferecer suporte às principais operações de um **Sistema de Vendas para Loja**, garantindo integridade, organização e facilidade de consulta dos dados.

### 👤 Gerenciamento de Clientes
- Cadastro de clientes com dados pessoais e de contato  
- Identificação única de cada cliente  
- Relacionamento do cliente com seus pedidos  

### 📦 Gerenciamento de Produtos
- Cadastro de produtos com descrição, preço e categoria  
- Controle de produtos disponíveis para venda  
- Associação dos produtos aos pedidos realizados  

### 🏬 Controle de Estoque
- Registro da quantidade disponível de cada produto  
- Atualização de estoque conforme vendas  
- Prevenção de inconsistências nos dados de produtos  

### 🧾 Gerenciamento de Pedidos
- Criação de pedidos vinculados a clientes  
- Registro da data do pedido  
- Associação de múltiplos produtos a um único pedido  

### 🛒 Itens do Pedido
- Controle detalhado dos produtos vendidos em cada pedido  
- Registro de quantidade e valor unitário  
- Cálculo indireto do valor total do pedido  

### 💳 Formas de Pagamento
- Cadastro de diferentes métodos de pagamento  
- Associação da forma de pagamento aos pedidos  
- Flexibilidade para futuras expansões  

### 🔗 Integridade Relacional
- Uso de **chaves primárias e estrangeiras**  
- Garantia de consistência entre tabelas  
- Estrutura preparada para consultas complexas e relatórios  

---


## 🧠 Escopo do Projeto

O sistema de vendas contempla os seguintes elementos principais:

**✨ Entidades e funcionalidades:**

✔ Clientes  
✔ Produtos  
✔ Estoque  
✔ Formas de Pagamento  
✔ Pedidos  
✔ Itens de Pedido  

O banco de dados foi modelado considerando as relações entre estas entidades para suportar operações típicas de uma loja (cadastro, pedidos, controle de estoque, etc).

---

## 📁 Estrutura do Repositório

| Arquivo / Pasta | Descrição |
|-----------------|-----------|
| `ddl/`          | Scripts DDL (*Data Definition Language*) que criam as tabelas e chaves do banco. |
| `dml/`          | Scripts DML (*Data Manipulation Language*) com inserts e populações de exemplo. |
| `README.MD`     | Documentação do projeto (este arquivo). |

---

## 🛠 Tecnologias Utilizadas

O projeto foi desenvolvido com:

- 🗄 **PostgreSQL** – Sistema de gerenciamento de banco de dados relacional open-source. :contentReference[oaicite:0]{index=0}

---


