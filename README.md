# projeto-Backend-LaBook

## 💻 Sobre o projeto

O Labook é uma rede social com o objetivo de promover a conexão e interação entre seus mais diversos usuários. As pessoas poderão criar e curtir publicações.

---

## ⚙️ Funcionalidades

### Endpoint signup

Endpoint para cadastrar o usuário através da inserção dos dados nome, e-mail e senha.

### Endpoint login

Endpoint para logar o usuário já cadastrado no sistema através da inserção do e-mail e da senha.

### Endpoint createPost

Endpoint para criar post.

### Endpoint getPosts

Endpoint para listar todos os posts já cadastrados no sistema.

### Endpoint deletePost

Endpoint para deletar um post. Admins podem deletar qualquer post enquanto contas normais só podem deletar seus próprios posts.

### Endpoint addLike

Endpoint para dar like no post. Uma mesma pessoa não pode dar mais de um like em um post.

### Endpoint removeLike

Endpoint para remover like do post.

---

## 🚀 Como executar o projeto

```bash
# Criar arquivo .env e adicionar os dados do seu banco de dados

PORT = 3003
DB_HOST = 
DB_USER = ""
DB_PASSWORD = ""
DB_DATABASE = ""

JWT_KEY = ""
JWT_EXPIRES_IN = ""

BCRYPT_SALT_ROUNDS = 12

# Instalar as dependências
$ npm install

# Inserir as tabelas no banco de dados
$ npm run migrations

# Executar a aplicação em modo de desenvolvimento
$ npm run start

```
---

## 🛠 Tecnologias Utilizadas

TypeScript

Node

MySQL

Express

---

## 🛠 API



---

## Autor do Projeto

Labenu
