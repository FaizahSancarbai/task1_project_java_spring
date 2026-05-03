# Task 1 – Java Spring Boot Web Application

This project is a simple Spring Boot web application demonstrating:
- Basic routing with a controller
- Passing parameters using `@RequestParam`
- Rendering views with Thymeleaf
- Serving static resources (images)

---

## Features

### Greeting Page
- URL: `/greeting`
- Accepts a `name` parameter
- Displays a personalized greeting using Thymeleaf

### Home Page
- URL: `/`
- Redirects to the greeting page

### Static Image
- Logo stored in: `src/main/resources/static/images/logo.png`
- Displayed on the greeting page

---

## How to Run

1. Open the project in IntelliJ IDEA.
2. Run the main class
3. Open the browser and go to:
   http://localhost:8080/greeting?name=Vistula

