# Acebook


## QuickStart Instructions

- Fork and clone this repository to your machine
- Open the codebase in an IDE like InteliJ or VSCode
- Create a new Postgres database called `acebook_springboot_development`
- Install Maven `brew install maven`
- Build the app and start the server, using the Maven command `mvn spring-boot:run`
> The database migrations will run automatically at this point
- Visit `http://localhost:8080/users/new` to sign up

## Running the tests

- Install chromedriver using `brew install chromedriver`
- Start the server in a terminal session `mvn spring-boot:run`
- Open a new terminal session and navigate to the Acebook directory
- Run your tests in the second terminal session with `mvn test`

> All the tests should pass. If one or more fail, read the next section.

# acebook-java-fullstack
