# java-spring-tutorial-masterclass-learn-spring-framework-5

Quick Summary: Can't Find a good Spring Tutorial? Finally Understand Spring 5 With Spring Core, Spring MVC, Spring Boot 2 and more

<table>
<tr>
<th id="table-of-contents"> Table of Contents </th>
<th> Table of Contents (cont'd) </th>
</tr>
<tr>
<td>

[Section 1: Course Introduction](##section-1-Course-Introduction)

[Section 2: Install and Setup](##section-2-Install-and-Setup)

[Section 3: Maven and
your first project](##section-3-Maven-and-your-first-project)

[Section 4: Logging with
SLF4J & Logback](##section-4-Logging-with-SLF4J-&-Logback)

[Section 5: Multi module
Spring Project](##section-5-Multi-module-Spring-Project)

[Section 6: Lombok
Introduction](##section-6-Lombok-Introduction)

<!-- [Section 12: ](##section-12-)
[Section 13: ](##section-13-)
[Section 14: ](##section-14-)
[Section 15: ](##section-15-)
[Section 16: ](##section-16-)
[Section 17: ](##section-17-)
[Section 18: ](##section-18-) -->

</td>
<td>

[Section 7: Spring MVC](##section-7-Spring-MVC)

[Section 8: Spring Boot 2
Introduction](##section-8-Spring-Boot-2-Introduction)

[Section 9: Spring Boot 2
And Thymeleaf 3](##section-9-Spring-Boot-2-And-Thymeleaf-3)

[Section 10: Gradle
Introduction](##section-10-Gradle-Introduction)

[Section 11: Gradle Multi
Module Project Setup](##section-11-Gradle-Multi-Module-Project-Setup)

<!-- [Section 19: ](##section-19-)
[Section 20: ](##section-20-)
[Section 21: ](##section-21-)
[Section 22: ](##section-22-)
[Section 23: ](##section-23-)
[Section 24: ](##section-24-)
[Section 25: ](##section-25-)
[Section 26: ](##section-26-)
[Section 27: ](##section-27-)
[Section 28: ](##section-28-)
[Section 29: ](##section-29-)

[Section 30: ](##section-30-)
[Section 31: ](##section-31-)
[Section 32: ](##section-32-)
[Section 33: ](##section-33-)
[Section 34: ](##section-34-)
[Section 35: ](##section-35-)
[Section 36: ](##section-36-)
[Section 37: ](##section-37-) -->

</td>
</tr>
</table>

## Section 1: Course Introduction

## 3min

### [Back to Table of Contents](##table-of-contents)

### 1. Introduction

- Get up to speed with the Spring framework as quickly as possible!

- Work in progress course. Targets the latest release of this framework!

### 2. Content still to come

- Major topics to be added

  1. Spring Data

  2. JPA

  3. Hibernate

  4. Data versioning using Liquibase

## Section 2: Install and Setup

## 54min

### [Back to Table of Contents](##table-of-contents)

### 3. Which Version Of Java?

-

### 4. Installing JDK 11 on Windowns

-

### 5. Installing and Cofiguring IntelliJ IDEA on Windows

-

### 6. Installing JDK 11 on a Mac

-

### 7. Installing and Configuring IntelliJ IDEA on a Mac

-

### Installing JDK 11 on a Linux Machine

-

### 9. Installing and Configuring IntelliJ IDEA on a Linux Machine

-

## Section 3: Maven and your first project

## 31min

### [Back to Table of Contents](##table-of-contents)

### 10. Your Programming Career Questions Answered

- 106 videos, programming tips of the day

- [Programming Tips of the Day Video 1](https://www.youtube.com/watch?v=z_8Hocokycg&list=PLXtTjtWmQhg1YRG0L0dIT5B22Utujaq20)

### 11. Access to Programming Career Q&A

- [Programming Tips of the Day Video 1](https://www.youtube.com/watch?v=z_8Hocokycg&list=PLXtTjtWmQhg1YRG0L0dIT5B22Utujaq20)

### 12. Spring 5 Feature Overview

- The main features of Spring Framework 5 can be summarized as follows:

  1.

  2.

  3. **Core container updates** Spring 5 supports component

  4.

  5. **Reactive Programming Model** -

  6.

  7.

  8. **Discontined support** -

### 13. Maven and Other Tools

- What is Maven?

  - Maven is a software project management tool. It's used to manage build automation

  - Maven's primary goal is to allow a developer to understand the complete state

- Maven Feautures

  - Maven has

  - It offers consisteent

  - It boasts

  - It's able

  - It has a large and

  - It offers model based builds:

  - It also has dependency management:

  - And much more.

- Typical Maven Project Structure

  - IMAGE

- Alternatives

  - Apache Ant

    -

  - Gradle

    -

- How it works

- Find out about some of its features

### 14. Creating a Maven Project

- Creating Your First Maven Project

  - How to create a maven project.

  - How to build a maven project

- IntelliJ IDEA FILE

  - new package under src main java.

  - new class under the new package.

### 15. Importing Maven Projects

- Reimport if necessary.

- help bot will prompt sometimes.

### 16. Maven Lifecycle Plugin and Goals

- Maven Build Lifecycle

  - What is the Maven build lifecycle?

  - Maven is based around

  - There are three built-in build

  - Each of these build lifecycles is defined by a different list of build phases

  - a build phase

  - To check

- The Maven Default lifecycle

  - The default

    - validate

    -

    -

- Maven Plugins

  - "Maven" is really just

  - In other words,

  - In Maven :

    - Build plugins

    - Reporting plugins

- Maven Plugins and Goals

  - All plugins

  - Whenever

  - Plugins

  -

  - For example,

  - The compile

  - The testCompile

### 17. Fix our Maven Project

- Won't worry too much about plugins at the moment.

- Look at Lifecycle under View, Tool Windows, Maven.

- FILE hello-maven

## Section 4: Logging with SLF4J & Logback

## 37min

### [Back to Table of Contents](##table-of-contents)

### 18. What is Logging?

- An Introduction to Logging

  - What is logging?

  - Logging use cases.

  - History.

  - Logging API and implementations

- What is Logging?

  - Logging is

  - Logging is

  - Logging gives you data

  - There are two

  - With good logging in place,

  - The first and foremost advantage

  - The great thing about logging

  - Logging will also help you to

- Logging use Cases

  - Debugging

  - Help to

  - Tracing

  - Creating data

  - Whatever

- History

  - Historically, Java logging

  - Debug logs

  - In production,

  - Log records before the

- Slf4j - The Logging API

  - We will be

  - There are 2 aspects

  - The Logging API

  - The Logging implementation

  - Both API and implementation

  - slf4j-api is an

  - There are

  - You can think

- Logging implementation - Using logback

  - Each logging

  - Logback is intended

  - Logback is reliable

  - Logback is highly

  - Logback is built using maven

  - Logback has three main components:

    - loggers:

    - appenders:

    - layouts:

  - Logback

- Advantages of logback

  - Logging behavior

  - It uses

  - The format

  - The target or

  - Logback

  - Logback

- Why logback and log4j

  - Logback

  - Large

  - Both

  - Logback

  - Logback

  - Logback

  - Configuration

  - Automatic

  - Automatic

  - Filters

  - And much more

### 19. Using Logging with Logback

-

### 20. Logback Configuration

-

## Section 5: Multi module Spring Project

## 3hr 40min

### [Back to Table of Contents](##table-of-contents)

### 21. Project Overview

- Talk about

- Learn

-

-

- core , console, web module.

- Benefits of a multi-module project

  - When

  - You can

  - Easier maintainability

  - One single maven command

  - And

- UML

  - The

    - modeling

    - analysis

  - UML
  - UML

  - It can

  - In simple

  - for more info visit https://www.uml-diagrams

### 2

-

### 2

-

### 2

-

### 2

-

### 2

-

### 2

-

### 2

-

### 2

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 3

-

### 4

-

### 4

-

### 4

-

### 4

-

### 44. Code Cleanup Challenge

-

## Section 6: Lombok Introduction

## 28min

### [Back to Table of Contents](##table-of-contents)

### 45. Lombok Introduction

- Let's discuss

- Project Lombok

- As an exmaple

- With other JVM

- With Project

- Those methods will be genearted

- It also saves

- This will allow you

- Lombok is using

- When your project gets com

- The final code

- Modern

- @Getter

  - You

  - A

- @Setter

  - A default

- @ToString

  - generates

- @EqualsAndHashCode

  - will

- @RequiredArgsConstructor

  - will

- @Slf4j
  - will
- There are many more

- @Data

  - Generates boileplate code

  - It combines

  - Constructor is not

- PHOTO

- PHOTO

- We will add the Lombok dependency in the next lesson.

### 46. Setup Lombok

- Lombok in Action

  - Let's start by installing the IntelliJ Lombok plugin.

  - And then we will setup Lombok as a dependency in our project.

- FILE

### 47. Using Lombok

- Time to start using Lombok in our code to see how it works

- FILE

### 48. Lombok Challenge

- Go through the

- Tip: you only need @Slf4j and @Getter annotations

- FILE

## Section 7: Spring MVC

## 3hr 51min

### [Back to Table of Contents](##table-of-contents)

### 49. Spring MVC Introduction

- Spring Web MVC is

- It has shipped

- Spring MVC

- MVC stands

- This pattern

- MVC :

  - **Model (M):**

  - **View (V)**

  - **Controller (C)**

- In the

- The actual work is

- The

- The

- The

- In other words

- With the Spring

- For example

- Later

- Spring MVC

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 5

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 6

-

### 7

-

### 7

-

### 72. View Item Challenge

-

## Section 8: Spring Boot 2 Introduction

## 36min

### [Back to Table of Contents](##table-of-contents)

### 73. Introduction to Spring Boot 2

-

### 7

-

### 7

-

### 76. Simple Spring Boot Application

-

## Section 9: Spring Boot 2 And Thymeleaf 3

## 4hr 3min

### [Back to Table of Contents](##table-of-contents)

### 77. Add Spring Boot to an Existing Project

-

### 97. Thymeleaf Recap

-

## Section 10: Gradle Introduction

## 31min

### [Back to Table of Contents](##table-of-contents)

### 98. What is Gradle?

-

### 103. Simple Spring Gradle Application

-

## Section 11: Gradle Multi Module Project Setup

## 39min

### [Back to Table of Contents](##table-of-contents)

### 104. Creating a Spring Boot Project Challenge

-

### 10.

-

### 10.

-

### 10.

-

### 108. More Content

- Spring 4 Content is available in later sections, but more Spring 5 content is also expected!

### 109. Are we done? Is there any more content?

- Refer back to lecture 2 for a list of upcoming content.

- Old content was created with Spring 4 in these later sections and certain things won't work well with Spring 4. For example JDK 11.

- In the next section, the entire old course videos are included - old installation videos, Eclipse IDE, etc.

- Keep that in mind.

<!-- ## Section 12:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 13:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 14:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 15:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 16:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 17:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 18:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 19:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 20:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 21:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 22:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 23:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 243:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

-

## Section 25:

## min

### [Back to Table of Contents](##table-of-contents)

###

-

###

- -->

## Section 26: Extra Information - Source code, and other stuff

## 14min

### [Back to Table of Contents](##table-of-contents)

### 272. Source code

- Really only 11 relevant sections right now.

### 273. Bonus Lecture and Information

- Free material:

  1. Learn to code course! Youtube
  2. Manual! ebook!
  3. Career path ebook!
  4. Udemy bonus / free content.
