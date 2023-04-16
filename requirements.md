# GH-repo

## Project Vision

### What is the vision of this product?

the project show lead the user to where you can buy the book, and add to favorite list.

### What pain point does this project solve?

minimize the time for looking for books and having a tracker to your favorite books.

### Why should we care about your product?

our project is like a shopping website for books where the user after opening show details for the book the detils will contain a link where you can buy this book and when the user click on it and buy the book from the website we will get a small profit.

## Scope

### In

- the web app will help the user to find the book he need

- save the books he read and like

- showing more details about the book

- sending the user to website where he can buy the book

- the app should show detils about the books and allow the user to 

### Out

- making the user buy the book from our website

- making the user create multiple lists

## Minimum Viable Product

- add to database table favorite list
- add to database table books
- add to database table user
- delete from table favorite list
- update table user
- show all books in table books
- show all books in favorite list
- show information about the book when clicked on show book info
- show user profile info
- request from the api books

## Stretch

adding a user table and making the app know the list for what user

## Functional Requirements

1. user can create his account
2. user can update his description and profile image
3. user can add a book to favorit list
4. user can delete a book from favorit list

## Data Flow

at home page the site send a requist to the back_end to get books from the database.

if the user isn't login he have to log in so he send a requist to the back_end to get user sending with his/her email and password after that the user info will be send back to the front_end.

if the user don't have an account he should make an account by sending a requist to the back_end with his/her email and a username, password after that after taht it add the info to the user table

in favorite list the webapp send a requist to the back end to get books from the table favorite book list where the list id = list id for the user

## Non-Functional Requirements

1. Performance: our web app is faster and can handle multiple requists because we get the data from the api and add them in the database so when the user open the home page the books info will be from the the database not the api so the server internet connection doesn't matter.
2. Reliability: our web app can handle all the error from his side or the client side so the chance of of getting a failure is low, we handled the database error too.
