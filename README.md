## Flask Number Guessing Web App

This project is a simple interactive web application built using the Flask framework in Python.

The application generates a random number between 0 and 9 when the server starts. Users attempt to guess the number by entering their guess directly in the browser URL.

The server evaluates the guess and responds with visual feedback indicating whether the guess is too high, too low, or correct.

This project demonstrates how Flask routing can be used to build interactive web applications that respond dynamically to user input.

This project was developed as part of the #90DaysOfCode challenge to practice backend web development using Python and Flask.

---

## Technologies Used

Python  
Flask  
HTML (rendered within Flask responses)

---

## Key Concepts Demonstrated

Building web applications using Flask

Dynamic routing with URL parameters

Handling user input through URL paths

Generating random values using Python

Returning HTML responses from Flask routes

Creating simple interactive web applications

---

## Application Workflow

1. The server generates a random number between 0 and 9
2. The homepage prompts the user to guess the number
3. The user enters their guess in the URL
4. Flask captures the guess using a dynamic route parameter
5. The server compares the guess with the random number
6. The browser displays feedback indicating if the guess is too high, too low, or correct

---

## Installation

Install Flask

```
pip install flask
```

---

## Run

```
python main.py
```

Once the server starts, open your browser and navigate to:

```
http://127.0.0.1:5000
```

Then enter your guess in the URL like this:

```
http://127.0.0.1:5000/5
```

---

## Why This Project Matters

This project introduces important backend development concepts such as dynamic routing and server-side logic.

It demonstrates how web frameworks can process user input and return dynamic responses based on application logic.

---

## Author

Faiz Hasan  
Python Automation & Backend Developer
