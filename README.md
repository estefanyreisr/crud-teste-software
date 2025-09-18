#Descrição do TP

Optei por Criar uma aplicação de Console utilizando SQLite como banco de dados. Implementarei funcionalidades básicas de CRUD (Create, Read, Update,
Delete) para um recurso escolhido para gerenciamento (livros). O recurso é suficientemente simples para ser representado por apenas uma tabela no banco de dados. Desenvolverei Desenvolva uma aplicação de linha de comando que permita ao usuário interagir com o recurso. Implementarei as seguintes funcionalidades:
-Listar Recursos 
-Buscar por ID
-Cadastrar Recurso
-Atualizar Recurso
-Deletar Recurso

Testes Unitários: Contará com testes unitários para validar as principais funcionalidades da aplicação. Demonstrando a capacidade em garantir a qualidade e a robustez do código.

Dessa forma, poderei evidenciar como os testes ajudam na manutenção de um sistema de software.

# 📌 Detalhamento do Sistema de Cadastro de Livros (CRUD)

## 👥 Atividade realizada por:
- Estefany dos Reis Regis dos Santos (2024005904)

## 📝 Explicação do Sistema
O sistema desenvolvido é um **CRUD (Create, Read, Update, Delete) de livros**, com uma API em backend e interface frontend, permitindo:  

- **Criar** novos livros com título, autor, gênero, editora, número de páginas e data de lançamento.  
- **Listar** todos os livros cadastrados.  
- **Buscar** livros por ID.  
- **Atualizar** dados de um livro existente.  
- **Deletar** livros.  

Este sistema simples permite aplicar **testes unitários, testes de integração e testes de regressão**, evidenciando como os testes automatizados ajudam na manutenção do software.  

---

## ⚙️ Tecnologias Utilizadas

### Backend
- **Python 3** → linguagem principal do backend.  
- **Flask** → micro-framework web para criação da API.  
- **SQLAlchemy** → ORM para manipulação do banco de dados SQLite.  
- **SQLite** → banco de dados relacional leve.  
- **Cerberus** → validação de dados de entrada.  
- **Pytest** → framework de testes automatizados.  

### Frontend
- **ReactJS** → biblioteca para criação da interface web.  
- **TypeScript** → tipagem estática para JavaScript, usada com React.  
- **Axios** → biblioteca para requisições HTTP.  
- **React Bootstrap** → biblioteca de componentes para estilização.  

### Ferramentas Auxiliares
- **DBeaver** → visualização e gerenciamento do banco de dados.  
- **Postman** → teste de endpoints da API.
