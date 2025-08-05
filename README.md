📚 Workshop MongoDB com Spring Boot
Este projeto tem como objetivo demonstrar na prática a integração entre o banco de dados MongoDB e o framework Spring Boot, utilizando conceitos de arquitetura RESTful, manipulação de documentos, repositórios, DTOs e boas práticas no desenvolvimento de APIs.

🔧 Tecnologias Utilizadas
✅ Java 17+

✅ Spring Boot

✅ Spring Data MongoDB

✅ MongoDB

✅ Maven

📌 Funcionalidades
👤 Cadastro, listagem, edição e exclusão de usuários

📝 Criação de postagens com título, corpo, data e autor

💬 Associação de comentários aos posts, com nome do autor e data

🔍 Busca de posts por:

Título (case insensitive)

Conteúdo completo (título, corpo e comentários) com filtro de data

📸 Demonstrações
<img width="743" height="223" alt="Imagem 1" src="https://github.com/user-attachments/assets/112c9d63-b310-4e35-966a-bd3e4cc034dc" /> <br/> <img width="804" height="213" alt="Imagem 2" src="https://github.com/user-attachments/assets/89c5188e-430d-4cb1-95c5-b551df81d0cb" /> <br/> <img width="613" height="258" alt="Imagem 3" src="https://github.com/user-attachments/assets/3d561b88-9ee5-474e-9fc0-726647630ab2" /> <br/> <img width="829" height="302" alt="Imagem 4" src="https://github.com/user-attachments/assets/cdd416d9-8ab9-4f11-876f-ed1edcf30d8f" /> <br/> <img width="778" height="332" alt="Imagem 5" src="https://github.com/user-attachments/assets/fb0f25b6-8515-4913-8285-be6af2e62cec" /> <br/> <img width="695" height="337" alt="Imagem 6" src="https://github.com/user-attachments/assets/70d10082-ef8a-44ca-968c-4550447a83bf" />
📁 Estrutura do Projeto
bash
Copiar
Editar
src/
├── domain/            # Entidades: User, Post
├── dto/               # Data Transfer Objects: UserDTO, AuthorDTO, CommentDTO
├── repository/        # Interfaces de acesso ao MongoDB (MongoRepository)
├── resources/         # Controladores REST para Users e Posts
├── services/          # Regras de negócio e integração com os repositórios
