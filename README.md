# Eat-Da-Burger! - MySQL, Node, Express & Handlebars

## Link to deployed app: [https://burgerpls.herokuapp.com/](https://burgerpls.herokuapp.com/)

![Burger demo](/public/assets/img/burger.gif)

---

## Overview

- Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

- Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.

- Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

- The app stores every burger in the MySQL database, whether devoured or not.

---

## MVC Directory structure

This app roughly follows the Model-View-Controller (MVC) folder structure below:

```
.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│  
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
```

## Built with:

- [Bootstrap](https://getbootstrap.com/) - Front-end component library for developing with HTML, CSS, and JS.
- CSS3
- [Express](https://expressjs.com/) - Fast, unopinionated, minimalist web framework for node.
- [Handlebars.js](https://handlebarsjs.com) - Templating engine based on the Mustache template language.
- [Heroku](https://heroku.com) - cloud platform as a service supporting several programming languages.
- HTML5
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/JavaScript) - High-level programming language.
- [jQuery](https://jquery.com/) - JavaScript library.
- [MySQL](https://www.mysql.com/products/workbench/) - Visual tool for database architects.
- [Node.js](https://nodejs.org/en/) - Open-source run-time environment that executes JS code outside of a browser.

---

## Author:

- **Pauline Senh** - [plsenh](https://github.com/plsenh)
