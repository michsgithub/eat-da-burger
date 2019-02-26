##About the eat-da-burger app

The app is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM.

#Features:
1. User Enters a burger, which is added to the New Burgers list

2. The Devour button next to it can be clicked on that moves the burger to the Devoured Burger list

3. The Remove button next to a devoured burger can be clicked on that removes the burger from display and db

4. all new and devoured burgers are saved in db burger_db until they are removed.

#### MVC design pattern as directed in homework instructions
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
