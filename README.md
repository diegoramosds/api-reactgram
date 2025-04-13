# 🧠 API - Reactgram

## 📦 Sobre o Projeto

Esta é a **API backend** do projeto **Reactgram**, uma aplicação inspirada em redes sociais como Instagram. Desenvolvi esta API com foco em funcionalidades modernas de rede social, como upload de fotos, curtidas, comentários, autenticação e muito mais.

Utilizando **Node.js**, **Express** e **MongoDB com Mongoose**, a API fornece todas as rotas e lógicas necessárias para o funcionamento do frontend Reactgram, permitindo uma comunicação segura e eficiente com o banco de dados.

---

## 🛠️ Funcionalidades da API

- 🔐 **Autenticação de Usuário** (Login e Registro)
- 🧑‍🤝‍🧑 **Gerenciamento de Perfil**
- 📸 **Upload de Fotos**
- ❤️ **Sistema de Curtidas e Descurtidas**
- 💬 **Comentários em Fotos**
- 🕵️‍♂️ **Busca de Usuários**
- 🧾 **Feed de Fotos**
- 🧹 **Deleção de Fotos e Comentários**
- 📤 **Atualização de Perfil**
- 📁 **Serviço de Upload com Multer**

---

## 🚀 Tecnologias Utilizadas

- **Node.js** – Ambiente de execução JavaScript no servidor
- **Express** – Framework para criação de APIs RESTful
- **MongoDB** – Banco de dados NoSQL
- **Mongoose** – ODM para modelar os dados do MongoDB
- **JWT** – Autenticação segura com JSON Web Token
- **Bcrypt** – Criptografia de senhas
- **Multer** – Upload de arquivos com suporte a imagens
- **CORS** – Segurança para requisições HTTP cruzadas
- **Dotenv** – Variáveis de ambiente

---

## 🚀 Como Rodar o Projeto

### 🔧 **Pré-requisitos**  

Antes de começar, certifique-se de ter instalado:  

✅ **Node.js** (versão 18 ou superior) → [Baixar aqui](https://nodejs.org/)  

✅ **Gerenciador de pacotes** (npm ou yarn)  

✅ **Git** (para clonar o repositório)  

---  

<br>  


## ▶️ Passo a Passo  

### 🛠 **Executando a API**  

1️⃣ **Clone o repositório**:  
```bash
git clone https://github.com/diegoramosds/api-reactgram.git

```

2️⃣ **Acesse o diretório da API** no terminal.
```bash
cd backend
```

3️⃣ Execute para instalar as dependências do projeto.
```bash
npm install
```

4️⃣ Crie um arquivo .env na raiz do projeto com as variáveis de ambiente necessárias:
```bash
PORT=5000
DB_USER=seu_usuario_mongodb
DB_PASS=sua_senha_mongodb
JWT_SECRET=sua_chave_secreta

CLOUDINARY_CLOUD_NAME=seu_cloud_name
CLOUDINARY_API_KEY=sua_api_key
CLOUDINARY_API_SECRET=sua_api_secret
```

5️⃣ Execute para iniciar o servidor da API.
```bash
npm run server
```

6️⃣ Aguarde até que a API esteja rodando e ouvindo requisições na porta especificada.




