# Campus Course and  Records Manager (CCRM)

It is a Java console application for maintaing records of students, courses, grades , etc  in an university.

## Features

- Student Management (add, list, update, deactivate)
- Grade Management (record marks, compute GPA)
- Course Management (add, list, update, deactivate, search)
- Enrollment Management (enroll, unenroll with business rules)
- etc

## Evolution of Java

- 1995: Java 1.0 released by Sun Microsystems
- 1997: Java 1.1 with JDBC, RMI, and reflection
- 2000: Java 1.3 with HotSpot JVM
- 2004: Java 5 with generics, annotations, autoboxing
- 2017: Java 9 with module system
- 2018: Java 11 as LTS version
- 2023: Java 21 with new improvements

## Java Platforms Comparison

| Platform | Full Name | Purpose | Key Features |
|----------|-----------|---------|--------------|
| Java SE | Standard Edition | Desktop and server applications | Core Java libraries, JVM |
| Java EE | Enterprise Edition |Commercial Applications| Servlets, JSP, EJB, JMS (now Jakarta EE) |
| Java ME | Micro Edition | small devices | Limited libraries for constrained environments |

## Java Architecture

- **JDK (Java Development Kit)**: Development environment including compiler, debugger, etc
- **JRE (Java Runtime Environment)**: Runtime environment for executing Java programs
- **JVM (Java Virtual Machine)**: Executes Java bytecode, portable

JDK contains JRE, which contains the JVM. Developers use the JDK to create applications, which run on  JRE using the JVM.

## Installation on Windows

1. Download JDK from Oracle's website
2. Run installer and follow  instructions 
3. Set JAVA_HOME environment variable to JDK installation path
4. Add %JAVA_HOME%\bin to PATH environment variable
5. Do verification of installation with `java -version` in command prompt

## Eclipse IDE Setup

1. Download Eclipse IDE for Java Developers
2. Extract to a folder and run eclipse.exe
3. Create a new Java project
4. Configure JDK in project properties
5. Create packages and classes as needed
- Note-reference taken from Eclipse's website.

## How to Run

1. Clone repository
2. Compile with `javac -d bin src/**/*.java`
3. Run with `java -cp bin edu.ccrm.Main`

## Enabling Assertions

Add `-ea` flag when running application: