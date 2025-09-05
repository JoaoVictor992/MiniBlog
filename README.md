MiniBlog

MiniBlog é um microblog construído em React — leve e funcional, ideal para publicar posts, editar e navegar por conteúdos de forma simples.

Tecnologias Utilizadas

Frontend: React

Estilo: CSS Modules

Autenticação e Contexto: AuthContext.js + custom hook useAuthentication.js

CRUD de Posts: hooks personalizados (useFetchDocuments, useInsertDocument, useUpdateDocument, useDeleteDocument)

Rotas e Navegação: componentes e páginas como Home, PostDetail, CreatePost, EditPost, Dashboard, Search

Componentes comuns: Navbar, Footer, Post, Search, About

 Funcionalidades Principais

Cadastro e login de usuários

Publicação de posts

Edição e remoção de posts

Visualização detalhada de cada post

Dashboard do usuário com seus posts

Busca por posts

Navegação entre páginas: Home, Sobre, Autenticação, Criação e Edição de posts
Estrutura do Projeto:<br>
src/<br>
├── components/<br>
│   ├── Navbar.js<br>
│   ├── Footer.js<br>
│   └── Post.js<br>
├── pages/<br>
│   ├── Home.js<br>
│   ├── PostDetail.js<br>
│   ├── CreatePost.js<br>
│   ├── EditPost.js<br>
│   ├── Dashboard.js<br>
│   ├── Login.js<br>
│   ├── Register.js<br>
│   ├── Search.js<br>
│   └── About.js<br>
├── hooks/<br>
│   ├── useAuthentication.js<br>
│   ├── useFetchDocuments.js<br>
│   ├── useInsertDocument.js<br>
│   ├── useUpdateDocument.js<br>
│   └── useDeleteDocument.js<br>
├── context/<br>
│   └── AuthContext.js<br>
├── utils/<br>
│   └── config.js<br>
├── index.js<br>
├── App.js<br>
├── App.test.js<br>
└── setupTests.js<br>


Como Rodar o Projeto

Clone o repositório:

git clone https://github.com/JoaoVictor992/MiniBlog.git
cd MiniBlog


Instale as dependências:

npm install


Configure variáveis de ambiente se necessário (por exemplo, URL da API, keys, etc.) em config.js.

Inicie o servidor de desenvolvimento:

npm start


Acesse o projeto em http://localhost:3000.


Scripts Disponíveis

Por ser um projeto React padrão, você pode usar (caso esteja configurado):

npm start         # executa em ambiente de desenvolvimento
npm test          # executa testes
npm run build     # gera build de produção





Este projeto é um teste e um treino para minhas habilidades

Contribuições são bem-vindas!
