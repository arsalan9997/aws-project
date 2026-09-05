# AWS Student Management System

A fresher-level Java web application project demonstrating Git, Maven, AWS EC2, AWS S3 and Apache Tomcat.

## Technologies Used
- Java 17
- Maven
- Git and GitHub
- AWS EC2
- AWS S3
- Apache Tomcat
- Linux

## Project Workflow
Developer -> GitHub -> AWS EC2 -> Maven Build -> WAR File -> Tomcat -> Web Application

AWS S3 can be used for storing application images and documents.

## Build Locally
```bash
mvn clean package
```

The generated WAR file:
```text
target/student-management.war
```

## EC2 Deployment Steps
1. Launch an AWS EC2 instance.
2. Install Java, Git and Maven.
3. Clone this repository.
4. Run `mvn clean package`.
5. Install Apache Tomcat.
6. Copy the WAR file to `/opt/tomcat/webapps/`.
7. Open the application on port 8080.

## Example Commands
```bash
git clone YOUR_GITHUB_REPOSITORY_URL
cd aws-student-management
mvn clean package
sudo cp target/student-management.war /opt/tomcat/webapps/
```

## Resume Description
Developed and deployed a Java-based web application using Git and Maven. Hosted the application on AWS EC2 using Apache Tomcat and used AWS S3 for storing application assets and documents.
