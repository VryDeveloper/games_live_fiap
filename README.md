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
