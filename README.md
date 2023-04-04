# Book Search Engine Starter Code

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table-of-Contents

- [Description](#description)
- [Deployed Site](#deployed-site)
- [Usage](#Usage)
- [Technologies](#technologies)
- [Credits](#credits)

## Description

In this project, I replace the former RESTful API with a GraphQL API integrated into a fully functional book engine developed using the MERN stack.

## Deployed Site

[this link takes you to heroku deployed site]() 

## Usage:

- Run npm init to start the server and install all dependencies.
- Configure all package requirements.
json (root, server, client) - Configure an Apollo server to retrieve and edit data using GraphQL queries and modifications, replacing the old RESTful API.
- Change the existing authentication middleware so that it can be used with a GraphQL API.
- Build an Apollo Provider in order for requests to interface with an Apollo Server.
## User Story
    ```
    GIVEN a book search engine
    WHEN I load the search engine
    THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
    WHEN I click on the Search for Books menu option
    THEN I am presented with an input field to search for books and a submit button
    WHEN I am not logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
    WHEN I click on the Login/Signup menu option
    THEN a modal appears on the screen with a toggle between the option to log in or sign up
    WHEN the toggle is set to Signup
    THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
    WHEN the toggle is set to Login
    THEN I am presented with two inputs for an email address and a password and login button
    WHEN I enter a valid email address and create a password and click on the signup button
    THEN my user account is created and I am logged in to the site
    WHEN I enter my account’s email address and password and click on the login button
    THEN I the modal closes and I am logged in to the site
    WHEN I am logged in to the site
    THEN the menu options change to Search for Books, an option to see my saved books, and Logout
    WHEN I am logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
    WHEN I click on the Save button on a book
    THEN that book’s information is saved to my account
    WHEN I click on the option to see my saved books
    THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
    WHEN I click on the Remove button on a book
    THEN that book is deleted from my saved books list
    WHEN I click on the Logout button
    THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
    ```

## Technologies

- CSS
- bcrypt
- React.js
- concurrently
- JWT
- Bootstrap
- npm
- JavaScript
- Node.js
- Express.js
- MongoDB
- @apollo/client
- Google Books API
- Mongoose
- nodemon
- graphQL
- apollo-server-express

## Credits

this project was created by Jagmit Cheema, starter code provided by UNC Bootcamp.

## Licensing

The application is covered under the following license: [MIT](https://opensource.org/licenses/MIT)