# Sistema de Gerenciamento de Eventos

## 📌 Sobre o Projeto
Sistema desenvolvido para a disciplina de PHP, utilizando arquitetura MVC e Design Patterns. Permite gerenciar eventos pessoais com cadastro de usuários e autenticação.

## 🛠️ Tecnologias Utilizadas
- PHP 8
- MySQL
- Bootstrap 5
- PDO

## 🎨 Design Patterns
- **Singleton** – Conexão única com o banco de dados
- **Front Controller** – Centralização das requisições

## ✨ Funcionalidades
- Cadastro/Login de usuários (senha com bcrypt)
- Dashboard com estatísticas
- CRUD completo de eventos
- Visualização detalhada de eventos
- Interface responsiva

## 📁 Estrutura do Projeto
projeto-eventos/
├── config/ # Configurações
├── controllers/ # Controladores
├── models/ # Modelos e banco de dados
├── views/ # Templates HTML
│   ├── auth/ # Login e cadastro
│   ├── dashboard/ # Página inicial
│   └── eventos/ # CRUD de eventos
├── public/ # Front controller e assets
└── database.sql # Script do banco de dados

## 🚀 Como Executar
1. Clone o repositório para `htdocs` do XAMPP
2. Importe o arquivo `database.sql` no phpMyAdmin
3. Configure o banco em `config/database.php`
4. Acesse: `http://localhost/projeto-eventos/public/`

**Usuário de teste:**
- E-mail: `admin@teste.com`
- Senha: `123456`

## 👨‍💻 Autor
Fellipe Silva Vieira - 5162151

## 📅 Data
Maio/2025
