# Games Live FIAP

![Java](https://img.shields.io/badge/Java-SpringBoot-6DB33F?logo=springboot)
![Maven](https://img.shields.io/badge/Maven-Build-C71A36?logo=apachemaven)
![Docker](https://img.shields.io/badge/Docker-Container-2496ED?logo=docker)

## About

Project developed during classes at **FIAP** to learn the fundamentals of **Java** in practice. The application is a **simple games CRUD**, along with an introduction to **Dockerfile** for containerizing the application.

---

## Technologies

- **Java** — Main language
- **Spring Boot** — Application framework
- **Maven** — Dependency management
- **Docker** — Application containerization

---

## Features

- **Create** — Register new games
- **List** — View all registered games
- **Update** — Edit game data
- **Delete** — Remove games

---

## Project Structure

```
games_live_fiap/
├── .mvn/wrapper/      # Maven wrapper
├── src/               # Application source code
├── Dockerfile         # Container configuration
├── pom.xml            # Project dependencies
├── mvnw               # Maven script (Linux/Mac)
└── mvnw.cmd           # Maven script (Windows)
```

---

## How to Run

### Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/VryDeveloper/games_live_fiap.git
   ```
2. Navigate to the project folder:
   ```bash
   cd games_live_fiap
   ```
3. Run with Maven:
   ```bash
   ./mvnw spring-boot:run
   ```

### With Docker

1. Build the image:
   ```bash
   docker build -t games-live-fiap .
   ```
2. Run the container:
   ```bash
   docker run -p 8080:8080 games-live-fiap
   ```

---

## Academic Context

Project developed at **FIAP** as a hands-on Java learning exercise, covering CRUD concepts, Spring Boot and an introduction to containerization with Docker.

---

## Author

Made with 💜 by [VryDeveloper](https://github.com/VryDeveloper)

---

> LEARNING PROJECT

# Games Live FIAP 🎮

## Sobre o Projeto

Projeto desenvolvido durante as aulas na **FIAP** com o objetivo de aprender os fundamentos do **Java** na prática. A aplicação consiste em um **CRUD simples de games**, além de uma introdução ao uso de **Dockerfile** para containerização da aplicação.

---

## 🛠️ Tecnologias Utilizadas

- **Java** — Linguagem principal do projeto
- **Spring Boot** — Framework para criação da aplicação
- **Maven** — Gerenciamento de dependências
- **Docker** — Containerização da aplicação

---

## ✨ Funcionalidades

- ➕ **Criar** — Cadastro de novos games
- 📋 **Listar** — Listagem de todos os games cadastrados
- ✏️ **Atualizar** — Edição de dados de um game
- 🗑️ **Deletar** — Remoção de games

---

## 📁 Estrutura do Projeto

```
games_live_fiap/
├── .mvn/wrapper/      # Maven wrapper
├── src/               # Código-fonte da aplicação
├── Dockerfile         # Configuração do container
├── pom.xml            # Dependências do projeto
├── mvnw               # Script Maven (Linux/Mac)
└── mvnw.cmd           # Script Maven (Windows)
```

---

## 🚀 Como Executar

### Localmente

1. Clone o repositório:
   ```bash
   git clone https://github.com/VryDeveloper/games_live_fiap.git
   ```
2. Acesse a pasta do projeto:
   ```bash
   cd games_live_fiap
   ```
3. Execute com Maven:
   ```bash
   ./mvnw spring-boot:run
   ```

### Com Docker

1. Construa a imagem:
   ```bash
   docker build -t games-live-fiap .
   ```
2. Rode o container:
   ```bash
   docker run -p 8080:8080 games-live-fiap
   ```

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido na **FIAP** como exercício prático de aprendizagem em Java, abordando conceitos de CRUD, Spring Boot e introdução à containerização com Docker.

---

## 👨‍💻 Autor

Feito com 💜 por [VryDeveloper](https://github.com/VryDeveloper)

---

> PROJETO DE APRENDIZAGEM
