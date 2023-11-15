# FastAPI

This is a simple example of a FastAPI application that demonstrates user authentication using JWT (JSON Web Tokens). The application includes features such as token generation, password hashing, and user validation.

## Development Requirements

This app was built using Python(3.8+)

## Endpoints

- /token: Generates an access token for a user based on their credentials.

- /users/me/: Returns information about the currently authenticated user.

- /users/me/items: Returns a list of items owned by the currently authenticated user.

## Authentication

The application uses JWT for user authentication. To obtain an access token, make a POST request to the /token endpoint with valid credentials.

## Dependencies

- FastAPI: A modern, fast (high-performance), web framework for building APIs with Python 3.7+.

- Passlib: A password hashing library.

- Pydantic: Data validation and settings management using Python type annotations.

- PyJWT: JSON Web Token implementation for Python.

## Author

[Musyoki Wambua](https://github.com/Musyoki-Wambua)
