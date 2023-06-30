Sure, here is the GitHub Markdown documentation for the E-Validify project:


# E-Validify Project Documentation

## Overview
This project is a web application that allows users to register, login, and view their profile information. Users can also send a website to validate its contents.

## Technologies Used

* Node.js
* Express.js
* Sequelize ORM
* MySQL
* bcrypt

## Installation

1. Clone the repository to your local machine.
2. Install Node.js and MySQL if not already installed.
3. Create a new MySQL database.
4. Create a `.env` file in the root directory and add the following variables:

    * `DATABASE_URL`: the URL of your MySQL database

5. Run `npm install` to install the required dependencies.
6. Run `npm start` to start the server.

## Usage

1. Run the `index.html` file in the `client` directory on your browser.
2. Register a new account by clicking the "Sign Up" button and filling out the registration form.
3. Log in to your account by clicking the "Log In" button and entering your email and password.
4. View your profile information by clicking the "Profile" button.
5. Send the website for validation by filling out the URL form on the home page and clicking the "Submit" button.

## API Endpoints

| Endpoint | Description |
|---|---|
| `POST /register` | Creates a new user account. |
| `POST /login` | Logs in a user and returns a JSON Web Token. |
| `POST /logout` | Logs out a user and destroys their session. |
| `GET /user` | Returns the currently logged in user's information. |
| `POST /validate` | Sends website for validation. |

## Future Improvements

* Implement client-side form validation to improve user experience and prevent invalid data from being submitted.
* Add the ability for users to edit their profile information.
