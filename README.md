# ccooker: JSON to C/C++ Code Generator

`ccooker` is a tool designed to automatically generate C or C++ code from JSON files. Its purpose is to streamline the process of incorporating JSON data structures into C or C++ applications by generating the necessary code to represent and manipulate these structures.

## Features

- Convert JSON objects to C structs or C++ classes.
- Handle nested and complex JSON structures.
- Support for generating both C and C++ compatible code.
- Customizable output for different coding standards and practices.

## Requirements

- C++20 compiler (e.g., GCC 10+, Clang 12+, MSVC 2019+)
- CMake 3.14 or higher
- Conan package manager

## Installation

### Clone the repository

```bash
git clone https://github.com/yourusername/ccooker.git
cd ccooker
```
###  Install dependencies using Conan
Create a build directory, configure dependencies, and install them:
```
mkdir build
cd build
conan install .. --build=missing
```
This will fetch catch2, spdlog, and nlohmann_json libraries as specified.
