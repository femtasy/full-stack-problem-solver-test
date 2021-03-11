# Femtasy frontend technical test

## Introduction

Write a simple front React application that consumes the [Star Wars API](https://swapi.dev/) and shows the content requested by the user.

## Specifications

* By default, the app will show the list of films
* When users clicks on an element of the film list, show the following information:
  * Film data
  * Director data
  * List of characters
* Users can click a character to show its information
* Users can save a film as favorite
* Users can save a character as favorite

## Goal

* Deliver a production ready application
* Provide all tests necessary to ensure the correctness of the application
* Provide information about how to run the project locally
* Provide documentation on how would you deploy the application to a cloud provider

### Bonus

* Provide a Docker container with the application
* Document how you instrument your application (metrics, error tracking...)
* Deploy the application to a cloud provider

## Considerations

* Use a mobile first approach
* There is no need for pagination
* Is up to you how to implement storage
* There is no need to add users to the system
* Favorites are stored globally
* For films show: 
    * Issue number
    * Title
    * Description
    * Cover picture
    * List of characters
* For characters show: 
    * Name
    * Description
    * Picture
* Feel free to use any UI framework
