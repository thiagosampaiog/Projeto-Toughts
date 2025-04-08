# 🧠 Projeto Toughts

Aplicação web para compartilhar pensamentos! Aqui você pode criar, visualizar, buscar e deletar seus pensamentos. Cada pensamento é associado a um usuário.

---

## 🚀 Tecnologias usadas

- Node.js
- Express.js
- Sequelize (ORM)
- MySQL
- Express-Handlebars
- Sessions (autenticação)
- bcryptjs (criptografia de senhas)
- Nodemon (ambiente de desenvolvimento)
- Flash messages

---

## 📦 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/thiagosampaiog/Projeto-Toughts.git
cd Projeto-Toughts
```

2. Instale as dependências:

```bash
npm install
```

3. Configure o banco de dados:

Crie um banco no MySQL chamado `toughts` (ou outro nome, mas atualize no `db/conn.js`).

4. Edite o arquivo `db/conn.js` com as credenciais do seu banco:

```js
const sequelize = new Sequelize('toughts', 'usuario', 'senha', {
    host: 'localhost',
    dialect: 'mysql'
});
```

---

## ▶️ Como rodar

```bash
npm start
```

Abra no navegador: [http://localhost:3000](http://localhost:3000)

---

## ✅ Funcionalidades

- Cadastro e login de usuários
- Criação de pensamentos
- Listagem geral de pensamentos
- Busca por título
- Ordenação por data (mais recentes ou antigos)
- Sessão autenticada
- Flash messages para feedback

---


