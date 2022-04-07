# Boas vindas ao repositório do projeto de MongoDB Commerce!

## Habilidades
Neste projeto, são avaliadas as seguintes habilidades:

  * Buscar documentos no banco
  
  * Usar filtros na busca
  
  * Deletar documentos conforme filtro
  
  * Contar documentos compreendidos nos filtros pedidos
  
  * Inserir documentos no banco

  * Utilizar o método `updateOne()` e `updateMany()`

  * Utilizar os operadores `$set`, `$mul`, `$inc`, `$min`, `$max` e `$currentDate`

  * Renomear campos e remover campos

  * Incorporar dados aos documentos através de arrays

  * Utilizar os operadores `$pop`, `$pull` e `$push`
  
  * Utilizar o operador `$addToSet`

  * Utilizar os operadores `$each`, `$slice` e `$sort`

  * Utilizar o operador `$all` para filtrar documentos

  * Utilizar o operador `$elemMatch` para filtrar documentos

  * Utilizar o operador `$size` para filtrar documentos pelo tamanho de arrays

  * Utilizar o operador `$expr` para criar expressões de agregação

  * Utilizar expressões regulares e o operador `$regex` para buscar documentos

  * Utilizar o operador `$mod`

---

## O que foi desenvolvido

Um projeto com o codinome _commerce_. Neste projeto, foram praticados todos os conceitos de **MongoDB** já ensinados até aqui.

A ideia é trabalhar com o banco de dados `commerce`, que contém dados do cardápio do **McDonald's**, como ingredientes, valores nutricionais e dados fictícios de vendas.

---

### Para rodar o projeto:

1. Clone o repositório

  - `git clone git@github.com:taicout6/project-mongodb-commerce.git`.
  - Entre na pasta do repositório que você acabou de clonar:
    - `cd project-mongodb-commerce`

2. Suba o docker compose:
  - `npm run compose:up`

3. Rode o comando para criar/resetar o banco de dados:
  - `npm run restore`
