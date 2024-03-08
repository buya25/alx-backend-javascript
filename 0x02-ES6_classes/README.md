# Tasks README

Welcome to the repository for JavaScript tasks focusing on ES6 classes. Each task provides a specific challenge to test your understanding and implementation of classes, constructors, methods, getters, setters, inheritance, and more.

## Installation

To run these tasks locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone <repository_url>
   ```

2. Navigate to the project directory:

   ```bash
   cd alx-backend-javascript/0x02-ES6_classes
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

## Usage

Each task has its own JavaScript file with an associated test file for execution. You can execute each task by running the respective main file.

### Task Execution

To execute a specific task, run the corresponding main file:

```bash
npm run dev <task_number>-main.js
```

Replace `<task_number>` with the task number you want to execute.

## Task Overview

1. **You used to attend a place like this at some point**: Implement a class named `ClassRoom` with a constructor attribute `maxStudentsSize`.

2. **Let's make some classrooms**: Import the `ClassRoom` class and implement a function named `initializeRooms` to return an array of `ClassRoom` objects with specified sizes.

3. **A Course, Getters, and Setters**: Implement a class named `HolbertonCourse` with constructor attributes and getters/setters.

4. **Methods, static methods, computed methods names..... MONEY**: Implement a class named `Currency` with constructor attributes and a method named `displayFullCurrency`.

5. **Pricing**: Import the `Currency` class and implement a class named `Pricing` with constructor attributes, getters/setters, and a method named `displayFullPrice`.

6. **A Building**: Implement an abstract class named `Building` with a constructor attribute and a method that must be overridden by subclasses.

7. **Inheritance**: Import `Building` and implement a subclass named `SkyHighBuilding` with constructor attributes and an overridden method.

8. **Airport**: Implement a class named `Airport` with constructor attributes and a default string description.

9. **Primitive - Holberton Class**: Implement a class named `HolbertonClass` with constructor attributes and methods to be cast into a number or string.

10. **Vroom**: Implement a class named `Car` with constructor attributes and a method named `cloneCar`.

11. **EVCar**: Import `Car` and implement a subclass named `EVCar` with constructor attributes, a method `cloneCar` that returns an instance of `Car`, and privacy considerations.

## Contributing

Contributions are welcome! Feel free to open issues or pull requests for any improvements or additional features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
