# Angular-CRUD Modernizado (v21)

Um sistema CRUD (Create, Read, Update, Delete) robusto e moderno, construído com o ecossistema **Angular** e **Material Design**.

## 🚀 Modernização Tecnológica

Originalmente desenvolvido em Angular 9, este projeto passou por um processo sistemático de modernização de infraestrutura:

-   **Framework:** Elevado de Angular 9.1 para **Angular 21.2**.
-   **TypeScript:** Atualizado para a versão **6.0.2**.
-   **Arquitetura:** Preservação da estrutura **NgModule** (standalone: false) para garantir compatibilidade com componentes legados sem refactoring invasivo.
-   **Ambiente:** Otimizado para **Node.js v22.12.0**.

## 🏗️ Estrutura do Projeto

-   **frontend/**: Aplicação Angular utilizando Angular Material para uma interface rica e responsiva.
-   **backend/**: API Fake servida pelo `json-server`, facilitando testes e prototipagem rápida.

## 🛠️ Pré-requisitos

-   **Node.js**: v22.12.0 ou superior.
-   **npm**: v10.x ou superior.
-   **Angular CLI**: Instalado localmente via dependências do projeto.

## 🏃 Como Executar

### 1. Preparar o Backend
Navegue até a pasta do backend e inicie o servidor da API:
```bash
cd backend
npm install
npm start
```
A API estará disponível em `http://localhost:3001`.

### 2. Preparar o Frontend
Em um novo terminal, navegue até a pasta do frontend e inicie a aplicação:
```bash
cd frontend
npm install
npm start
```
Acesse a aplicação em `http://localhost:4200`.

## 🌳 Gestão de Branches

Para fins de arquivamento e comparação, o estado original da aplicação (Angular 9) foi preservado na branch:
-   `angular-8-initial` (Baseline original do projeto).

## 🧭 Roadmap de Melhorias
Este projeto está em constante evolução técnica, com foco em:
-   Correção de tipagem estrita e refatoração de serviços.
-   Implementação de validações avançadas de formulários.
-   Adição de filtros e paginação no lado do cliente.

---
*Desenvolvido com foco em modernização de infraestrutura mantendo 100% da identidade visual original.*
