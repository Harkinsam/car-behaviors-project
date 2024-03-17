# Car Simulation

This Java project simulates different types of cars with varying features and behaviors.

## Description

The project includes classes for a base Car, Mitsubishi, and Ford. Each class represents a specific type of car with its own characteristics such as cylinders, name, and engine status. The project demonstrates inheritance and method overriding in Java.

## Classes

### Car Class

Represents a basic car with properties like cylinders, name, engine status, and number of wheels. Includes methods for starting the engine, accelerating, and braking.

### Mitsubishi Class

Extends the Car class and adds specific behaviors for a Mitsubishi car, including customized accelerate, brake, and engine start methods.

### Ford Class

Similar to the Mitsubishi class, the Ford class extends Car and provides specific functionalities for a Ford car.

## Usage

1. Create instances of different car classes:
   ```java
   Car car = new Car(8, "Base car");
   Mitsubishi mitsubishi = new Mitsubishi(6, "Outlander VRW 4WD");
   Ford ford = new Ford(6, "Ford Falcon");
Use the methods provided by each class to interact with the cars:

1. **startEngine():**
   - Description: Starts the engine of the car.

2. **accelerate():**
   - Description: Simulates acceleration of the car.

3. **brake():**
   - Description: Simulates braking of the car.
## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
