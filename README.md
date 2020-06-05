# awesome-development

## Backend Frameworks
- **[Express](https://expressjs.com)** fast, unopinionated, minimalist web framework for Node.js

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
 
- **[Rails](https://rubyonrails.org)**
- **[Laravel]()**
- **[Spring]()**

## Frontend Javascript Frameworks
- **[Angular]()**
- **[React]()**
- **[Vue]()**
- **[Ember]()**
- **[Backbone]()**
- **[AlertifyJS](https://alertifyjs.com)** - javascript framework for developing pretty browser dialogs and notifications.
