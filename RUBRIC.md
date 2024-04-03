# Grading Rubric for Spring XML Configuration Homework

## Setup a Simple Project (20 Points)
- [ ] Project is correctly set up with Maven and Spring context dependency (10 points)
- [ ] Project can be built and run without errors (10 points)

## Implement DI with a Weather Monitoring System (30 Points)
- [ ] TemperatureSensor and WeatherStation classes are created to simulate a weather monitoring system (10 points)
- [ ] Constructor and setter injections for the Weather Monitoring System are correctly implemented and configured in XML (10 points)
- [ ] The main class demonstrates successful injection and functional interaction between TemperatureSensor and WeatherStation (10 points)

## Bean Lifecycle Experiment (25 Points)
- [ ] A class with suitable `init-method` and `destroy-method` is created (10 points)
- [ ] Lifecycle methods are correctly configured in XML and demonstrated to be called at the appropriate times (15 points)

## Explore Bean Scopes (25 Points)
- [ ] Singleton and Prototype beans are correctly defined in XML and demonstrated within the application (10 points each)
- [ ] Observations and behavior of Singleton and Prototype scopes are well-documented (5 points)

## Additional Notes:
- Deduct up to 10 points for lack of documentation or incorrect project structure.
- Bonus points (up to 5) may be awarded for additional creativity in demonstrations or thorough documentation.

Total Points: 100