# ba-service-backend

This project contains a web service based on the Spring Boot framework.
It features RESTful endpoints.

- Check out and run the ApplicationController (you might need to install Java 1.8 and configure the project to use it since Spring Boot seems to dislike later Java versions)

### Port
- default port is 8080
- for deployment, port can be edited in /resources/application.properties

### Check with cURL

- check with "curl localhost:8080/sentiments?tweet=IBM&format=json"
- for textual output: "curl localhost:8080/sentiments?tweet=IBM&format=text"

### Check using html-tester
- URL: "localhost:8081/html"


