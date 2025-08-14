# Real World App - Automação de Testes

## Sobre o Projeto
Projeto prático de automação das funcionalidades **Login** e **Registro de Usuário** do **Real World App**.

## Tecnologias
- **Cypress.io**
- **Node.js / Yarn**

## Casos de Teste

**Login**
- Login com sucesso: verificar login com credenciais válidas.  
- Login inválido: verificar login com credenciais inválidas.

**Registro de Usuário**
- Registro com sucesso: criar novo usuário com informações válidas.  
- Registro incompleto: garantir que novos usuários não possam ser criados ao deixar campos obrigatórios sem preencher.

## Automação
Para rodar os testes:

```bash
cd ~/Documents/cypress-realworld-app
yarn install
yarn start
yarn cypress open
