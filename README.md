# Projeto de Estudo de API com Node.js

## Descrição

Este projeto é um caso de estudo onde apliquei alguns conceitos fundamentais do protocolo HTTP, como os métodos GET, PUT, POST e DELETE. A API foi desenvolvida em **Node.js** e será consumida por um projeto simples em **React.js**.

## Tecnologias Utilizadas

- **Node.js**: Utilizado para criar a API, proporcionando um ambiente leve e eficiente para manipulação de rotas e manipulação de dados.
- **Express**: Framework utilizado para facilitar a criação das rotas e gerenciamento de requisições HTTP.
- **React.js**: Framework utilizado para criar a interface de usuário que consome a API desenvolvida.

## Funcionalidades da API

A API suporta as seguintes operações:

- **GET**: Recupera dados de um recurso específico.
- **POST**: Cria um novo recurso no servidor.
- **PUT**: Atualiza um recurso existente com base em seu identificador.
- **DELETE**: Remove um recurso específico do servidor.


## Estrutura de Diretórios

```plaintext
/
├── backend/           # Código-fonte da API em Node.js
│   ├── routes/        # Definições de rotas da API
│   ├── controllers/   # Controladores que implementam a lógica das rotas
│   └── app.js         # Configuração principal do servidor
└── frontend/          # Código-fonte do projeto React.js
    ├── src/           # Componentes e lógica do frontend
    └── public/        # Arquivos públicos do frontend
