# Parent Pom Project

## 1. Project's Title

- The name of project : Parent pom
- The goal of this project is to use same version of java and spring version

## 2. Project Description

- When you work with maven you can set at the parent pom this project
- Then your project is ready to use with specific version of Java and Spring Boot version
- The main goal is when you want to change the version of java, you just need to change the parent pom version
    - because parent need to upgrade due java new version, then your project setting up to work with new version
- This project is useful because your project doesn't managing project version. This project does for you !!!
- The project run with maven with Java 17 and Spring Boot 3

## 3. How to Install and Run the Project
- On your pom.xml
  - you have section parent, you just need to import the package
```
    <parent>
        <groupId>com.ranushan</groupId>
        <artifactId>parent-pom</artifactId>
        <version>0.0.1-SNAPSHOT</version>
        <relativePath/>
    </parent>
```
- After that you have 2 possiblities :
  - you can load your project
  - you can download on your repository (.m2/repository) by running command : `mvn clean install`

## 4. How to Use the Project
- The project automatically load all that you need for working on maven project
- Control version of JDK <strong>(Current : JAVA 17)</strong>
- Control version of Spring boot <strong>(Current : 3.2.5)</strong>
- By Default Set Lombok for all project
