# Hello World C++ Project

A simple C++ "Hello World" program demonstrating basic C++ syntax and project structure.

## Description

This project contains a basic C++ program that prints "Hello, World!" to the console. It's designed as a starting point for learning C++ programming.

## Files

- `main.cpp` - The main C++ source file containing the hello world program
- `CMakeLists.txt` - CMake configuration file for building the project
- `README.md` - This documentation file

## Requirements

- C++ compiler (GCC, Clang, or MSVC)
- CMake (version 3.10 or higher)

## Building and Running

### Using CMake

1. Create a build directory:
   ```bash
   mkdir build
   cd build
   ```

2. Generate build files:
   ```bash
   cmake ..
   ```

3. Compile the program:
   ```bash
   cmake --build .
   ```

4. Run the executable:
   ```bash
   ./hello-world  # On Linux/Mac
   hello-world.exe  # On Windows
   ```

### Direct Compilation

Alternatively, you can compile directly using a C++ compiler:

```bash
g++ main.cpp -o hello-world
./hello-world
```

## Output

When you run the program, you should see:
```
Hello, World!
Welcome to C++ Programming!
```

## Author

Created by hghxwy

## License

This project is open source and available under the MIT License.