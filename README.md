## 📚 Workshop MongoDB com Spring Boot
Este projeto tem como objetivo demonstrar na prática a integração entre o banco de dados MongoDB e o framework Spring Boot, utilizando conceitos de arquitetura RESTful, manipulação de documentos, repositórios, DTOs e boas práticas no desenvolvimento de APIs.

## 🔧 Tecnologias Utilizadas
✅ Java 17+

✅ Spring Boot

✅ Spring Data MongoDB

✅ MongoDB

✅ Maven

## 📌 Funcionalidades
👤 Cadastro, listagem, edição e exclusão de usuários

📝 Criação de postagens com título, corpo, data e autor

💬 Associação de comentários aos posts, com nome do autor e data

🔍 Busca de posts por:

Título (case insensitive)

Conteúdo completo (título, corpo e comentários) com filtro de data

## 📸 Demonstrações

<img width="935" height="296" alt="Image" src="https://github.com/user-attachments/assets/308507d2-c949-4284-a2b7-888c1c32a9a0" />
<img width="926" height="302" alt="Image" src="https://github.com/user-attachments/assets/00148766-ba56-443a-a721-ec59041d1a9f" />

<img width="652" height="665" alt="Image" src="https://github.com/user-attachments/assets/0550cc48-f8bb-49c3-8c67-3f6d44292072" />

## 📁 Estrutura do Projeto
bash
Copiar
Editar
src/
├── domain/            # Entidades: User, Post
├── dto/               # Data Transfer Objects: UserDTO, AuthorDTO, CommentDTO
├── repository/        # Interfaces de acesso ao MongoDB (MongoRepository)
├── resources/         # Controladores REST para Users e Posts
├── services/          # Regras de negócio e integração com os repositórios
