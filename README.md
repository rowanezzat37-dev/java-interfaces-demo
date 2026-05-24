# 🏠 Smart Devices Controller (Interface & Exception Handling)

A Java-based system that models various smart home devices, demonstrating core concepts of **Object-Oriented Programming (OOP)**, specifically **Interfaces** and custom **Exception Handling**.

## 🚀 Key Features

- **Unified Interface (`Controllable`):** Ensures all devices implement standard operations (`turnOn`, `turnOff`, `getStatus`), allowing for polymorphic behavior.
- **Custom Exception Handling:** Implements specialized exceptions (e.g., `OpenDoor`, `InvalidStatus`, `LowBattery`) to manage hardware-specific states safely.
- **Polymorphic Execution:** Uses an array of `Controllable` objects in the `Main` class to interact with different device types uniformly.
- **Robustness:** Includes input validation and state management to prevent illegal device operations.

## 🛠️ Concepts Applied

- **Interfaces:** Defining a contract for device behavior.
- **Custom Exceptions:** Creating user-defined exceptions that extend `RuntimeException` for clean error handling.
- **Polymorphism:** Treating different smart devices as `Controllable` objects.
- **Try-Catch Blocks:** Ensuring the program remains stable even when hardware constraints (like an open microwave door) are violated.

## 💻 Project Structure

- `Controllable.java`: The main interface defining device behavior.
- `Microwave.java`, `SmartPhone.java`, `SmartWatch.java`: Concrete classes implementing the interface with custom logic and exceptions.
- `Main.java`: The driver class demonstrating the lifecycle of these devices.

## 👤 Author

**Rowan Ezzat Mohamed**
- GitHub: [@rowanezzat37-dev](https://github.com/rowanezzat37-dev)
