<div align="center">

# 🅰️ Guia de Criação e Estrutura de Projeto Angular 18 + Firebase

![Angular](https://img.shields.io/badge/Angular-18-DD0031?logo=angular&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-20.x-339933?logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-10.x-CB3837?logo=npm&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-Ativo-brightgreen)

</div>

Um guia simples e direto para criar um novo projeto **Angular 18** com **Firebase** e configurar uma **estrutura base automatizada** com Node.js.

---

## 🚀 Passo a passo para criar o projeto

### 1️⃣ Escolha a pasta do projeto e abra o **CMD**
No explorador de arquivos, vá até a pasta onde deseja criar o projeto e digite **CMD** na barra de pesquisa.
<img width="661" height="302" alt="image" src="https://github.com/user-attachments/assets/673a1d1c-ebe8-4cf1-989b-7584b44c61c9" />

### 2️⃣ Crie o projeto Angular
No terminal, execute:
`ng new nome-projeto`

<img width="607" height="251" alt="image" src="https://github.com/user-attachments/assets/e0a2d784-66ca-439a-93d6-1e8598d97ebc" />

Escolha CSS (dê um ENTER)

<img width="843" height="320" alt="image" src="https://github.com/user-attachments/assets/bcadd978-d84d-4b34-921f-7dbb9471b310" />

Digite `N` (para não adicionar SSR se preferir)

<img width="1153" height="273" alt="image" src="https://github.com/user-attachments/assets/3310f554-9764-4ba8-b9c7-b938a002e8a5" />

O processo de instalação do NPM começará automaticamente.

<img width="1163" height="679" alt="image" src="https://github.com/user-attachments/assets/70acd64d-fbf9-45b3-870a-e822eb98862c" />

### 3️⃣ Entre na pasta do projeto
`cd nome-projeto`

<img width="691" height="191" alt="image" src="https://github.com/user-attachments/assets/6d6f64ce-7037-443a-885c-fba5b9d33219" />


### 4️⃣ Abra o projeto no VS Code
`code .`

<img width="538" height="197" alt="image" src="https://github.com/user-attachments/assets/71e424bc-caa7-4db2-8b87-644ed5403a91" />


## 🧩 Criando estrutura base Angular 18

Agora vamos automatizar a criação da estrutura de pastas padrão para o seu projeto Angular.

### 1️⃣ Crie o arquivo setup-structure.js

Dentro da raíz do projeto, crie o arquivo:
``setup-structure.js``

<img width="300" height="363" alt="image" src="https://github.com/user-attachments/assets/28159aa4-dfd0-4da9-8350-b04609668fb5" />

### 2️⃣ Cole o script do repositório:

<img width="521" height="245" alt="image" src="https://github.com/user-attachments/assets/947c8170-004f-44a5-9b1d-e36e12a4062a" />

### 3️⃣ Adicione o comando no package.json

Abra o arquivo package.json e adicione dentro de "scripts":
``"setup": "node setup-structure.js"``

<img width="434" height="185" alt="image" src="https://github.com/user-attachments/assets/9e16bedf-0420-44d7-b77b-748fe7379f9e" />

### 4️⃣ Execute o comando para gerar a estrutura

No terminal, rode:
`npm run setup`

<img width="416" height="242" alt="image" src="https://github.com/user-attachments/assets/1f0fb928-cc3a-47df-a6ca-718e42a19f08" />

### ✅ Resultado Final

Sua estrutura base do Angular 18 com Firebase foi criada automaticamente!
Agora você tem um projeto organizado, escalável e pronto para desenvolvimento.

# 💻 O que o script faz?

### 🧾 Resumo das Ações Automáticas
| Etapa                | Descrição                                                             |
| :------------------- | :-------------------------------------------------------------------- |
| 📁 **Estrutura**     | Cria diretórios base para `view`, `model`, `services` e `assets`      |
| 📝 **Gitignore**     | Gera um `.gitignore` completo e otimizado                             |
| 🌐 **SEO**           | Cria `robots.txt` e `sitemap.xml` em `src/`                           |
| ⚙️ **angular.json**  | Adiciona assets e ajusta budgets de build                             |
| 🔥 **Firebase**      | Instala `firebase` e `@angular/fire` automaticamente se não existirem |
| 🧩 **app.config.ts** | Configura a integração inicial com o Firebase                         |
| 🚀 **firebase.json** | Cria ou atualiza o arquivo de deploy do Firebase Hosting              |


<div align="center">

💡 Feito por <a href="https://www.linkedin.com/in/emanuelsacoman/" target="_blank">Emanuel Sacoman</a>

</div>
