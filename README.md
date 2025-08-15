# Hello Java Maven - Jenkins Build

## 📌 Overview
This is a simple Java "Hello World" application built using **Maven** and deployed through **Jenkins** as part of Task 8 in my DevOps internship.  
It demonstrates how Jenkins can be integrated with Maven to compile, package, and run a Java project.

---

## 🛠 Tools & Technologies
- **Java JDK 11**
- **Apache Maven 3.8.6**
- **Jenkins LTS**
- **Git & GitHub**
- **Docker** (to run Jenkins)

---

## 📂 Project Structure
hello-java-maven/
├── pom.xml
└── src/
└── main/
└── java/
└── HelloWorld.java


## 📜 Code
**HelloWorld.java**
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, Jenkins + Maven!");
    }
}
pom.xml contains Maven build configuration including Java compiler plugin.

🚀 Steps Performed
Created HelloWorld.java and pom.xml.

Pushed the code to a GitHub repository.

Installed and configured Jenkins (via Docker).

Added Maven and JDK in Global Tool Configuration.

Created a Jenkins Freestyle project:

Linked to GitHub repo.

Added Maven build step: clean package.

Triggered Build Now in Jenkins.

Verified [INFO] BUILD SUCCESS in console output.
