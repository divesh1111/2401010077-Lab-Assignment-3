# 2401010077-Lab-Assignment-3
📘 Student Entry System (Java)

A Java console application demonstrating Custom Exceptions, Multithreading, Interfaces, and Robust Input Validation while collecting student details through user input.

🚀 Features ✔ Exception Handling

Custom exception: StudentNotFoundException

Handles:

Empty fields

Invalid numeric values

Invalid marks range

Unexpected input

✔ Multithreading

A separate thread (Loader) displays a loading animation using:

Thread t = new Thread(new Loader("Loading"));

✔ Interface Usage

RecordActions interface contains the method:

void addStudent() throws StudentNotFoundException;

✔ Strong Input Validation

Ensures name, email, and course cannot be empty
