# Homework week 21 - Full Stack MERN book search application


Link: https://booksearchdb.herokuapp.com/saved<br>
Repo: https://github.com/Brento20/book_search<br>


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table of Contents
[Project Description](#project-description)

[File Structure](#file-structure)

[Usage](#file-structure)

[Future Development](#future-development)

<br><br>

## Project Description

This web application allows a user to browse the google books API to select books they have read, add them to a database that is accessible using the user login details.

The user is presented with a name, description and image for books that they search for.

The user can also remove these books from the database.

<br>


## File Structure

### MVC Model-View-Controller
 <br></br>

## Deployment via Visual Studio
### Preliminary NPM Install
    - At the root level run "NPM install"
        - To run the application locally, run "NMP RUN DEVELOP"
### Online Deployment
    - Create accounts on Heroku and Atlas/mongoDB
    - Create a cluster using Atlas and create a connection with a username and password.
    - Create a heroku application and share the database username and password as a config var in your heroku application. 
    - Git push application to the heroku repository.

 <br></br>
## Usage

Upon running the application, you are able to sign in using a JWS authenticated session, call the google books API and save results from this API in a MongoDB.

## Deployed application images


![deployed2](readmeImages/003.png)


## Future Development

1. Social media integration: sharing, liking, and commenting. 
2. Indexing and PDF creation. 
3. Advertisement opportunities.
