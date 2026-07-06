Java Practice & Portfolio Exercises

A set of small Java programs covering core concepts from coursework, 
including algorithm logic, object-oriented design, and file handling.

Contents

### Portfolio 1 — Local Peaks
Counts "local peaks" in a list of temperatures (a value that is 
greater than both its neighbors), using a simple loop-based approach.

Portfolio 2 — Library Book System
Demonstrates inheritance and method overriding:
- `Book` — base class with title, copies available, and a `borrowBook()` method
- `RegularBook` — inherits default borrowing behavior
- `ReferenceBook` — overrides `borrowBook()` to block borrowing, since reference books can't leave the library

File I/O Practice
A series of standalone examples exploring Java's file handling:
- Reading files with `BufferedReader` and `Scanner`
- Writing to files with `PrintWriter` and `FileWriter`
- Checking file existence, creating, and deleting files with `File`
- Reading from one file, transforming each line, and writing the result to another file

Tech
- Java (core language, no external libraries)
- `java.io` and `java.util` packages
- Object-oriented principles: inheritance, method overriding
