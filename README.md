# 🚀 C++ 7-Days Bootcamp

[![C++](https://img.shields.io/badge/C++-17-blue.svg)](https://isocpp.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/adhikareeprayush/CPP-ACES-2081-SUBMISSIONS)

A comprehensive 7-day C++ bootcamp designed to take you from basics to intermediate-level Object-Oriented Programming concepts. This repository contains all the code examples, hands-on exercises, and resources covered during the bootcamp.

---

## 📋 Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Daily Curriculum](#daily-curriculum)
- [Extras](#extras)
- [Certification Task](#certification-task)
- [Contributing](#contributing)
- [License](#license)

---

## 📖 About

This bootcamp is organized by **ACES (Association of Computer Engineering Students)** and covers fundamental to intermediate C++ concepts including:

- Object-Oriented Programming (OOP) principles
- C++ language fundamentals
- Functions, Arrays, and Pointers
- Classes and Objects
- Inheritance and Polymorphism
- Operator Overloading and File I/O
- Templates and Exception Handling

---

## ✅ Prerequisites

Before starting this bootcamp, ensure you have:

- Basic understanding of programming concepts
- A C++ compiler installed (g++, clang++, or MSVC)
- An IDE or text editor (VS Code, Code::Blocks, CLion, etc.)
- Git installed for version control

### Recommended Setup

```bash
# Check if g++ is installed
g++ --version

# If not installed (Ubuntu/Debian)
sudo apt-get install g++

# If not installed (macOS)
brew install gcc

# If not installed (Windows)
# Install MinGW or use Visual Studio
```

---

## 🚀 Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/adhikareeprayush/CPP-7-Days-Bootcamp.git
   cd CPP-7-Days-Bootcamp
   ```

2. **Navigate to a day's folder**

   ```bash
   cd day1_intro_oop_basics
   ```

3. **Compile and run a C++ file**
   ```bash
   g++ -o output hello_world.cpp
   ./output
   ```

---

## 📁 Project Structure

```
CPP-7-Days-Bootcamp/
├── README.md                          # Main documentation
├── day1_intro_oop_basics/             # Day 1: Introduction & OOP Basics
│   ├── hello_world.cpp
│   └── compare_c_vs_cpp.cpp
├── day2_language_fundamentals/        # Day 2: C++ Fundamentals
│   ├── basic_calculator.cpp
│   ├── io_manipulators_demo.cpp
│   └── main_with_arguments.cpp
├── day3_functions_arrays/             # Day 3: Functions & Arrays
│   ├── array_function.cpp
│   ├── array_pointer.cpp
│   ├── calculate_area.cpp
│   ├── default_message.cpp
│   ├── multiply_overload.cpp
│   ├── pass_by_val_vs_ref.cpp
│   ├── pointers.cpp
│   ├── power.cpp
│   ├── square_cube.cpp
│   ├── strings.cpp
│   └── problems/
│       ├── array_sorting.cpp
│       ├── max_array.cpp
│       └── min_array.cpp
├── day4_classes_objects/              # Day 4: Classes & Objects
│   ├── README.md
│   ├── class.cpp
│   ├── constructors.cpp
│   ├── count.cpp
│   ├── descructors.cpp
│   └── person.cpp
├── day5_inheritance_polymorphism/     # Day 5: Inheritance & Polymorphism
│   ├── README.md
│   ├── access.cpp
│   ├── inheritance.cpp
│   ├── invocation_constructor.cpp
│   ├── polymorphism.cpp
│   └── practice1-3.cpp
├── day6_operator_overloading_file/    # Day 6: Operator Overloading & File I/O
│   ├── README.md
│   ├── add.cpp
│   ├── coordinates.cpp
│   ├── file.cpp
│   ├── friend_function_overloading.cpp
│   └── friend.cpp
└── day7_templates_exception_handling/ # Day 7: Templates & Exception Handling
    └── README.md
```

---

## 📚 Daily Curriculum

### 🟢 **Day 1 – Introduction to OOP & C++ Basics**

**Objectives:**

- Understand why OOP is needed.
- Get introduced to C++ syntax and structure.

**Topics:**

- Problems with Procedure-Oriented Programming
- What is OOP? Core concepts: Class, Object, Encapsulation, Abstraction, Inheritance, Polymorphism
- Advantages of OOP
- Overview of C++: History, Features, Use Cases
- First C++ Program (`iostream`, `main()`, `cout`, `cin`)
- Compile and run in any IDE or terminal

**Hands-On:**

- Write and run a basic C++ program
- Compare simple C vs. C++ code structure

**Day 1/2 Slides:**

- [Click Here](https://www.figma.com/slides/GDxk45QC8EFq27Rng46ogK/CPP-ACES?node-id=1-25&t=LVOcI8dKBrunFvTL-1)

---

### 🟢 **Day 2 – C++ Language Fundamentals**

**Objectives:**

- Learn C++ syntax and data types
- Understand control flow

**Topics:**

- Keywords, Identifiers, Data Types
- Variables, Constants (`const`)
- Operators and Expressions
- Conditional Statements (`if`, `switch`)
- Loops (`for`, `while`, `do-while`)
- `cin` and `cout`, `endl`, manipulators

**Hands-On:**

- Create a calculator using conditionals and loops
- Use I/O manipulators for formatting output

**Day 1/2 Slides:**

- [Click Here](https://www.figma.com/slides/GDxk45QC8EFq27Rng46ogK/CPP-ACES?node-id=1-25&t=LVOcI8dKBrunFvTL-1)

---

### 🟢 **Day 3 – Functions & Arrays**

**Objectives:**

- Learn about modular programming
- Understand arrays and basics of pointers

**Topics:**

- Function syntax, declaration/definition
- Function Overloading
- Default Arguments
- Pass by Value vs Reference
- Arrays: 1D, basics of 2D
- Intro to Pointers and Strings

**Hands-On:**

- Write overloaded functions (e.g., `add(int, int)` and `add(double, double)`)
- Pass arrays to functions
- Reverse a string using pointer arithmetic

**Day 3 Slides:**

- [Click Here](https://www.figma.com/deck/Ieba5luhmsgCKYtCliKHX5/CPP-ACES-Day-3?node-id=19-184&p=f&t=ynn3oqwN8dj5BA6Y-0&scaling=min-zoom&content-scaling=fixed&page-id=0:1)

---

---

### 🟢 **Day 4 – Classes and Objects**

**Objectives:**

- Understand class-based programming
- Work with constructors and destructors

**Topics:**

- Defining Classes and Objects
- Access Specifiers (`private`, `public`, `protected`)
- Member Functions
- Constructors (default, parameterized)
- Destructors
- `this` pointer
- Static members

**Hands-On:**

- Class `Student` with multiple constructors
- Use static data for count of created objects

---

### 🟢 **Day 5 – Inheritance & Polymorphism**

**Objectives:**

- Implement and explore inheritance
- Use virtual functions

**Topics:**

- Inheritance: single, multilevel
- Base and Derived class relationships
- Constructor invocation order
- Polymorphism basics
- Virtual functions
- Abstract classes (pure virtual functions)

**Hands-On:**

- Base class `Person`, derived class `Teacher`
- Virtual function example with base class pointer

---

### 🟢 **Day 6 – Operator Overloading & File I/O**

**Objectives:**

- Understand operator overloading
- Learn how to handle basic file operations

**Topics:**

- Operator Overloading: `+`, `==` as member functions
- Friend function for overloading
- File I/O: `fstream`, `ifstream`, `ofstream`
- Opening, writing, reading from text file

**Hands-On:**

- Overload `+` for a `Complex` number class
- Create a student record manager that writes/reads from file

---

### 🟢 **Day 7 – Templates & Exception Handling**

**Objectives:**

- Write reusable code with templates
- Handle errors with exceptions

**Topics:**

- Function Templates
- Class Templates (intro only)
- Try-Catch-Throw Exception Model
- Catching multiple exceptions
- `throw` and `rethrow`

**Hands-On:**

- Template for swapping two values
- Exception handling for division by zero

---

## ✏️ **Extras (as time permits or bonus handouts)**

- `new` / `delete` – dynamic memory basics
- STL Introduction: `vector`, `stack`, `map` (quick demo)
- Mini Project Suggestion: **Student Report Card Generator** or **Inventory Management**

---

## Certification Task

- Code Push: Raise Pull Request for the code till day 7 to [this repo](https://github.com/adhikareeprayush/CPP-ACES-2081-SUBMISSIONS.git)
- Format:
  - BCT: Raise PR in `BCT` folder, Rename your folder on your name For eg. `prayush`
  - BEI: Raise PR in `BEI` folder, Rename your folder on your name For eg. `prayush`
- Mini Project Submission:
  - Submit the mini project in the same repo by raising another PR.
  - Create `project` folder inside your folder and put the project there.

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/improvement`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add new feature'`)
5. Push to the branch (`git push origin feature/improvement`)
6. Create a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Prayush Adhikari**

- GitHub: [@adhikareeprayush](https://github.com/adhikareeprayush)

---

## ⭐ Show Your Support

If you found this bootcamp helpful, please consider giving it a star! ⭐

---

<p align="center">Made with ❤️ by ACES</p>
