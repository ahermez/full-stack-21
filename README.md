## Avid Reader's Book Search and Management App
This README file provides an overview of the features and functionality of the "Avid Reader's Book Search and Management" web application. This app is designed for book enthusiasts who want to discover and track books they'd like to read. It offers a user-friendly interface for searching books, creating an account, saving books, and managing saved book lists.

## Table of Contents
Introduction
Features
Usage
Getting Started
Technologies Used
Contributing
License

## Features
As an avid reader, you can use this application to:

Search for Books: The application provides a user-friendly book search engine with the following features:

- A menu with options to "Search for Books" and "Login/Signup."
- An input field to search for books.
- A submit button to initiate the search.
Search Results (Not Logged In): When you enter a search term and click the submit button while not logged in, you will receive several search results, each featuring a book's:

- Title
- Author
- Description
- Image
A link to that book on the Google Books site.
Login/Signup: You can access the login/signup modal through the menu. When toggling between "Login" and "Signup":

- For Signup, you'll be presented with three inputs for a username, an email address, and a password, along with a signup button.
- For Login, you'll be presented with two inputs for an email address and a password, along with a login button.
User Authentication: When you enter a valid email address and create a password for signup, your user account is created, and you are logged into the site. For login, entering your account's email address and password will log you in.

User Dashboard (Logged In): When logged in, the menu options change to:

- "Search for Books"
- "My Saved Books"
- "Logout"
Search Results (Logged In): When logged in, if you enter a search term and click the submit button, you will receive several search results. Each result includes a book's:

- Title
- Author
- Description
- Image
- A link to that book on the Google Books site.
- A button to save a book to your account.
Save and Manage Books: You can save books to your account by clicking the "Save" button on a book. You can also view and manage your saved books, including the ability to remove a book from your account.

Logout: Clicking the "Logout" button logs you out of the site, returning you to the initial menu.

## Usage
1. Begin by searching for books or logging in/signup, depending on your status.
2. Perform book searches and save books to your account when logged in.
3. Access and manage your saved books in the "My Saved Books" section.
4. Log out when you're finished.

## Getting Started
To get a local copy of this application up and running, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have the necessary technologies installed (see Technologies Used).
3. Set up the required database and authentication configurations.
4. Run the application locally.

## Technologies Used
This application is built using the following technologies:

Frontend:
- HTML
- CSS
- JavaScript
- Frameworks and libraries (e.g., React, Angular, or Vue.js)
  
Backend:
- Server-side language (e.g., Node.js, Python, Ruby)
- Database (e.g., MongoDB, PostgreSQL, MySQL)
- User authentication system (e.g., Passport, Devise)

External APIs:
- Google Books API (for book information)


# Project Reference
[Heroku] <a href="https://when-i-was-21-35289fcd3882.herokuapp.com/">Deployment</a>
[GitHub] <a href="https://github.com/ahermez/full-stack-21">Ahermez</a>


# Screen Shot Images

<figure>
  <img src="images\book.png" alt="Login and New User Page" style="width:100%"> <figcaption><i>Login and New User Page</i></figcaption>
  </figure>

# Contributors:
Alicia Hermez
[Netify] <a href="https://20-portfolio.netlify.app/">Ali's Porfolio</a>
Rene Trevino

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it according to the terms of the license.