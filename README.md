# 📦 Apache Maven

Apache Maven is a **build automation and project management tool** primarily used for Java projects. It uses a **Project Object Model (POM)** to manage a project's build, reporting, and documentation from a central piece of information.

---

## 🚀 Features of Maven

- **Dependency Management** – Automatically downloads required libraries from remote repositories.
- **Standard Directory Layout** – Consistent project structure across teams.
- **Build Automation** – Compiles code, runs tests, packages, and deploys automatically.
- **Plugin Support** – Extend Maven with numerous plugins.
- **Multi-Module Support** – Manage multiple projects from a single POM file.
- **Portable Builds** – Build is consistent across different machines.

---


---

## 📄 The `pom.xml` File

The `pom.xml` (Project Object Model) is the heart of Maven. It contains:

```xml
<project xmlns="http://maven.apache.org/POM/4.0.0"
         xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
         xsi:schemaLocation="http://maven.apache.org/POM/4.0.0 
                             http://maven.apache.org/xsd/maven-4.0.0.xsd">
    <modelVersion>4.0.0</modelVersion>

    <groupId>com.example</groupId>
    <artifactId>my-app</artifactId>
    <version>1.0-SNAPSHOT</version>
    <packaging>jar</packaging>

    <dependencies>
        <!-- Example Dependency -->
        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>4.13.2</version>
            <scope>test</scope>
        </dependency>
    </dependencies>
</project>
---



## 🔧 Maven Lifecycle

mvn clean        # Removes target directory
mvn compile      # Compiles the source code
mvn test         # Runs tests
mvn package      # Packages compiled code into JAR/WAR
mvn install      # Installs package into local repository
mvn deploy       # Deploys to remote repository




