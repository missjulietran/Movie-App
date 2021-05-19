# MÖVIEPICK

The MÖVIEPICK application is a only movie database that is simple and easy to navigate. 

It uses the Moviedb API (https://www.themoviedb.org/) and allows users to search and sort movies by popularity, user rating, vote count, release date, etc. Users are also able to sign in, edit their personal profile by uploading images of their favourite movie, leave reviews and add movies to their watchlist. Lastly, this application has a ecommerce store where people can buy MÖVIEPICK swag.

You can visit the application here: http://future-nostalgic.site/

**How to use this Application:**
- Clone the github repository to your local machine
- Run the command, "npm install" inside the cloned directory
- Run the command "nodemon index.js" inside the cloned directory to start the application
- Go to "http://future-nostalgic.site/" to see the rendered pages

**Test Login**: 
username: kim 
password: 123

**Technologies used to build this application:**
- Passport.js - Login authentication middleware for Node.js 
- Knex - building movie queries for watchlist
- Moviedb API - for all movie databases
- Handlebars - for templating 
- Stripe - used to take payments for the ecommerce store
