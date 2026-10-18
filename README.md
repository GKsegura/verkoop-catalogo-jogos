# Verkoop — Catálogo de Jogos

Sistema desktop em C# (Windows Forms) para gestão de catálogo de jogos, desenvolvido como projeto semestral no curso técnico de informática.

## Funcionalidades

- **Login e autenticação de usuário**, com senha protegida por hash MD5
- **Cadastro de usuários** (criação, edição e exclusão)
- **Cadastro de jogos**: nome, descrição, preço e restrição de idade
- **Pesquisa e exclusão de jogos** no catálogo
- Conexão com banco de dados relacional para persistência dos dados
- Menu principal e tela de splash na inicialização

## Tecnologias

- C# / .NET Framework (Windows Forms)
- Banco de dados relacional (via classe de conexão dedicada)
- Criptografia MD5 para senhas

## Estrutura

- `frmLogin` — autenticação de usuário
- `frmCadUsuario` — cadastro de usuário
- `frmCadJogo` — cadastro de jogo
- `frmPesqJogo` — pesquisa de jogos
- `frmExcluiJogo` — exclusão de jogo
- `frmMenu` — menu principal
- `ConexaoBanco` — camada de acesso ao banco de dados

## Contexto

Projeto desenvolvido na disciplina de C# — 2º Semestre, 2º Ano — Colégio Técnico Industrial "Prof. Isaac Portal Roldán" (UNESP).

## 📊 Linguagens

![Linguagens](https://raw.githubusercontent.com/GKsegura/GKsegura/main/cards/verkoop-catalogo-jogos.svg)
