# Sistema de login com Node.JS e MySQL
Este repositório faz referência à uma simples aplicação de login desenvolvida com Node.js em conjunto com o banco de dados MySQL. Para o front-end utilizou-se o framework Bootstrap.

<h2> Tecnologias Utilizadas </h2>

- [Node.js](https://nodejs.org/en/)
- [MySQL](https://www.mysql.com/)
- [Bootstrap](https://getbootstrap.com/)
- [JavaScript](https://www.javascript.com/)
- [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
- [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)

<h2> Banco de Dados </h2>

Incialmente é preciso criar um banco de dados no MySQL.

```
CREATE DATABASE dblogin;

use dblogin;

CREATE TABLE users(
	id INTEGER PRIMARY KEY AUTO_INCREMENT,
    username VARCHAR (100) NOT NULL,
    email VARCHAR (100) NOT NULL,
    idade INTEGER NOT NULL,
    pass INTEGER NOT NULL

);
```
<h2> Comandos NPM </h2>

Os seguintes pacotes foram instalados utilizando o NPM:

```
npm init
npm instal nodemon -g 
npm install -- save express
npm install express-session
npm install --save body-parser
npm install --save mysql
npm install ejs -save
```

<h2> Páginas </h2>
<img src=/public/images/img_index.png">

<h2> Contato </h2>

[![Linkedin Badge](https://img.shields.io/badge/-Otávio-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/otaviosilva22/)](https://www.linkedin.com/in/otaviosilva22/)
[![Gmail Badge](https://img.shields.io/badge/-otavio.ssilva22@gmail.com-c14438?style=flat-square&logo=Gmail&logoColor=white&link=mailto:otavio.ssilva22@gmail.com)](mailto:otavio.ssilva22@gmail.com)
