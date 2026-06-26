# Electronic Voting System

Electronic Voting System is a desktop application developed in Java for managing electronic elections through a secure and structured voting process.

The application follows the Model–View–Controller (MVC) architectural pattern and provides different functionalities for administrators and voters, including election management, user authentication, vote submission, and result visualization. Data is persisted in a relational database, while the project documentation includes UML diagrams describing the system architecture and design.

This project was developed as part of the Software Engineering course at the University of Milan.

---

## Features

- User authentication.
- Election and voting session management.
- Political party and candidate management.
- Support for multiple voting methods.
- Secure vote registration.
- Vote counting and result visualization.
- Relational database persistence.
- UML documentation of the software architecture.

---

## Technologies

- Java
- JavaFX
- Maven
- MySQL
- JDBC
- MVC Architecture
- Log4j

---

## Software Architecture

The application follows the **Model–View–Controller (MVC)** design pattern.

The system is organized into three main layers:

- **Model** – manages business logic and database access.
- **View** – graphical user interface developed with JavaFX.
- **Controller** – coordinates user interactions and application logic.

The project also includes UML documentation describing the software architecture, use cases, activity diagrams, sequence diagrams, deployment diagram, component diagram and database schema.

---

## Project Structure

```text
.
├── docs/
├── src/
│   ├── main/
│   ├── resources/
│   └── test/
├── pom.xml
├── README.md
└── LICENSE
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/alecucco/electronic-voting-system.git
```

Move into the project directory:

```bash
cd electronic-voting-system
```

Build the project using Maven:

```bash
mvn clean install
```

The application can be executed directly from an IDE such as IntelliJ IDEA or Eclipse.

---

## Main Functionalities

The application allows administrators to:

- manage elections;
- create and configure voting sessions;
- manage parties and candidates;
- close voting sessions;
- view election results.

Voters can:

- authenticate;
- access available voting sessions;
- cast their vote;
- confirm the submitted vote.

---

## Documentation

The repository contains a complete software engineering documentation, including:

- Use Case Diagram
- Class Diagram
- Component Diagram
- Deployment Diagram
- Activity Diagrams
- Sequence Diagrams
- Entity-Relationship Diagram
- Database schema

---

## Notes

This project focuses on software architecture, object-oriented design, graphical user interface development, and relational database integration.

Generated files and IDE-specific folders (such as `target/`, `.idea/`, `.settings/`, and `bin/`) should not be included in the repository.

---

## Author

**Alessandro Cucco**

Master's Degree in Computer Science  
University of Milan
