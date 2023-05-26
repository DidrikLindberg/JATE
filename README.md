# JATE

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


[![JavaScript](https://img.shields.io/badge/JavaScript-%E2%9C%A8-yellow)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Babel](https://img.shields.io/badge/Babel-%F0%9F%8C%8D-yellow)](https://babeljs.io/)
[![Webpack](https://img.shields.io/badge/Webpack-%E2%9C%A8-blue)](https://webpack.js.org/)
[![WebpackPWAManifest](https://img.shields.io/badge/WebpackPWAManifest-%F0%9F%93%B2-blue)](https://www.npmjs.com/package/webpack-pwa-manifest)
[![Service Workers](https://img.shields.io/badge/Service%20Workers-%E2%9C%A8-blue)](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
[![IndexedDB](https://img.shields.io/badge/IndexedDB-%F0%9F%97%84-blue)](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API)
[![node.js](https://img.shields.io/badge/node.js-%E2%9C%A8-green)](https://nodejs.org/en)
[![Express.js](https://img.shields.io/badge/Express.js-%F0%9F%8C%90-green)](https://expressjs.com/)
[![Heroku](https://img.shields.io/badge/Heroku-%F0%9F%8F%A0-lightgrey)](https://devcenter.heroku.com/articles/heroku-cli)


---

## Technology Used 🖥️

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| JavaScript | [https://developer.mozilla.org/en-US/docs/Web/JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)     |  
| Babel | [https://babeljs.io/](https://babeljs.io/) |
| Webpack | [https://webpack.js.org/](https://webpack.js.org/) |
| WebpackPWAManifest | [https://www.npmjs.com/package/webpack-pwa-manifest](https://www.npmjs.com/package/webpack-pwa-manifest) |
| Service Workers | [https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API) |
| IndexedDB | [https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API](https://developer.mozilla.org/en-US/docs/Web/API/IndexedDB_API) | 
| node.js | [https://nodejs.org/en](https://nodejs.org/en)     |     
| Express.js | [https://expressjs.com/](https://expressjs.com/)     |     
| dotenv | [https://www.npmjs.com/package/dotenv](https://www.npmjs.com/package/dotenv)     |     
| HTML | [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)         |   
| CSS | [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)         |   
| Heroku | [Heroku](https://devcenter.heroku.com/articles/heroku-cli)     |
| Git | [https://git-scm.com/](https://git-scm.com/)     |   

---

## Description 📝

JATE (Just Another Text Editor) is a progressive web app that allows you to edit text on the application. It serves the purpose of a simple text editor without any additional features.

JATE was built primarily using webpack and various associated functions. For example, WebpackPWAManifest was used to serve and bundle all the necessary frontend components of the application. The app also utilizes service workers for caching, enabling faster loading and offline usage. Since JATE doesn't rely on databases like MongoDB or MySQL, it stores information on the client's side using IndexedDB and local storage. IndexedDB enables storing and retrieving the text written by the user without additional server-side overhead.

## Table of Contents 📋
* [Installation Instructions](#installation-instructions-📥)
* [Usage Information](#usage-information-✅)
* [Author Info](#author-info-👤)
* [Questions?](#questions-❓)
* [License](#license-🚩)


## Installation Instructions 📥

To install the application, please follow the steps below:

1. Clone or download the contents of this repository to your local machine.
2. Open the terminal in the root directory of the application.
3. Run `npm run install` to download all the required dependencies.
4. Run `npm run start` or `npm run start:dev` to start the server and automatically build the `client/dist` folder.

## Usage Information ✅

To use the app, follow the steps below:

1. Make sure you have followed the instructions above to install the application.
2. Go to `http://localhost:3000` to view the application.
3. Type anything you want.
4. Alternatively, you can also visit the website: [https://daevidvo-jate.herokuapp.com/](https://daevidvo-jate.herokuapp.com/)

------------------------

## Author Info 👤

Didrik Lindberg
* [GitHub](https://www.github.com/didriklindberg)
* [LinkedIn](https://www.linkedin.com/in/didriklindberg)

## Questions ❓

If you have any questions, feel free to reach out:

Email: [didrik.lindberg@example.com](mailto:lindberg.didrik@gmail.com)
GitHub: [didriklindberg](https://www.github.com/didriklindberg)

------------------------

## License 🚩

https://opensource.org/licenses/MIT

The MIT License (MIT)
=====================

...