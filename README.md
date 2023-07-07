# Site-Verifier

Site-Verifier is a web application that allows users to register, login, and validate website contents. It provides a user-friendly interface for managing user accounts, sending website for validation, and viewing previously sent website.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

## Features

- User registration: Users can create a new account by providing their name, username, email, and password.
- User login/logout: Registered users can log in and out of their accounts securely.
- User profile: Users can view their profile information, including their name, username, and email.
- Site validation: Users can input the Url for validation, and the system will check its contents for validity.

## Technologies Used

- Node.js: JavaScript runtime environment for server-side development.
- Express.js: Web application framework for building RESTful APIs.
- bcrypt: Library for password hashing and verification.

## Installation

1. Clone the repository to your local machine.
2. Install Node.js and MySQL if not already installed.
3. Create a new MySQL database.
4. Create a `.env` file in the root directory and add the following variables:

    ```
    DATABASE_URL=your_mysql_database_url
    ```

5. Run the following command to install the required dependencies:

    ```bash
    npm install
    ```

6. Start the server by running the following command:

    ```bash
    npm start
    ```

7. Access the application by opening `index.html` in the `client` directory in your browser.

## Usage

1. Open the Site-Verifier application in your browser.
2. Register a new account by clicking the "Sign Up" button and filling out the registration form.
3. Log in to your account by clicking the "Log In" button and entering your email and password.
4. View your profile information by clicking the "Profile" button.
5. Input URL for validation then click the "Submit" button.

## API Endpoints

| Endpoint     | Description                                |
| ------------ | ------------------------------------------ |
| POST /register    | Creates a new user account.                      |
| POST /login       | Logs in a user and returns a JSON Web Token.     |
| POST /logout      | Logs out a user and destroys their session.      |
| GET /profile      | Retrieves the user's profile information.        |
| POST /validate    | Sends website for validation.                   |
| GET /emails       | Retrieves a list of previously sent URL.      |

## Contributing

Contributions to the Site-Verifier project are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

When contributing, please ensure that you follow the existing code style and conventions, write clear commit messages, and provide appropriate documentation for any new features or changes.

## License

The Site-Verifier project is licensed under the [MIT License](LICENSE).

---

Feel free to customize this `README.md` file according to

 your specific project requirements and add more details as needed.
