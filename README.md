# Dev-D8
  Run a Simple Java Maven Build Job in Jenkins
# Dev-D8: Java Maven Build with Jenkins

## Objective
Set up Jenkins to build a simple Java application using Maven as part of a CI/CD pipeline.

## Tools Used
- Jenkins (running on AWS EC2 Ubuntu)
- Maven
- Java 17
- Git & GitHub

## Structure
- `hello-java-maven/` - Java source code and Maven `pom.xml`
- `screenshots/` - Jenkins build console output (success)

## Steps Performed
1. Installed Jenkins, Java, and Maven on EC2
2. Created a HelloWorld Java app and `pom.xml`
3. Configured Jenkins freestyle job to run `mvn clean package`
4. Built the job and verified successful build in console

## Result
Maven successfully built the Java project via Jenkins.
