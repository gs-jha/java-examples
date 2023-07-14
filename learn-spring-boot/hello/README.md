# Hello world Rest API Example

Simple REST API Example with Spring Boot 3

## Step 1: Create spring initializer project

- Go to start.spring.io
- Select Maven or Gradle. For This I choosed Maven project
- Then select Spring Boot version. For this I choosed 3.1.1
- Specify project metadata, like group, artifact, name, description and package name
- For now keep packaging as Jar
- Select Java version. Choose latest Java version. For this I choosed Java 20.
- Add dependencies for Spring Boot. For now just select Spring Web.
- Click Generate to generate zip for this project.

## Step 2: Import project in Eclipse

## Step 3: Create new java class in Eclipse

- Create java class in same package as Spring Boot. Name it as HelloWorldController
- Add `@RestController` annotation to HelloWorldController.
- Create public function as `public String helloWorld(){}`.
- Create `@RequestMapping` annotation newly created function. eg. `@RequestMapping("/hello")`
- Import classes for annotation used

## Step 4: Run the project and check http://localhost:8080/hello
