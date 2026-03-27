# 📘 Spring MVC + Maven 

---

# 🔹 MVC Architecture

### ❓ What is MVC Architecture?

**Answer:**
MVC stands for Model, View, Controller.

* **Model** → Handles data and business logic
* **View** → UI layer (JSP / Thymeleaf)
* **Controller** → Handles user request and response

👉 It separates concerns and makes application maintainable.

---

### ❓ Explain Controller → Service → DAO → DB flow

**Answer:**

1. Client sends request
2. Controller receives request
3. Controller calls Service
4. Service processes logic
5. Service calls DAO
6. DAO interacts with Database
7. Response goes back to Controller → View

---

### ❓ What is Controller?

**Answer:**

* Entry point of web request
* Handles HTTP methods (GET, POST)
* Calls service layer
* Returns response/view

---

### ❓ Why do we use Service Layer?

**Answer:**

* Contains business logic
* Avoids logic in controller
* Reusable code
* Easy testing

---

### ❓ What is DAO?

**Answer:**
DAO (Data Access Object) is a layer that interacts with database using SQL or ORM.

---

# 🔹 CRUD Operations

### ❓ What is CRUD?

**Answer:**
CRUD = Create, Read, Update, Delete operations.

---

### ❓ How does Create work?

**Answer:**

* Inserts new record into database
* Uses INSERT query

---

### ❓ How does Read work?

**Answer:**

* Fetches data from DB
* Uses SELECT query

---

### ❓ How does Update work?

**Answer:**

* Modifies existing data
* Uses UPDATE query

---

### ❓ How does Delete work?

**Answer:**

* Removes data from DB
* Uses DELETE query

---

# 🔹 Maven

### ❓ What is Maven?

**Answer:**
Maven is a build and project management tool used for Java applications.

---

### ❓ Why Maven?

**Answer:**

* Dependency management
* Build automation
* Standard project structure

---

### ❓ What is mvn clean?

**Answer:**
Deletes the `target` folder (old compiled files).

---

### ❓ What is mvn install?

**Answer:**
Builds project and installs into local repository.

---

### ❓ What is mvn package?

**Answer:**
Compiles code and creates JAR/WAR file.

---

### ❓ Difference between Maven commands?

**Answer:**

* clean → deletes
* package → builds
* install → builds + stores

---

# 🔹 Maven Lifecycle

### ❓ What is Maven Lifecycle?

**Answer:**
Sequence of build phases.

---

### ❓ What are lifecycle phases?

**Answer:**

* validate
* compile
* test
* package
* install
* deploy

---

### ❓ What is Clean lifecycle?

**Answer:**
Removes old build files.

---

### ❓ What is Default lifecycle?

**Answer:**
Main build lifecycle (compile → test → package → install).

---

# 🔹 pom.xml

### ❓ What is pom.xml?

**Answer:**
Project Object Model file used to configure project.

---

### ❓ Explain pom.xml structure

**Answer:**
Contains:

* project details
* dependencies
* plugins

---

### ❓ What is `<project>` tag?

**Answer:**
Root element of pom.xml.

---

# 🔹 Dependencies

### ❓ What is `<dependencies>`?

**Answer:**
Used to add external libraries.

---

### ❓ How to add dependency?

**Answer:**
Add inside `<dependencies>` tag with groupId, artifactId, version.

---

# 🔹 Build & Plugin

### ❓ What is `<build>`?

**Answer:**
Defines build process.

---

### ❓ What is `<plugin>`?

**Answer:**
Adds extra features to Maven.

---

### ❓ Why plugins?

**Answer:**

* Compile code
* Run tests
* Package application

---

# 🔹 View Technologies

### ❓ What is JSP?

**Answer:**
Java Server Pages used to create dynamic web pages.

---

### ❓ What is Thymeleaf?

**Answer:**
Modern template engine used in Spring Boot.

---

### ❓ JSP vs Thymeleaf

**Answer:**

| Feature     | JSP  | Thymeleaf |
| ----------- | ---- | --------- |
| Syntax      | Java | HTML      |
| Modern      | No   | Yes       |
| Readability | Low  | High      |

---

# 🔹 Spring Mail

### ❓ What is Spring Mail?

**Answer:**
Used to send emails using Spring framework.

---

### ❓ What is SMTP?

**Answer:**
Simple Mail Transfer Protocol used for sending emails.

---

### ❓ How mail is sent?

**Answer:**

1. Configure SMTP
2. Create MailSender
3. Send email

---

# 🔹 Spring Message

### ❓ What is Spring Message?

**Answer:**
Used for handling messages and localization.

---

### ❓ What is i18n?

**Answer:**
Internationalization → supports multiple languages.

---

# 🔹 Bean & DI

### ❓ What is Bean lifecycle?

**Answer:**

1. Bean creation
2. Dependency injection
3. init()
4. ready
5. destroy()

---

### ❓ What is init()?

**Answer:**
Called after bean creation.

---

### ❓ What is destroy()?

**Answer:**
Called before bean destruction.

---

### ❓ What is Dependency Injection?

**Answer:**
Providing dependencies from outside instead of creating inside class.

---

### ❓ What is IoC?

**Answer:**
Inversion of Control → Spring controls object creation.

---

# 🔹 Project Flow

### ❓ Explain user request flow

**Answer:**
User → Controller → Service → DAO → DB → View → User

---

### ❓ How view rendering works?

**Answer:**
Controller returns view name → View resolver → UI rendered.

---

### ❓ How form data handled?

**Answer:**
Spring automatically binds form data to Java object.

---

### ❓ Why layered architecture?

**Answer:**

* Clean code
* Easy maintenance
* Reusability

---

# 🔹 Database

### ❓ How DB connection works?

**Answer:**
Using JDBC or ORM frameworks.

---

### ❓ What is JDBC?

**Answer:**
Java API for database connectivity.

---

### ❓ What is ORM?

**Answer:**
Maps Java objects to database tables (Example: Hibernate).

---

# 🔹 Build Tools Comparison

### ❓ Maven vs Gradle

**Answer:**

| Feature     | Maven | Gradle |
| ----------- | ----- | ------ |
| Syntax      | XML   | Groovy |
| Speed       | Slow  | Fast   |
| Flexibility | Less  | More   |

---

### ❓ Which is better?

**Answer:**

* Maven → easy, stable (beginners)
* Gradle → fast, flexible (advanced projects)

---

# ✅ Final Tip

👉 Learn flow + concepts clearly
👉 Use real-time examples in interview
👉 Focus on Service, DI, MVC flow

---
