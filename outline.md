```
Installing packages and creating folder for our fresh fruits app
```

```
Explain Morgan
HTTP request logger middleware for node.js
Morgan is a middleware that logs HTTP requests and errors. 
Middleware is simply a function that has access to the request and response lifecycle methods. 
We can either use predefined formats or create new ones to format our logs.
```

```
setup package scripts
```
```
Summarize Dependencies
```

```
Setup .env and .gitignore
```

```
Setup server.js as the only file for right now
```

```
Run dev server
```

```
create seed
```

```
create index route

explain 3 equivalent syntaxes for async functions

set up views folder and public folder and views/fruits

create Default.jsx

Review Sematic HTML

Create fruits/Index.jsx

create show route

create show view 

create new route and new view

link Index to New

create create route

create edit route and edit view

create update route

create delete route

connect delete to index and edit to show
```

### Move the connection
```
create a folder called models, and in it a file called connection.js
move our connection code from server.js to models/connection.js
```

### Move the model also

### Move the fruit routes into a controller/router

```
Your app should now be working just like it was before but now should be more organized. Notice all the pieces for fruits have been broken down into MVC.

models/fruit.js- handles the getting the database connection and defining the fruit model (share of data)
views/fruits/- this folder contains all our views/templates for our fruits
controllers/fruit.js- creates all our routes which pull data from the model and sends them over to the templates
```

### Make a seed script
```
create a models/seed.jsfile
```

```js
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js",
    "seed": "node models/seed.js"
  }
```

### Break to talk about Project
