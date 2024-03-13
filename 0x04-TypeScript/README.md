## Project: TypeScript Tasks

This repository contains solutions to TypeScript tasks for a backend JavaScript course. Each task is located in a separate directory and includes detailed instructions on what needs to be implemented. Below is a summary of each task along with the directory structure and configuration files.

### Task 0: Creating an interface for a student
- **Directory:** `task_0`
- **Files:**
  - `js/main.ts`
  - `package.json`
  - `.eslintrc.js`
  - `tsconfig.json`
  - `webpack.config.js`
- **Description:** Implements an interface named `Student` and creates an array of students. Renders a table using Vanilla JavaScript and appends rows to display student information.

### Task 1: Let's build a Teacher interface
- **Directory:** `task_1`
- **Files:**
  - `js/main.ts`
  - `webpack.config.js`
  - `tsconfig.json`
  - `package.json`
- **Description:** Defines a `Teacher` interface with specific attributes and properties. Allows for adding custom attributes to objects without explicitly defining them.

### Task 2: Extending the Teacher class
- **Directory:** `task_2`
- **Files:**
  - `js/main.ts`
- **Description:** Extends the `Teacher` interface to create a new interface named `Directors`. Adds an attribute named `numberOfReports` to the `Directors` interface.

### Task 3: Printing teachers
- **Directory:** `task_3`
- **Files:**
  - `js/main.ts`
- **Description:** Implements a function named `printTeacher` that returns formatted teacher information. Defines an interface named `printTeacherFunction` for the function.

### Task 4: Writing a class
- **Directory:** `task_4`
- **Files:**
  - `js/main.ts`
- **Description:** Creates a class named `StudentClass` with specific methods and properties. Describes the class constructor and class through an interface.

### Task 5: Advanced types Part 1
- **Directory:** `task_5`
- **Files:**
  - `js/main.ts`
- **Description:** Defines interfaces for `Director` and `Teacher` classes with specific methods. Implements classes `Director` and `Teacher` to fulfill interface requirements. Creates a function to create employee instances based on salary.

### Task 6: Creating functions specific to employees
- **Directory:** `task_6`
- **Files:**
  - `js/main.ts`
- **Description:** Implements functions `isDirector` and `executeWork` to perform specific actions based on employee type.

### Task 7: String literal types
- **Directory:** `task_7`
- **Files:**
  - `js/main.ts`
- **Description:** Defines a string literal type named `Subjects`. Implements a function named `teachClass` to return subject-specific strings based on input.

### Task 8: Ambient Namespaces
- **Directory:** `task_8`
- **Files:**
  - `js/main.ts`
  - `js/interface.ts`
  - `js/crud.d.ts`
- **Description:** Implements type declarations for CRUD operations using an external library. Utilizes ambient namespaces to define types.

### Task 9: Namespace & Declaration merging
- **Directory:** `task_9`
- **Files:**
  - `js/main.ts`
  - `js/subjects/Cpp.ts`
  - `js/subjects/Java.ts`
  - `js/subjects/React.ts`
  - `js/subjects/Subject.ts`
  - `js/subjects/Teacher.ts`
- **Description:** Organizes code into namespaces and utilizes declaration merging. Implements classes for different subjects and teachers.

### Task 10: Update task_4/js/main.ts
- **Directory:** `task_10`
- **Files:**
  - `js/main.ts`
- **Description:** Defines constants and objects for various subjects and teachers. Calls methods on subjects and prints the results.

### Task 11: Brand convention & Nominal typing
- **Directory:** `task_11`
- **Files:**
  - `js/main.ts`
- **Description:** Defines interfaces with a brand property for nominal typing. Implements functions to sum credits for major and minor subjects.

Feel free to explore each task directory for detailed implementation and instructions.
