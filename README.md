# Using Flask to Create a Simple API

## Example 1: JSON Response

```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def index():
    return {"message": "Hello World"}
```

This example demonstrates a basic Flask application that creates a simple API. When a GET request is made to the root URL ("/"), it returns a JSON response with a message "Hello World".

## Example 2: Plain Text Response
```python
from flask import Flask
app = Flask(__name__)

@app.route("/")
def index():
    return "Hello World"
```

In this example, another basic Flask application is created. When a GET request is made to the root URL ("/"), it returns a plain text response "Hello World".

These examples show how to create simple APIs using Flask, a lightweight and flexible Python web framework.
