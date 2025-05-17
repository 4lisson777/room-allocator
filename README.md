# Room Allocator

An intelligent classroom scheduling system for educational institutions that optimizes space utilization and prevents scheduling conflicts.

![Java Version](https://img.shields.io/badge/Java-17-brightgreen)
![JavaFX](https://img.shields.io/badge/JavaFX-17-orange)
![License](https://img.shields.io/badge/License-MIT-blue)

## 📋 Overview

Room Allocator is a comprehensive solution designed to streamline classroom allocation in educational environments. The system intelligently assigns appropriate spaces based on class requirements, instructor availability, and room specifications while preventing scheduling conflicts.

## ✨ Key Features

- **Smart Room Management**: Track classroom capacity, available resources, and maintenance periods
- **Intelligent Scheduling**: Automatically assign rooms based on capacity, available resources, and time constraints
- **Conflict Prevention**: Built-in validation to prevent double-booking of rooms or professors
- **Comprehensive Reporting**: Generate usage statistics and exportable reports
- **User-Friendly Interface**: Intuitive JavaFX interface for easy navigation and management

## 🛠️ Technology Stack

- **Core**: Java 17+
- **UI Framework**: JavaFX
- **Data Persistence**: JDBC/Hibernate
- **Reporting Tools**: iText/JasperReports (PDF), Apache POI (CSV)
- **Testing**: JUnit, Mockito
- **Time Management**: Java Time API

## 📊 UML Diagrams

Project architecture and data relationships are documented using draw.io UML diagrams located in the `/docs/diagrams` directory.

## 🚀 Getting Started

### Prerequisites

- Java JDK 17 or higher
- Maven 3.6+
- Git

### Installation

```bash
# Clone the repository
git clone git@github.com:4lisson777/room-allocator.git

# Navigate to project directory
cd room-allocator

# Build the project
mvn clean install

# Run the application
mvn javafx:run
```

## 📁 Project Structure

```
room-allocator/
├── src/
│   ├── main/
│   │   ├── java/           # Source code
│   │   │   ├── model/      # Domain models
│   │   │   ├── controller/ # Application logic
│   │   │   ├── view/       # UI components
│   │   │   ├── util/       # Helper classes
│   │   │   └── report/     # Report generation
│   │   └── resources/      # UI resources, configs
│   └── test/               # Unit tests
├── docs/
│   └── diagrams/           # UML diagrams (draw.io)
├── pom.xml                 # Project dependencies
├── LICENSE                 # MIT License
└── README.md               # Project documentation
```

## 💡 Usage Examples

```java
// Sample code showing how to allocate a room will be added here
```

## 📑 Documentation

Detailed documentation will be available in the `/docs` directory including:
- User Manual
- API Documentation
- Architecture Overview

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a pull request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🧑‍💻 Authors

- **Alisson Santos**
- **Pedro Roma**
- **Luiz Maranhao**
- **Mario Jorge**
- **João Pedro**
