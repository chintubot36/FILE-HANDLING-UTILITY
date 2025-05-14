COMPANY : CODTECH IT SOLUTIONS

NAME :KUMBAM SAI KIRAN

INTERN ID : CT04DM738

DOMAIN : JAVA PROGRAMMING

DURATION : MAY 10th 2025 to JUNE 10th, 2025.

MENTOR : NEELA SANTOSH KUMAR


The **File Handling Utility** is a Java-based software project designed to perform a variety of file operations such as creating, reading, writing, updating, deleting, and searching files within a system. It is especially useful for managing textual data, maintaining logs, or organizing file systems. File handling is a fundamental part of any application that deals with data storage, and this utility provides a simplified, user-friendly interface for such operations.


### **Project Objective**

The main objective of the File Handling Utility is to allow users to efficiently manipulate files without needing deep technical knowledge of Java's I/O (Input/Output) libraries. This utility acts as a bridge between the user and the underlying file system, automating tasks that would otherwise require complex coding.

### **Core Features**

1. **Create Files**
   Users can create new files by specifying a file name and path. The utility checks for file existence to avoid overwriting unless explicitly allowed.

2. **Read Files**
   The utility can open and read the contents of a file line by line or in full, displaying the data on the console or a GUI.

3. **Write to Files**
   Users can input data that is then written to a specified file. It supports both overwriting and appending modes.

4. **Update File Content**
   This feature allows users to update specific content within the file, such as modifying a line or replacing a keyword.

5. **Delete Files**
   Files can be permanently removed from the system through the utility, with confirmation prompts to avoid accidental deletion.

6. **Search within Files**
   The tool can search for specific words or phrases within files, useful for log analysis or document scanning.

7. **File Metadata Retrieval**
   It can display file properties like size, creation date, last modified date, path, and file permissions.


### **Technologies Used**

This project is implemented using **Java**, leveraging several built-in libraries and technologies for efficient file operations:

1. **Java I/O Package (`java.io`)**

   * Core to this project, this package provides classes like `File`, `FileReader`, `FileWriter`, `BufferedReader`, `BufferedWriter`, etc.
   * Used for reading from and writing to files, checking file status, and manipulating file directories.

2. **Java NIO Package (`java.nio.file`)**

   * Introduced in Java 7, this package offers an alternative, modern file handling approach.
   * Classes like `Paths`, `Files`, and `StandardOpenOption` allow more efficient file operations with better exception handling.

3. **Exception Handling**

   * Robust exception handling using `try-catch-finally` blocks ensures that file-related errors (e.g., file not found, permission denied) are handled gracefully.

4. **Collections Framework**

   * In some implementations, lists or maps are used to store file data temporarily during read-modify-write operations.

5. **Java Swing or JavaFX (Optional)**

   * For a graphical version of the utility, Java Swing or JavaFX can be used to create a user interface.
   * Users can interact through buttons, text fields, and file choosers instead of using the command line.

6. **Logging API**
* The utility can include logging using `java.util.logging` to record user actions, errors, and system events for auditing and debugging.
* Simplifies the learning process for Java file handling.
* Automates repetitive tasks like reading or updating logs.
* Enhances productivity by providing a ready-to-use tool for developers and administrators.
* Encourages modular programming through clearly separated methods for each file operation.
