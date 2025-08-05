# 📚 Workshop MongoDB com Spring Boot

Este projeto tem como objetivo demonstrar na prática a integração entre o banco de dados **MongoDB** e o framework **Spring Boot**, utilizando conceitos de arquitetura RESTful, manipulação de documentos, repositórios, DTOs, e muito mais.

---

## 🔧 Tecnologias Utilizadas

- Java 17+
- Spring Boot
- Spring Data MongoDB
- MongoDB
- Maven

---

## 📌 Funcionalidades

- Cadastro, listagem, edição e exclusão de usuários
- Criação de postagens com título, corpo, data e autor
- Associação de comentários aos posts, com nome do autor e data
- Busca de posts por:
  - Título (case insensitive)
  - Conteúdo completo (título, corpo e comentários) com filtro de data

---

## 📁 Estrutura do Projeto

```bash
├── domain/            # Entidades: User, Post
├── dto/               # DTOs: UserDTO, AuthorDTO, CommentDTO
├── repository/        # Interfaces de acesso ao banco (MongoRepository)
├── resources/         # Controladores REST para Users e Posts
├── services/          # Lógica de negócio e integração com os repositórios
├── config/            # Classe de configuração para instanciar dados no banco
├── exception/         # Tratamento global de exceções
├── util/              # Utilitários para manipulação de URLs e datas
