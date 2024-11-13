# Gerenciador de Estoque

Este repositório contém a implementação de um sistema de **Gerenciamento de Estoque** desenvolvido para a disciplina **Laboratório de Banco de Dados**. O projeto foi desenvolvido utilizando conceitos de **Programação Orientada a Objetos (POO)** e **Banco de Dados**, com integração ao **MySQL**.

## Objetivo do Projeto

O sistema visa proporcionar funcionalidades de gerenciamento de estoque, permitindo o cadastro, edição, exclusão e consulta de produtos e categorias, além da movimentação de estoque e geração de relatórios detalhados.

## Funcionalidades

### 1. Gerenciamento de Produtos

- Cadastro de produtos com os campos:
  - **ID do produto** (gerado automaticamente)
  - **Nome**
  - **Descrição**
  - **Quantidade em estoque**
  - **Preço de compra**
  - **Preço de venda**
  - **Categoria**
- Edição e exclusão de produtos.
- Consulta de produtos com filtros como nome, categoria e quantidade em estoque.

### 2. Gerenciamento de Categorias

- Cadastro de categorias com:
  - **ID da categoria** (gerado automaticamente)
  - **Nome**
  - **Descrição**
- Edição e exclusão de categorias.
- Consulta de categorias cadastradas.

### 3. Movimentação de Estoque

- Registro de entrada e saída de produtos com atualização automática da quantidade em estoque.
- Alerta para produtos com quantidade em estoque abaixo do mínimo especificado.

### 4. Geração de Relatórios

- **Relatório de produtos cadastrados**
- **Relatório de movimentação de estoque** (entradas e saídas)
- **Relatório de produtos com baixo estoque**
- **Relatório de vendas e lucro**, baseado nos preços de compra e venda.

## Persistência de Dados

O sistema utiliza um banco de dados **MySQL** para armazenamento de dados, com operações realizadas por meio de comandos SQL.

## Interface

A interface do usuário é intuitiva, permitindo a navegação para todas as funcionalidades mencionadas.

## Stored Procedures e Triggers

- **Stored Procedures** para padronizar operações, incluindo:
  - Cadastro de produtos e categorias (obrigatório).
  - Consultas e geração de relatórios (opcionais).
- **Trigger** para verificar estoque baixo, emitindo alerta ao detectar quantidade abaixo do limite.

## Requisitos para Configuração

- MySQL instalado e configurado.
- Java (ou C/C++) para executar o sistema.

## Entrega e Avaliação

### Critérios de Avaliação

1. **Funcionalidade**: Implementação correta dos requisitos.
2. **Interface Gráfica**: Interface intuitiva e fácil de usar.
3. **Documentação**: Descrição das classes, modelagem de dados, fluxo do sistema e funcionalidades.
