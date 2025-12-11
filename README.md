
# Desafio: Implementação de Tela de Login em Angular (Front-End Mockado)

## 🎯 Objetivo
Desenvolver uma **tela de login** utilizando **Angular**, simulando todo o fluxo de autenticação.
O login deve ser completamente **mockado** no front-end.

---

## 📋 Descrição do Desafio

### 1. **Tela de Login**
Crie uma tela contendo:

- Um formulário com os campos:
  - **Email**
  - **Senha**
- Botão **Entrar**
- Validações obrigatórias:
  - Ambos os campos são obrigatórios
  - Email deve estar em formato válido
  - Senha deve ter no mínimo 6 caracteres
- Exibir mensagens de erro de forma clara e acessível

---

### 2. **Fluxo de Autenticação (Mockado)**
Como não há backend, toda a autenticação deve ser simulada no front-end.

---

### 3. **Comportamento da Interface**
- Se o login for bem-sucedido:
  - Redirecionar para uma **página inicial simples** (ex.: “Bem-vindo!”)
- Se o login falhar:
  - Exibir uma mensagem de erro amigável

---

## ⭐ Extras (Opcional)
Implementações opcionais que contam pontos:

- Criar um **AuthGuard** que impede acesso à página inicial sem estar “logado” (mockado)
- Adicionar botão de **mostrar/esconder senha**

---

## Entrega Esperada
- Repositório no GitHub contendo o projeto
- Um arquivo `README.md` com instruções de como rodar a aplicação:
  ```bash
  npm install
  ng serve