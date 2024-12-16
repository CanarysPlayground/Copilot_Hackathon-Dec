## Challenge 1 – API Development and CRUD Operations

### 1. Setup Your Development Environment 
**Install JDK:** 
- Ensure you have the Java Development Kit (JDK) installed. You'll need JDK 8 or higher. 
- Verify installation by running `java -version` and `javac -version` in your terminal. This should return the installed versions.

**Choose an Integrated Development Environment (IDE):**
- Select an IDE such as IntelliJ IDEA, or Visual Studio Code (with Java support and Copilot enabled).

**Set Up Maven or Gradle:** 
- Maven and Gradle are build automation tools that help manage project dependencies.
- Install Maven or Gradle if they aren't already installed.
- Set up your project as a Maven or Gradle project in your IDE. This will create the necessary project structure.

### 2. Create a New Java Project 

### 3. Add Required Dependencies
Dependencies are external libraries that your project needs to function. They are managed through `pom.xml` for Maven or `build.gradle` for Gradle.

**Spring Boot:** 
- Add Spring Boot, a framework for building RESTful APIs in Java.
- For Maven, add the `spring-boot-starter-web` dependency to your `pom.xml`.
- Spring Boot simplifies application development by providing pre-configured templates.

### 4. Create the Model Class for the Following JSON
```json
[
    { 
        "id": "1", 
        "name": "Laptop", 
        "description": "A high-performance laptop suitable for gaming and work.", 
        "price": 1200.00 
    }, 
    { 
        "id": "2", 
        "name": "Smartphone", 
        "description": "A latest-generation smartphone with a large display and powerful camera.", 
        "price": 800.00 
    }, 
    { 
        "id": "3", 
        "name": "Wireless Headphones", 
        "description": "Noise-cancelling wireless headphones with long battery life.", 
        "price": 200.00 
    }, 
    { 
        "id": "4", 
        "name": "Smartwatch", 
        "description": "A smartwatch with fitness tracking and customizable watch faces.", 
        "price": 150.00 
    }, 
    { 
        "id": "5", 
        "name": "Tablet", 
        "description": "A lightweight tablet with a sharp display, ideal for reading and browsing.", 
        "price": 300.00 
    } 
]
```

### 5. Read and Write to the JSON File 

### 6. Perform CRUD Operations Using REST Controller
Use the following annotations for CRUD operations:
- `GET /api/items`: Retrieve all items.
- `GET /api/items/{id}`: Retrieve an item by its ID.
- `POST /api/items`: Create a new item.
- `PUT /api/items/{id}`: Update an existing item.
- `DELETE /api/items/{id}`: Delete an item.

### 7. Add Exception Handling
