# Femtasy Full Stack technical test

## Description

This is the technical assessment for a full-stack position in femtasy.

Write two simple backend & front applications to show Star Wars content to the users.

## Goal

* Deliver a **production ready application**
* Provide all **tests** necessary to ensure the correctness of the application
* Provide a `docker-compose` file to launch the project
* Provide any relevant **documentation**

## Backend side

* Create a _backend for front end_ project that consumes [Star Wars API](https://swapi.dev/)
* The backend can transform the data in any way

### Bonus

* Provide the necessary files to deploy the backend in a Kubernetes cluster
* Deploy the backend in a cloud provider (Heroku, for example)
* Use GraphQL to provide the content
* Instrument your application (metrics, error tracking...)

## Frontend side

* The front client should consume the information from backend above
* By default, the app will show the list of films
* When users clicks on an element of the film list, show the following information:
  * Film data
  * Director data
  * List of characters
* When users click on a character, show its information
* Users can save a film as favorite
* Users can save a character as favorite

### Bonus

* Use SASS as CSS extension language
* Server-side rendering
* Instrument your application (metrics, error tracking...)
* Deploy the application to a cloud provider

## Considerations

* Use a _mobile first_ approach
* Feel free to use any UI framework
* There is no need for pagination
* For films show:
    * Title
    * Director name
    * Description
    * Cover picture
    * List of characters
* For characters show:
    * Name
    * Gender
    * Home world
    * Description
    * Picture
