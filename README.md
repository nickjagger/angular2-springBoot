# angular2-springBoot

### overview
Angular 2 frontend with Spring Boot backend. Simple template app for creating new projects.

Based on the example here: [Angular2 and Spring Boot: Getting Started](https://blog.jdriven.com/2016/12/angular2-spring-boot-getting-started)

### usage
1. cd into the _backend_ project and run: `mvn spring-boot:run`
This will start the Spring Boot application and also serve the front end from http://localhost:8080.

2. With the backend running, cd into the _frontend\src\main\frontend_ project and run: `npm start`
This will start the angular-cli development server and make the frontend available at htp://localhost:4200. Code changes made to the frontend will be automatically reloaded by the dev server and be immediately visible.
