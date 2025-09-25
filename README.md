
#Campus Course & Records Manager (CCRM)

A console-based Java SE application for managing students, courses, enrollments, grades, and transcripts in a university setting.
This project demonstrates core Java concepts (OOP pillars, exception handling, collections, streams, NIO.2 file operations, recursion, enums, lambdas, and design patterns like Singleton & Builder) while offering practical features like data import/export, backup utilities, and transcript generation.

✨ Features

Student Management – Create, update, list, and deactivate students; generate profiles & transcripts.

Course Management – Add, update, search, and filter courses by department, semester, or instructor.

Enrollment & Grading – Enroll/unenroll students with rules (e.g., max credits/semester), compute GPA, and record letter grades.

File Operations – Import/export data using CSV/text files, create timestamped backups, and recursive directory utilities.

Reports – Stream-based GPA distribution and top student reports.

CLI Workflow – Menu-driven interface covering all operations.


🛠 Tech Stack

Language: Java SE

Architecture: Modular packages (cli, domain, service, io, util, config)

Concepts: Encapsulation, Inheritance, Abstraction, Polymorphism, Interfaces, Nested Classes, Lambdas, Enums

APIs & Utilities: Java Date/Time API, NIO.2, Streams, Assertions

 Java Platform & Architecture Explained
This document provides a clear breakdown of the different Java editions and the core components of its architecture.

Java Editions: ME vs. SE vs. EE
Java isn't a single entity; it's a platform that comes in different editions, each tailored for specific types of applications.

Java SE (Standard Edition) 🖥️
This is the core Java platform. It provides the fundamental APIs (for collections, networking, I/O, etc.) and the Java Virtual Machine (JVM). If you're building a desktop or console application, you're using Java SE.

Analogy: Think of it as the foundation and frame of a house. It's the essential structure upon which everything else is built.

Java EE (Enterprise Edition) / Jakarta EE 🌐
Now known as Jakarta EE, this edition is built on top of Java SE. It adds a vast library of APIs needed for building large-scale, multi-tiered, and reliable network applications. This is the choice for web services, banking applications, and complex business systems.


Analogy: This is the fully-equipped house, complete with industrial-grade plumbing, electrical systems, and security (Servlets, JavaServer Pages, Enterprise Beans).

Java ME (Micro Edition) 📱
This is a lightweight, stripped-down subset of Java SE. It’s designed for resource-constrained devices like IoT sensors, smart cards, and older mobile devices. It provides a small-footprint JVM and a limited set of APIs tailored for low memory and power consumption.

Analogy: This is a smart home sensor or a tiny cabin. It’s highly specialized, efficient, and contains only what is absolutely necessary to perform its function.

Comparison Summary
Feature	Java ME (Micro Edition)	Java SE (Standard Edition)	Java EE (Enterprise Edition)
Target	Small, resource-constrained devices (IoT, etc.)	Desktop, server, console applications	Large-scale, distributed enterprise systems (web apps)
Scope	Subset of SE	Core platform	Superset of SE
Key APIs	Lightweight UI, specific I/O, security for small devices	Core APIs (Collections, I/O, Swing)	Servlets, JSP, Enterprise Beans (EJB), JMS, REST APIs

Export to Sheets
Java Architecture: JDK vs. JRE vs. JVM
These three acronyms represent the nested components of the Java platform. They are the machinery that makes Java work.

JVM (Java Virtual Machine) ⚙️
The JVM is the heart of the Java platform. It's an abstract computing machine that enables a computer to run a Java program. When you compile your Java code, it's turned into bytecode, which is a set of instructions for the JVM. The JVM then translates this bytecode into native machine code for the specific operating system it's running on. This is the key to Java's "write once, run anywhere" principle.




Analogy: The JVM is like a universal video game console engine. Game developers create games (bytecode) for the engine, and the engine itself is adapted to work on any TV (operating system).

JRE (Java Runtime Environment) 🏃
The JRE is the software package that provides everything needed to run Java applications on your machine. It includes the JVM plus the Java Class Libraries—a set of standard code (like String, List, etc.) that your program can use. You need the JRE installed to run any Java application.

Analogy: The JRE is the game console engine (JVM) bundled with the essential game assets and libraries (like graphics renderers and sound engines) that all games need to function.

JDK (Java Development Kit) 🛠️
The JDK is the full development package for Java programmers. It contains everything the JRE has, plus the development tools necessary to create Java applications. The most important tools are the compiler (javac), the archiver (jar), and the debugger (jdb). If you want to write Java code, you need the JDK.

Analogy: The JDK is the complete game developer's studio kit. It includes the console and its essential libraries (JRE) plus all the software needed to create a new game from scratch (compiler, debugger).

The Relationship
The relationship is simple:
JDK contains JRE, which in turn contains JVM.

JDK = JRE + Development Tools
JRE = JVM + Core Libraries






---

👉 Perfect for learning Java SE and showcasing software engineering best practices in a structured project.

