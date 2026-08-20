# CS-300 Project Two

## Course Planner

This project was completed as part of CS-300 and demonstrates the use of data structures and algorithms in C++. The goal of the project was to develop a course planning application that can load course information from a file, organize the information using an appropriate data structure, display courses in alphanumeric order, and allow a user to search for individual courses and their prerequisites.

## 1. What was the problem you were solving in the projects for this course?

The main problem I was solving was determining how to efficiently store, organize, search, and display course information for an academic advising program. The application needed to read course data from an input file and store information such as the course number, course title, and prerequisites. It also needed to display the complete course list in alphanumeric order and allow a user to search for a specific course to view its information and prerequisites.

Throughout the course, I explored multiple data structures, including vectors, hash tables, and binary search trees. Comparing these structures helped me determine which one was best suited for the requirements of the course planner.

## 2. How did you approach the problem? Consider why data structures are important to understand.

I approached the project by first examining the requirements and comparing the advantages and disadvantages of the different data structures covered throughout the course. I considered how efficiently each structure could load data, search for courses, and display the entire course list in sorted order. This helped me understand that selecting the correct data structure can have a significant impact on a program's performance and organization.

For the final implementation, I used a binary search tree to organize the course information. Each course contains its course number, title, and prerequisite information. The program reads the input file, separates the values using commas, creates course objects, and inserts them into the binary search tree. An in-order traversal allows the program to display the courses in alphanumeric order, while the search functionality allows the user to locate an individual course and view its prerequisites.

## 3. How did you overcome any roadblocks you encountered while going through the activities or project?

One of the biggest challenges I encountered was correctly reading and parsing information from the input file. I had to make sure each line was separated properly and that the correct values were assigned to the course number, title, and prerequisites. Working through these issues required testing different approaches, reviewing my program logic, and debugging sections of the code individually.

I also experienced challenges with setting up and running C++ projects in Visual Studio, especially making sure that the necessary files were located in the correct project folders and that the program could successfully locate the input file. Troubleshooting these problems helped me become more comfortable reading compiler and runtime errors and identifying whether an issue was caused by the code itself or by the project configuration.

## 4. How has your work on this project expanded your approach to designing software and developing programs?

This project expanded my understanding of software development by showing me the importance of planning a program before beginning the final implementation. Writing pseudocode and analyzing vectors, hash tables, and binary search trees allowed me to think about how the program should organize and process information before writing the C++ code.

I also gained a better understanding of how algorithms and data structures work together. Instead of focusing only on making a program produce the correct output, I learned to consider efficiency, runtime, scalability, and how the organization of data affects different operations. These concepts will help me make better design decisions in future programming projects.

## 5. How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?

Working on this project reinforced the importance of writing organized and understandable code. Breaking the program into separate functions for loading data, inserting courses, searching for courses, and displaying course information made the application easier to understand and debug. Using descriptive variable and function names, consistent formatting, and comments also helped improve the readability of the program.

The project also showed me why adaptable code is important. Designing the application so that course information is loaded from an external file allows the data to be updated without rewriting the entire program. Going forward, I plan to continue using modular functions, clear naming conventions, comments, and appropriate data structures so that my programs are easier to maintain, troubleshoot, and expand.

## Skills Demonstrated

* C++ programming
* Binary search trees
* Vectors and hash tables
* Data structure analysis
* File input and parsing
* Searching and sorting
* In-order tree traversal
* Algorithm efficiency and runtime analysis
* Debugging and error handling
* Writing maintainable and readable code
