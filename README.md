# 🚀 API Backend

API desenvolvida em Node.js para gerenciamento de usuários, produtos e categorias.

---

## 🛠️ Tecnologias

* Node.js
* Express
* Sequelize
* JWT
* Jest

---

## 📁 Estrutura

```
src/
├── database/
├── middleware/
├── models/
├── routes/
├── services/
├── app.js
└── server.js

tests/
```

---

## ⚙️ Configuração

Crie um arquivo `.env`:

```
PORT=3001

DB_HOST=localhost
DB_USER=root
DB_PASS=senha
DB_NAME=project_db

JWT_SECRET=secret
```

---

## ▶️ Como rodar

```
npm install
npm run dev
```

A API estará disponível em:

```
http://localhost:3001
```

---

## 🔐 Autenticação

Use JWT no header:

```
Authorization: Bearer <token>
```

---

## 📚 Rotas

### Usuários

* POST `/users`
* POST `/login`

### Produtos

* GET `/products`
* POST `/products`
* PUT `/products/:id`
* DELETE `/products/:id`

### Categorias

* GET `/categories`
* POST `/categories`

---

## 🧪 Testes

```
npm test
```

---

## 📌 Observações

* Configure o `.env` corretamente
* Certifique-se que o banco está rodando

---

Feito para estudo 🚀
