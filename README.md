<h1 align="center">
    <img 
        src="web/src/assets/readme/logo1.png"
        width="500px">
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/abnerwillys/">
    <img 
        alt="Made by Abner Willys" 
        src="https://img.shields.io/badge/MADE%20BY-Abner%20Willys-%230077b5?style=flat-square&logo=linkedin">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-%20brightgreen?style=flat-square&logo=">

  <a href="https://rocketseat.com.br/">
    <img 
        alt="Instituição de Ensino" 
        src="https://img.shields.io/badge/-Rocketseat-%237159c1?style=flat-square&logo=apache-rocketMQ&logoColor=White">
  </a>

  <a href="https://www.typescriptlang.org/">
    <img 
        alt="Typescript" 
        src="https://img.shields.io/badge/|-TypeScript-%23007ACC?style=flat-square&logo=TYPESCRIPT">
  </a>
  <a href="https://github.com/abner-starkasty/happy/tree/main/backend">
    <img 
        alt="server Node.js" 
        src="https://img.shields.io/badge/Server-Node.js-%23339933?style=flat-square&logo=node.js">
  </a>
  <a href="https://github.com/abner-starkasty/happy/tree/main/web">
    <img 
        alt="web React" 
        src="https://img.shields.io/badge/Web-React-%23007ACC?style=flat-square&logo=REACT">
  </a>
  <a href="https://github.com/abner-starkasty/happy/tree/main/mobile">
    <img 
        alt="mobile React Native" 
        src="https://img.shields.io/badge/Mobile-React%20Native-%235849BE?style=flat-square&logo=REACT">
  </a>
</p>

---

<p align="center">
 <a href="#-sobre">Sobre</a> •
 <a href="#-etapas-do-projeto">Etapas do projeto</a> • 
 <a href="#-tecnologias-utilizadas">Tecnologias</a> • 
 <a href="#-como-executar-o-projeto">Como executar o projeto</a> • 
 <a href="#-licença">Licença</a> • 
 <a href="#-desenvolvedor">Desenvolvedor</a>
</p>

---
### 🔖 Sobre

O projeto **Happy** é uma aplicação que conecta pessoas à casas de acolhimento institucional(antigamente denominados orfanatos) para fazer o dia de muitas crianças mais feliz e cheios de muito amor 💝.

Um projeto fullstack, desenvolvido em cima de uma API Rest com Node.JS, Front end web com ReactJS e Front end Mobile com React Native.

---
#### 💻 Web

<p align="center">
    <img src="./web/src/assets/readme/banner.png" width="600px">
    <img src="./web/src/assets/readme/banner2.png" width="600px">
    <img src="./web/src/assets/readme/banner3.png" width="600px">
    <img src="./web/src/assets/readme/banner4.png" width="600px">
</p>

#### 📱 Mobile

<p align="center">
    <img src="./mobile/src/images/readme/banner1.jpeg" height="350px"> <img src="./mobile/src/images/readme/banner2.jpeg" height="350px"> <img src="./mobile/src/images/readme/banner3.jpeg" height="350px"> <img src="./mobile/src/images/readme/banner4.jpeg" height="350px"> 
</p>

---
### 📝 Etapas do projeto

 - [x] 💯 ReactJS e Estrutura web;
 - [x] 💯 Back-end com Node.js;
 - [x] 💯 Finalizando front-end e conectando com API Rest;
 - [x] 💯 Estruturando App Mobile com React Native;
 - [x] 💯 Finalizando app mobile e conectando com API Rest.

---
### 🛠 Tecnologias utilizadas


As seguintes tecnologias/ferramentas foram utilizadas:

- [JavaScript](https://www.javascript.com/);
    - [TypeScript](https://www.typescriptlang.org/);
    - [ECS6+](http://www.ecma-international.org/ecma-262/6.0/);
    - [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS);
    - [HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML);
    - [React](https://reactjs.org/);
    - [React Native](https://reactnative.dev/);
- [Node.js](https://nodejs.org/en/);
    - [Express](https://expressjs.com/);
    - [Axios](https://www.npmjs.com/package/axios);
- [React Leaflet](https://react-leaflet.js.org/)
- [Expo](https://expo.io/);
- [TypeORM](https://typeorm.io/#/);
- [SQLite](https://www.sqlite.org/index.html);
- [Insomnia](https://insomnia.rest/);
- [Git](https://git-scm.com/);
- [Figma](https://www.figma.com/);
- [VSCode](https://code.visualstudio.com/);


---

### 🚀👩‍🚀 Como executar o projeto

#### 👉 Pré-requisitos:

- Editor:
  - [Vscode](https://code.visualstudio.com/) foi utilizado nesse projeto;
- [Node.Js](https://nodejs.org/en/) - Instalado em sua máquina;
- [Yarn](https://yarnpkg.com/getting-started/install) - Gerenciador de pacotes de sua preferência (Yarn foi usado nesse projeto);
- [Expo](https://expo.io/) - Caso queira testar a versão mobile instale aplicativo do expo no seu smartphone;
- [Git](https://git-scm.com/downloads) - Instalado em sua máquina;

#### 👉 Após instalar as ferramentas:

Podemos considerar este projeto como sendo divido em três partes:
1. Back End (pasta backend) 
2. Front End (pasta web)
3. Mobile (pasta mobile)

💡 **IMPORTANTE:** Tanto o Front End quanto o Mobile precisam que o Back End esteja executando para funcionar.

### 🛠 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone https://github.com/abner-starkasty/happy

# Acesse a pasta do projeto no terminal/cmd
$ cd happy

# Vá para a pasta backend
$ cd backend

# Instale as dependências
$ yarn

# Subir o servidor
$ yarn dev

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### ♻ Rodando a aplicação web

```bash
# Clone este repositório
$ git clone https://github.com/abner-starkasty/happy

# Acesse a pasta do projeto no terminal/cmd
$ cd happy

# Vá para a pasta web
$ cd web

# Instale as dependências
$ yarn

# Execute a aplicação (Lembrando que é necessário o server estar executando)
$ yarn start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```

### ♻ Rodando a aplicação mobile

```bash
# Clone este repositório
$ git clone https://github.com/abner-starkasty/happy

# Acesse a pasta do projeto no terminal/cmd
$ cd happy

# Vá para a pasta web
$ cd mobile

# Instale as dependências
$ yarn

# Execute a aplicação (Lembrando que é necessário o server estar executando)
$ yarn start

# Com seu celular entre no aplicativo Expo;

# Selecione para scanear o QR code gerado;
```

---
### 📜 Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

### 👨‍💻 Desenvolvedor

<p align="center">
    <a href="https://blog.rocketseat.com.br/author/thiago/">
        <img 
            style="border-radius: 50%;" 
            src="https://avatars0.githubusercontent.com/u/59853942?s=460&u=000274e39c7029e3c065fd9a6913c850907d4691&v=4" 
            width="120px;" 
            alt="Foto">
        <br/>
        <sub><b>Abner Willys  🚀</b></sub>
    </a>
</p>
</br>
<h6 align="center">
    Feito com 💜 por Abner Willys 🙌 Entre em contato 😊🤓
</h6>

<p align="center">
    <a href="https://www.linkedin.com/in/abnerwillys/">
        <img 
            alt="Linkedin Abner Willys" 
            src="https://img.shields.io/badge/-Abner%20Willys-%230077b5?style=flat-square&logo=linkedin">
    </a>
    <a href="https://twitter.com/AbnerStarkasty">
        <img 
            alt="twitter Abner Willys" 
            src="https://img.shields.io/badge/-@abnerStarkasty-%231ca0f1?style=flat-square&logo=twitter&logoColor=white">
    </a>
    <a href="mailto:tgmarinho@gmail.com">
        <img 
            alt="gmail Abner Willys" 
            src="https://img.shields.io/badge/-Gmail-%23c14438?style=flat-square&logo=gmail&logoColor=white">
    </a>
    <a href="https://www.facebook.com/abnerwillys">
        <img 
            alt="facebook Abner Willys" 
            src="https://img.shields.io/badge/-Abner%20Willys-%234267b2?style=flat-square&logo=facebook&logoColor=white">
    </a>
    <a href="https://bit.ly/3eC6MX5">
        <img 
            alt="whatsapp Abner Willys" 
            src="https://img.shields.io/badge/-Abner%20Willys-%2325D366?style=flat-square&logo=whatsapp&logoColor=white">
    </a>
</p>
