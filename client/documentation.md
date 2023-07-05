# Documentation for Site-validify Frontend

## Introduction
Site-validify is a web application that allows users to validate website. The application has two main pages: the index page and the profile page. The index page allows users to enter a website and validate it. The profile page displays the user's profile information and a list of previously validated website.

## Technologies Used
The Site-validify project was built using HTML, CSS, and JavaScript for the front-end. The back-end was built using Node.js and Express.js. The database used was MongoDB.

## File Structure
The project has the following file structure:

- `index.html`: This is the main page of the application where users can validate website.
profile.html: This page displays the user's profile information and a list of previously validated website.
- `index.html`: This is the main page of the application where users can validate website.
- `index.css`: This file contains the CSS styling for the index page.
- `index.js`: This file contains the JavaScript code for the index page.
- `profile.js`: This file contains the JavaScript code for the profile page.
- `login.js`: This file contains the JavaScript code for the login page.
- `signup.js`: This file contains the JavaScript code for the signup page.
- `profile.js`: This file contains the JavaScript code for the profile page.
- `profile.css`: This file contains the CSS styling for the profile page.
- `login.css`: This file contains the CSS styling for the login page.
- `signup.css`: This file contains the CSS styling for the signup page.

### The E-validify application has the following functionality:

- Users can enter an url on the index page and validate it.
- Users can view their profile information and a list of previously validated website on the profile page.
- Users can log in to the application using their email address and password.
- Users can log out of the application.
## API Endpoints
The Site-validify application has the following API endpoints:

- POST /api/v1/auth/signup: This endpoint allows users to sign up for the application.
- POST /api/v1/auth/signin: This endpoint allows users to log in to the application.
- POST /api/v1/auth/logout: This endpoint allows users to log out of the application.
- POST /api/v1/validate: This endpoint allows users to validate a website.
- POST /api/v1/validate_guest: This endpoint allows guests to validate a website.
- GET /api/v1/users/:id: This endpoint allows users to retrieve their profile information.
- GET /api/v1/user/:id/emails: This endpoint allows users to retrieve a list of previously validated website.
## Conclusion
The Site-validify project is a simple web application that allows users to validate website. The application has a clean and user-friendly interface and is easy to use. The project uses modern web technologies and follows best practices for web development.