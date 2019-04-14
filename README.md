# Bluewater Management - API
This is the back-end repository for the an investment accounts project.  This
application allows users to create, read, update and destroy their investment account
holdings.

## How it works
User will be allowed to authenticate their accounts by signing-up and into their
portal.

## Directory
    +  Active Site:
    +  Bluewater Management
      - Front End Repo:
    + Bluewater Management
      - Back End Repo:
    +  [Heroku](https://bluewater-mgnt-api.herokuapp.com/)

## Entity Resource Diagram
    [ERD](https://i.imgur.com/sVMAU3S.jpg)

## Technologies used
    + Ajax
    + Bootstrap
    + CSS3
    + Express.js
    + Handlebars
    + HTML5
    + JavaScript
    + jQuery
    + MongoDB and Mongoose
    + Node.js
    + Sass

## User Stories
    + As user, I'd like to sign up with email and password.
    + As a registered user, I'd like to sign in with email and password.
    + As a signed in user, I'd like to change password.
    + As a signed in user, I'd like to sign out.
    + As a signed in user, I'd like to create a bucket list item with a title and description.
    + As a signed in user, I'd like to update my bucket list item's title and description.
    + As a signed in user, I'd like to delete my bucket list item.
    + As a signed in user, I'd like to see all my bucket list items but not other users'.
    + As a signed-in user, I'd like to see bucket list items I've completed.


## Planning, process, and problem-solving strategies


## Routes and Methods
    + '/sign-up' --> router.post()
    + '/sign-in' --> router.post()
    + '/sign-out' --> router.delete()
    + '/change-password' --> router.patch()
    + '/list-items' --> router.get(), router.post()
    + '/list-items/:id' --> router.get(), router.patch(), router.delete()
    + '/account' --> router.get(), router.post()
    + '/account/:id' --> router.get(), router.patch(), router.delete()
