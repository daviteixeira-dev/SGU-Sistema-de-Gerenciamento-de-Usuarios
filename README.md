# CRUD-Application-with-Node
CRUD Application with Node, Express &amp; MongoDB

<h1 align="center">
  SGU - Sistema de Gerenciamento de Usuários
</h1>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/daviteixeira-btm/CRUD-Application-with-Node?style=flat-square">
  
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/daviteixeira-btm/CRUD-Application-with-Node?style=flat-square">
  
  <a href="https://github.com/daviteixeira-btm/CRUD-Application-with-Node/commits">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/daviteixeira-btm/CRUD-Application-with-Node?style=flat-square">
  </a>
  
  <img alt="GitHub" src="https://img.shields.io/github/license/daviteixeira-btm/CRUD-Application-with-Node?style=flat-square">

  <img alt="GitHub Stars" src="https://img.shields.io/github/stars/daviteixeira-btm/CRUD-Application-with-Node?style=social">
	<img alt="GitHub Forks" src="https://img.shields.io/github/forks/daviteixeira-btm/CRUD-Application-with-Node?style=social"> 
</p>
<p align="center">
  <a href="#-sobre-o-projeto">Sobre o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-instalação-execução-e-desenvolvimento">Instalação, execução e desenvolvimento</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-como-contribuir">Como contribuir</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-license">License</a>
</p>

![Printsreen](https://github.com/daviteixeira-btm/CRUD-Application-with-Node/tree/main/crud_app/assets/img/index.png)

## 👨🏻‍💻 Sobre o projeto
<p>Nossa plataforma aproxima quem quer comprar de quem quer vender. Eles mesmo se comunicam, e negociam os valores e a entrega. Sem atravessador e sem custo nenhum para o produtor e parar o consumidor.
</p>

## 🚀 Tecnologias

- [Node.js](https://nodejs.org/en/)
- [ReactJS](https://reactjs.org/)
- [Express](https://expressjs.com/pt-br/)
- [Prettier](https://prettier.io/)
- [EditorConfig](https://editorconfig.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [JSON Web Tokens](https://jwt.io/)
- [UUID v4](https://www.uuidgenerator.net/version4)
- [MySQL](https://www.mysql.com/)
- [Docker](https://www.docker.com/)
- [TypeORM](https://typeorm.io/#/)

## 💻 Instalação, execução e desenvolvimento

### Pré-requisitos

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)

### Backend

```bash
# Faça o downloald do projeto no seu computador
$ git clone https://github.com/daviteixeira-btm/CRUD-Application-with-Node.git

# Crie um container docker com o mysql na versão 5
sudo docker run --name mysql-server-5 -e MYSQL_ROOT_PASSWORD=<sua-senha> -dp 3306:3306 mysql:5

# Entre na pasta raiz do projeto
$ cd hackathon-crateus

# Instale as dependências do node
$ npm install

# Tudo pronto para iniciar o servidor
$ npm start

```

### Web
```bash
# Entre na pasta frontend
$ cd crud_app

# Instale as dependências
$ npm install

# Tudo pronto para iniciar a aplicação web
$ npm start

```
## 🤔 Como contribuir

**Faça um fork deste repositório e siga os passos a baixo**

```bash
# Clone seu fork
$ git clone seu-fork-url && cd NOME_DO_REPO

# Crie uma branch com sua feature
$ git checkout -b my-feature

# Faça commit das suas alterações
$ git commit -m 'feat: My new feature'

# Envie o código para sua remote branch
$ git push origin my-feature
```
Despois que sua pull request for merged, você pode deletar sua branch

## 📝 License

Esse projeto possui uma Licensa MIT License - veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---

<div align="center">

Feito com ❤️

</div>
