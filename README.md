# Lab 05 - Maven Session (Part 01)

## Student Information
- Module: Software Engineering
- Full Name:Jayasinghe HPNN
- Registration Number: 244086M

---

## Task Summary
In this practical laboratory session, a standard Java application was built and managed using Apache Maven.

1. Project Scaffold Generation: Created a standardized directory layout (`src/main/java`, `src/test/java`, `pom.xml`) using the `maven-archetype-quickstart` template.
2. POM Configuration: Configured custom organization settings (`groupId`) and project names (`artifactId`).
3. Property Injection: Added custom application properties (`app.name`, `app.version`) inside the `pom.xml` configurations.
4. App Implementation: Updated `App.java` to dynamically capture and log these injected configuration variables from the system runtime environment using `System.getProperty()`.
5. Executable JAR Build: Added and configured the `maven-jar-plugin` to embed the main entry-point class metadata directly into the final packaged binary.

---

## Build and Run Instructions

### Prerequisites
- Java JDK 17 or higher installed
- Apache Maven installed globally

### Compile and Package the App
To clean old target files and compile a fresh, executable JAR binary, execute:
```bash
mvn clean package