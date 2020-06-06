# awesome-development

## Backend Frameworks
- **[Express.js](https://expressjs.com)** fast, unopinionated, minimalist web framework for Node.js

- **[Django]()** makes it easier to build better Web apps more quickly and with less code.

- **[Flask](https://flask.palletsprojects.com)** is a lightweight WSGI web application framework. It is designed to make getting started quick and easy, with the ability to scale up to complex applications. It began as a simple wrapper around Werkzeug and Jinja and has become one of the most popular Python web application frameworks.

```
from flask import Flask, escape, request

app = Flask(__name__)

@app.route('/')
def hello():
    name = request.args.get("name", "World")
    return f'Hello, {escape(name)}!'
```

```
> set FLASK_APP=hello.py flask run
 * Serving Flask app "hello"
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
 ```
 
- **[Rails](https://rubyonrails.org)** another MVC framework, that combines the Ruby programming language, HTML, CSS, and JavaScript to build dynamic web applications. It offers seamless database table creation, migrations, and scaffolding of views for rapid development.

- **[Laravel](https://laravel.com)** Model-View-Controller framework that comes with an intuitive interface, out-of-the-box API support, as well as tools, packages, and libraries that greatly simplify the development of modern and secure web applications.

- **[Spring]()**

## Frontend Javascript Frameworks
- **[Angular](https://angular.io)** is one of the most popular JavaScript frameworks for developing front-end. This platform is used basically used for building mobile and desktop web applications. Once you learn to build applications, you can easily reuse your code and other abilities for building new applications. One important thing to learn in 2019 is Angular 2+ which is a TypeScript-based web application for front-end.

- **[Bootstrap](https://getbootstrap.com)** another popular framework for front-end. This platform is used for developing web applications with HTML, CSS, and JavaScript components. The framework was created by Twitter developers to build responsive mobile-first sites. It uses npm scripts for its build system and has interactive components such as modal dialogues, custom tooltips, etc.

- **[React](https://reactjs.org)** one of the most popular JS libraries for building user interfaces. It is said to the declarative, efficient and flexible JavaScript library for building user interfaces which lets you compose complex user interfaces from smaller and isolated pieces of components. This framework can be used as a base in the development of mobile applications.

- **[Vue.js](https://vuejs.org)** one of the most popular frameworks for building user interfaces. The core library is focused on the view layer only which is easy to pick up and integrate with other libraries or existing projects. The framework is also capable of powering sophisticated Single-Page Applications when used in combination with modern tooling and supporting libraries.

- **[Bootstrap](https://getbootstrap.com)**

- **[Material UI]()**

- **[Ember]()**

- **[Backbone]()**

- **[AlertifyJS](https://alertifyjs.com)** javascript framework for developing pretty browser dialogs and notifications.
