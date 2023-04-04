Joop App(Job Opportunities Application)


#Project Description

This is a job application for kenyans to check for new job listings.
It is a single page CRUD application that has a back-end that is created using Ruby and a sinatra API that uses Active Record to access and persist data in a database, which is used by a separate React frontend that interacts with the database via the API which is then fetched from : http://localhost:3000/cats and http://localhost:3000/listings.. The front-end is created using React , html and css.

#Repository URL:
-Front-end: https://github.com/wanjirugachunji/client

-Back-end: https://github.com/wanjirugachunji/bakend-rails-project

- user-auth-main :https://github.com/wanjirugachunji/user-auth-main


#Features:

The home page displays a description of the application, and instructs the user to click on the "Listings" link in the navigation in order to view all of the listings
Upon clickin g on "Listings" in the navigation there is a dropdown menu at the top of the page to allow you to sort the listings by category
Below the dropdown menu is a form where users can create new categories
Below the form is all of the listings which are displayed with a title, body, and category and have the ability to be edited as well as deleted
If you would like to create a new listing click "New Listing" in the navigation which will take you to a form to fill out
Once you are done filling out the form click "Create Listing" which will automatically take you to the "listings" page where you can see your new listing that you created


On the front end the application uses a total of 9 components: App.js, Home.js, Navigation.js, Listings.js, Listing.js, New Listing.js, EditListing.js, NewCategory.js, and Filter.js

The application has 3 different client-side routes throughout it using React-Router: Home, Listings, and NewListing

Styling was done using CSS and Bootstrap



## Installation

1. Fork and clone both the front-end and back-end repositories

2. Back-end
  - cd into the project directory
  - run 'bundle install'
  - run 'rake db:migrate'
  - run 'bundle exec rake server' to start the server
3. Front-end
  - cd into the project directory
  - run 'npm install'
  - run 'npm start' and the application will open into browser


#How to Use:

• Click "Listings in the navigation to see all of the listings"



• Use the dropdown menu to filter the listings by category



• Fill out the form and click "add" to create a new category



• Click the "edit" button to edit a listing



• Click the "save" button to save you edit



• If you want to delete a listing from the browser click the wastebasket button



• Click "New Listing" in the navigation to create a new listing



• Once you fill out the form click the "create listing" button which will take you back to the "Listings" page where you can see your new listing


#Copyrights:

© 2023 Github pages
