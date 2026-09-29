# REST API - Spring Boot + JPA

API REST desenvolvida em Java com Spring Boot, utilizando Spring Data JPA, Hibernate e H2 para persistência de dados.

O projeto foi desenvolvido com foco na prática de desenvolvimento de APIs REST, arquitetura em camadas, persistência de dados e organização de aplicações backend.

## 🚀 Tecnologias

- Java 17
- Spring Boot 3.5.5
- Spring Web
- Spring Data JPA
- Hibernate
- H2 Database
- Maven

## 📚 Conceitos praticados

- Desenvolvimento de APIs REST
- Arquitetura em camadas
- Persistência de dados com JPA/Hibernate
- Operações CRUD
- Relacionamentos entre entidades
- Tratamento de exceções
- Separação de responsabilidades
- Modelagem de entidades
- Consultas e persistência utilizando Spring Data JPA

## 🏗️ Estrutura do projeto

O projeto utiliza uma organização em camadas, separando as principais responsabilidades da aplicação:

- **Config** — configurações da aplicação e carga inicial de dados
- **Entities** — representação das entidades do domínio
- **Repositories** — acesso e persistência dos dados utilizando Spring Data JPA
- **Services** — implementação das regras e lógica da aplicação
- **Resources** — arquivos de configuração e recursos da aplicação

## 🗄️ Banco de dados

O projeto utiliza o **H2 Database** em memória para persistência dos dados durante a execução da aplicação.

Configurações principais:

- Banco: `testdb`
- URL: `jdbc:h2:mem:testdb`
- Usuário: `sa`
- Porta da aplicação: `8081`
- Console H2 habilitado

O console do H2 pode ser acessado em:

```text
http://localhost:8081/h2-console
