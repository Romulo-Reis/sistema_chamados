# Sistema de Chamados

O **Sistema de Chamados** é uma aplicação web desenvolvida em React, que utiliza o Firebase para gerenciamento de autenticação e dados. A aplicação é voltada para o controle e acompanhamento de chamados técnicos. Este projeto foi criado como parte do curso [**React Js do Zero ao Avançado na Prática**](https://www.udemy.com/share/101ybQ3@JR3RMe9rdQEKcNAasfH409QnfyZimGA3tzLNT0d-fwR5yH7000y5fc8O0BjwlklA/) na plataforma **Udemy**, com o objetivo de aprender e praticar os conceitos de React.

## 🌐 Acesso ao Projeto

Você pode acessar o projeto através do link abaixo:

[📲 Sistema de Chamados - Deploy no Netlify](https://sistema-de-chamados-sujeito-programador-curso-react.netlify.app/)

## 📋 Índice

- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Pré-requisitos](#pré-requisitos)
- [Instalação e Execução](#instalação-e-execução)
- [Scripts Disponíveis](#scripts-disponíveis)
- [Configuração](#configuração)
- [Contribuindo](#contribuindo)

---

## 🚀 Tecnologias Utilizadas

- [React](https://reactjs.org/) - Biblioteca para criação de interfaces de usuário.
- [Firebase](https://firebase.google.com/) - Plataforma de backend como serviço para autenticação e banco de dados.
- [React Router](https://reactrouter.com/) - Gerenciamento de rotas na aplicação.
- [React Scripts](https://create-react-app.dev/docs/getting-started/) - Ferramentas de configuração e execução para projetos criados com Create React App.

---

## ✅ Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 14 ou superior)
- [npm](https://www.npmjs.com/) ou [yarn](https://yarnpkg.com/)

---

## 📦 Instalação e Execução

Siga os passos abaixo para configurar o projeto em seu ambiente:

1. Clone este repositório:
   ```bash
   git clone https://github.com/Romulo-Reis/sistema_chamados.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd sistema-chamados
   ```

3. Instale as dependências:
   ```bash
   npm install
   ```

4. Inicie o servidor de desenvolvimento:
   ```bash
   npm start
   ```

Acesse a aplicação em: [http://localhost:3000](http://localhost:3000)

---

## 📜 Scripts Disponíveis

No diretório do projeto, você pode executar os seguintes comandos:

- `npm start`: Inicia o servidor de desenvolvimento.
- `npm build`: Gera uma versão otimizada para produção na pasta `build`.
- `npm test`: Executa os testes configurados no projeto.
- `npm eject`: Ejetar as configurações do Create React App (não é reversível).

---

## ⚙️ Configuração

1. Crie um arquivo `.env` na raiz do projeto para configurar as variáveis de ambiente. Exemplo:
   ```
   REACT_APP_FIREBASE_APIKEY=          # Chave da API do Firebase
   REACT_APP_FIREBASE_AUTHDOMAIN=      # Domínio de autenticação do Firebase
   REACT_APP_FIREBASE_PROJECTID=       # ID do projeto Firebase
   REACT_APP_FIREBASE_STORAGEBUCKET=   # Bucket de armazenamento do Firebase
   REACT_APP_FIREBASE_MESSAGINGSENDERID= # ID do remetente de mensagens do Firebase
   REACT_APP_FIREBASE_APPID=           # ID do aplicativo Firebase
   REACT_APP_FIREBASE_MEASUREMENTID=   # ID de medição do Firebase Analytics
   ```

2. Configure os serviços do Firebase, como autenticação e banco de dados, no painel de controle do Firebase.

---

## 🤝 Contribuindo

Contribuições são sempre bem-vindas! Sinta-se à vontade para enviar um pull request ou abrir uma issue para discutir melhorias.

---

Desenvolvido por [Rômulo Reis Tavares](https://github.com/Romulo-Reis).

