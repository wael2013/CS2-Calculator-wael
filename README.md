# CS2 Calculator Project

This project is a calculator application for CS2 class. 
It will implement basic arithmetic operations and potentially more advanced functions.

## Features
- Addition
- Subtraction
- Multiplication
- Division

Created by wael
## Build Instructions
### Using g++
g++ -o calculator test.cpp calculator.cpp calculator.exe
### Using CMake
mkdir build cd build cmake .. make calculator.exe
## Version Control Workflow
- The `main` branch contains stable code.
- The `feature-<name>` branches are used for development.
- All new features are merged into `main` after testing.