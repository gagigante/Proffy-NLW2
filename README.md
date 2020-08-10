<h1 align="center">
    <img alt="Proffy" title="#Proffy" src=".github/logo.png" width="450px" />
</h1>

<h4 align="center">
  Proffy
</h4>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/gagigante/Proffy-NLW2">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/gagigante/Proffy-NLW2">
  
  <a href="https://github.com/gagigante/Proffy-NLW2/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/gagigante/Proffy-NLW2">
  </a>

  <a href="https://github.com/gagigante/Proffy-NLW2/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/gagigante/Proffy-NLW2">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#runner-how-to-run">How to run</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<br>

<p align="center">
  <img alt="Frontend" src=".github/frontend.png" width="100%">
</p>

## :rocket: Technologies

This project was developed with the following techs:

- [Node.js](https://nodejs.org/en/)
- [React](https://reactjs.org)
- [React Native](https://facebook.github.io/react-native/)
- [Expo](https://expo.io/)
- [SQLite](https://www.sqlite.org/)
- [Knex](http://knexjs.org/)

## 💻 Project

This project is a online platform to help students to find teachers to learn specific subjects.

## :runner: How to run

### BACKEND: 
### Just access the fold `backend` and run:

To install dependencies
```
  $ yarn
  
  or

  $ npm install
```
To run the migrations
```
  $ yarn knex:migrate

  or

  $npm run knex:migrate
```
To start the server
```
  $ yarn start

  or

  $ npm start
```

### WEB: 
### Just access the fold `frontend` and run:

To install dependencies
```
  $ yarn
  
  or

  $ npm install
```
To start the server
```
  $ yarn start

  or

  $ npm start
```

### MOBILE: 
### First you need to edit the file `api.js` with your current IP address. 

mobile/src/services/api.js
```
import axios from 'axios';

const api = axios.create({
  baseURL: 'http://YOUR_IP_ADDRESS:3333',
});

export default api;
```

### So access the fold `mobile` and run:
To install dependencies
```
  $ yarn
  
  or

  $ npm install
```
To start the server
```
  $ yarn start

  or

  $ npm start
```

## 🤔 How to contribute

- Fork this repo;
- Create a branch for your new feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m 'feat: My brand new feature'`;
- Push it to your branch: `git push origin my-feature`.

After merge of your pull request, you can delete your branch.

## :memo: License

This project is under MIT license. See the file [LICENSE](LICENSE) for details.

---

[Visit my website!](https://www.ggportfolio.com.br)
