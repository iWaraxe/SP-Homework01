# Spring Framework XML Configuration Homework

## Objective
The goal of this homework is to solidify your understanding of basic Spring Framework concepts, focusing on XML configuration, Dependency Injection (DI), bean lifecycle, and bean scopes. You will set up a simple Spring project using IntelliJ and Maven, implement DI with XML configuration, explore bean lifecycle methods, and experiment with different bean scopes.

## Tasks

### 1. Setup a Simple Project
- **Objective**: Use IntelliJ IDEA and Maven to set up a basic Spring project.
- **Requirements**:
    - Create a new Maven project in IntelliJ IDEA.
    - Add Spring context dependency to your `pom.xml`.
    - Ensure the project can be built and run successfully.

### 2. Implement DI
- **Objective**: Create Java classes that simulate a basic weather monitoring system, and configure them using constructor and setter injections in XML. This assignment moves away from the typical service-repository architecture presented during the lectures to apply DI concepts in a different context.
- **Requirements**:
    - Create at least two simple Java classes that represent a basic weather monitoring system.
    - Use Spring XML configuration to wire these classes together using both constructor and setter injection methods.
    - Demonstrate the successful injection in a main class that retrieves beans from the Spring context and calls a method on the service class.

To introduce variety and challenge beyond the standard service and repository examples, let's design a homework assignment project around a different context. This will encourage you to apply the concepts of Dependency Injection (DI) in a new setting, enhancing their understanding and creativity. Here's a refreshed assignment focusing on a fictional scenario involving a `WeatherStation` and `TemperatureSensor` to represent the service and repository components, respectively.

### Homework Assignment: Implementing DI with a Weather Monitoring System

#### **Objective**
Create Java classes that simulate a basic weather monitoring system, and configure them using constructor and setter injections in XML. This assignment moves away from the typical service-repository architecture to apply DI concepts in a different context.

#### **Requirements**

1. **Create Java Classes for the Weather Monitoring System**
  - **TemperatureSensor Class**: This class simulates a temperature sensor device that can read the current temperature. Think of it as a "repository" that fetches data.
  - **WeatherStation Class**: This class acts as a "service" that uses `TemperatureSensor` to provide weather information.

2. **XML Configuration for Dependency Injection**
  - Configure both `TemperatureSensor` and `WeatherStation` beans in XML. Use constructor injection to inject a sensor ID into `TemperatureSensor`, and setter injection to associate `TemperatureSensor` with `WeatherStation`.

3. **Main Class to Demonstrate DI**
  - Implement a main class that retrieves the `WeatherStation` bean from the Spring context and calls `displayTemperature()` to demonstrate successful dependency injection.

#### **Deliverables**
You are required to submit:
- Source code for `TemperatureSensor` and `WeatherStation` classes.
- The Spring XML configuration file.
- The main class demonstrating the successful wiring and execution.
- A brief documentation explaining their implementation and any assumptions made.

This revised assignment encourages you to think creatively about applying DI in different scenarios while still adhering to the core principles discussed in class.

### 3. Bean Lifecycle Experiment
- **Objective**: Define beans with `init-method` and `destroy-method`, observe their lifecycle in a simple application.
- **Requirements**:
    - Create a class that includes methods suitable for `init-method` and `destroy-method`.
    - Configure these methods in your Spring XML configuration.
    - In a main class, load the Spring context and close it, observing the console output to verify that lifecycle methods are called at the correct times.

### 4. Explore Bean Scopes
- **Objective**: Configure beans with different scopes (`singleton`, `prototype`, `request`, `session`, and `globalSession`) and document how each behaves within the application context.
- **Requirements**:
    - Define multiple beans in your XML configuration with first two of the mentioned scopes.
    - Document your observations.

## Further Reading
- Visit the [official Spring documentation](https://docs.spring.io/spring-framework/docs/current/reference/html/core.html#beans) for a deeper understanding of XML configuration.
- Explore articles and tutorials on the transition from XML to annotation-based configuration in Spring to prepare for upcoming lectures.

## Submission
Submit your project as pull request in GitHub Classroom repository containing the Maven project with all source code and configurations.

Good luck!