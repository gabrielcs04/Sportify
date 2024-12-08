# Sportify - Rede Social para Atletas

Bem-vindo ao **Sportify**, uma plataforma de rede social criada para atletas de alto rendimento. O projeto permite que atletas, agências e patrocinadores se conectem, compartilhem suas conquistas, organizem eventos e gerenciem suas carreiras.

Este projeto contém o frontend desenvolvido em React e um backend em Java Spring (configurado separadamente), e está estruturado para funcionar em conjunto com um banco de dados relacional.

## Índice
- [Pré-requisitos](#pré-requisitos)
- [Instalação](#instalação)
- [Build e Execução](#build-e-execução)
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

Siga os passos abaixo para configurar o projeto localmente.

### 1. Clone o Repositório

No terminal, clone este repositório e navegue até o diretório do projeto:

```bash
git clone https://github.com/Sgabrielcs04/sportify.git
cd sportify
```

### 2. Instale as Dependências
Para instalar todas as dependências do frontend, execute:

```bash
cd sportify-frontend
npm install
```

Para instalar todas as dependências do backend, execute:

```bash
cd ../sportify-backend
mvn clean install
```

---

## Build e Execução

Após instalar as dependências, siga as instruções abaixo para buildar e executar o projeto.

### Frontend

No diretório do frontend (`sportify-frontend`), execute:

```bash
npm run build
npm start
```

- **`npm run build`**: Cria uma versão otimizada do projeto para produção.
- **`npm start`**: Inicia o servidor do frontend usando a build gerada.

### Backend

No diretório do backend (`sportify-backend`), execute:

```bash
mvn spring-boot:run
```

- **`mvn spring-boot:run`**: Compila e executa a aplicação Spring Boot localmente.

Certifique-se de que o banco de dados esteja configurado e acessível para que o backend possa conectar-se corretamente.

---

## Funcionalidades:

- **Cadastro de Atleta**: Usuários podem se cadastrar fornecendo dados como nome de usuário, nome completo, data de nascimento, esporte, gênero e (opcionalmente) agência e equipe.
- **Login**: Autenticação de usuários com nome de usuário e senha.
- **Feed**: Permite visualizar uma lista de publicações realizadas por determinados atletas.
- **Perfil do Atleta**: Cada usuário pode visualizar e atualizar suas informações de perfil, incluindo agência e equipe.

---

## Tecnologias Utilizadas

- **Frontend**:
  - Next.js: Framework React para construção de interfaces de usuário.
  - Axios: Biblioteca para fazer requisições HTTP para o backend.
  - TailwindCSS: Framework de CSS utilitário que fornece classes pré-definidas para estilização rápida e personalizável.
  - ChadCN: Conjunto de componentes pré-construídos usando TailwindCSS para agilizar o desenvolvimento de interfaces modernas.

- **Backend**:
  - Java e Spring Boot: Framework para construção de aplicações web em Java.
  - Banco de Dados Oracle: Sistema de banco de dados relacional para armazenar os dados dos atletas.

---

## Contribuição

Contribuições são bem-vindas! Para contribuir:

1. Faça um fork deste repositório.
2. Crie uma branch para sua feature ou correção (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`).
4. Push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.
