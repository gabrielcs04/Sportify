# Sportify - Rede Social para Atletas

Bem-vindo ao **Sportify**, uma plataforma de rede social criada para atletas de alto rendimento. O projeto permite que atletas, agências e patrocinadores se conectem, compartilhem suas conquistas, organizem eventos, e gerenciem suas carreiras.

Este projeto contém o frontend desenvolvido em React e um backend em Java Spring (configurado separadamente), e está estruturado para funcionar em conjunto com um banco de dados relacional.

## Índice
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Configuração do Backend](#configuração-do-backend)
- [Iniciando o Projeto](#iniciando-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Contribuição](#contribuição)

---

## Pré-requisitos

Antes de começar, você precisará das seguintes ferramentas instaladas em seu sistema:
- **Node.js** e **npm**: Para verificar a instalação, execute `node -v` e `npm -v`.
- **Java** e **Spring Boot** (para o backend).
- **Oracle Database** ou outro banco de dados relacional compatível (para o backend).

---

## Instalação

Siga os passos abaixo para configurar e executar o projeto localmente.

### 1. Clone o Repositório

No terminal, clone este repositório e navegue até o diretório do projeto:

```bash
git clone https://github.com/Sgabrielcs04/sportify.git
cd sportify
```

### 2. Instale as Dependências
Para instalar todas as dependências listadas no package.json, execute:

```bash
npm install
```

Isso abrirá o projeto em modo de desenvolvimento em seu navegador, acessível em http://localhost:3000

### 3. Possíveis Problemas

- Erro de Conexão: Certifique-se de que o backend está rodando e acessível em http://localhost:8080.

- Porta em Uso: Se a porta 3000 já estiver em uso, execute o React em outra porta:
PORT=3001 npm start

  - No Windows, use set PORT=3001 && npm start.


### 5. Funcionalidades Principais:

- Cadastro de Atleta: Usuários podem se cadastrar fornecendo dados como nome de usuário, nome completo, data de nascimento, esporte, gênero, e (opcionalmente) agência e equipe.

- Login: Autenticação de usuários com nome de usuário e senha.

- Feed: Permite visualizar uma lista de publicações realizadas por determinados atletas.

- Perfil do Atleta: Cada usuário pode visualizar e atualizar suas informações de perfil, incluindo agência e equipe.

### 6. Tecnologias Utilizadas

- Frontend:

  - NextJS: Framework React para construção de interfaces de usuário.
  - Axios: Biblioteca para fazer requisições HTTP para o backend.
  - TailwindCSS: Um framework de CSS utilitário que fornece classes pré-definidas para estilização rápida e personalizável.  
  - ChadCN: Um conjunto de componentes pré-construídos usando TailwindCSS, projetado para agilizar o desenvolvimento de interfaces de usuário modernas.  
  
- Backend (Separado):

  - Java e Spring Boot: Framework para construção de aplicações web em Java.
  - Banco de Dados Oracle: Sistema de banco de dados relacional para armazenar os dados dos atletas.

### 7. Contribuição

Contribuições são bem-vindas! Para contribuir:

- Faça um fork deste repositório.
- Crie uma branch para sua feature ou correção (git checkout -b feature/nova-feature).
- Commit suas mudanças (git commit -m 'Adiciona nova feature').
- Push para a branch (git push origin feature/nova-feature).
- Abra um Pull Request.