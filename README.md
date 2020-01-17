# Customers Service application using Angular, NodeJS, MongoDB 

This demo describes how nodejs restful-services can be called using Angular.

# Angular Concepts Covered

* Using the Angular CLI
* Using TypeScript classes and modules
* Using Custom Components
* Using the Http object for Ajax calls along with RxJS observables
* Performing GET, PUT, POST and DELETE requests to the server
* Working with Angular service classes for Ajax calls
* Using Angular databinding and built-in directives
* Creating a RESTful Service using Node.js
* (Optional) Using Docker containers


# Steps to run the application

1. Install Node.js (10.16 or higher) and MongoDB (3.4 or higher) on your dev box

    * Node.js: https://nodejs.org
    * MongoDB: https://docs.mongodb.com/manual/administration/install-community

1. Execute `mongod` to start the MongoDB daemon if it's not already running (read the installation instructions above if you are new to MongoDB or have issues running it)

1. Run `npm install -g @angular/cli nodemon` to install the Angular CLI and nodemon.

1. Run `npm install` at the project root to install the app dependencies

1. Run the following task to build the Angular app (and watch for any changes you make) and copy the built code to the `public` folder: 

    `ng build --watch`

1. Run `npm run server` in another console window to start the Node.js server

1. Browse to http://localhost:3000




