# K# Programming Language

Welcome to the K# programming language repository! This project contains the grammar rules and project setup for K#, a new programming language designed to be easy to learn and efficient for various programming tasks.

## Table of Contents

- [Introduction](#introduction)
- [Grammar Rules](#grammar-rules)
- [Project Setup](#project-setup)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

K# is a programming language that aims to combine simplicity and efficiency. It is designed for both beginner and advanced programmers, offering a clear and concise syntax. This repository contains the essential files needed to understand and work with K#.

## Grammar Rules

The `PLD Rule.grm` file defines the syntax rules for K#. Here are the main components:

- **Start Symbol**: `<program>`
- **Terminals**: Identifiers (`id`) and digits (`digit`)
- **Non-Terminals**: Program structure, statements, expressions, conditions, loops, function definitions, and more.

### Example Rules

- **Program**: A K# program starts with `Start` and ends with `End`.
- **Statements**: Includes assignments, if statements, for loops, while loops, function definitions, function calls, and I/O statements.
- **Expressions**: Supports arithmetic operations and nested expressions.

## Project Setup

The `WindowsFormsApp4.csproj` file sets up the build environment for compiling K# programs using Visual Studio. It includes:

- References to necessary libraries (`CalithaLib.dll` and `GoldParserEngine.dll`)
- Build configurations for Debug and Release modes
- Source files and resources required for the project

## Getting Started

To get started with K#, follow these steps:

1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/ksharp.git
   cd ksharp

2.Open the Project:

3.Open WindowsFormsApp4.sln in Visual Studio.
Build the Project:

4.Compile the project to generate the necessary executables.




5. **Writing a K# Program**:
   ```sh
   Start
     int x = 10;
     int y = 20;
     int sum = x + y;
     if (sum > 20) {
       print("Sum is greater than 20");
     } else {
       print("Sum is 20 or less");
     }
   End
   





