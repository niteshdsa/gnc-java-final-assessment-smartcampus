Assessment Name:   SmartCampus System

Author:     Nitesh Kumar

This project is a Java-based Smart Campus Management System developed as part of the final assessment.
It allows an admin to manage students, courses, and enrollments efficiently using core Java concepts.

Features

. Add Student
. Add Course
. Enroll Student in Courses
. View All Students
. View Enrollments
. Process Enrollment using Multithreading
. Search Student (Unique Feature 🔍)
. Exception Handling for invalid inputs

ADMIN
As an Admin, I can:

. Add and manage students
. Add and manage courses
. Enroll students in multiple courses
. View student and enrollment details

SYSTEM;
The system:

. Handles invalid inputs using exception handling
. Uses multithreading to process enrollments asynchronously

Technologies Used:

. Java
. OOP Concepts (Classes, Objects, Constructors)
. Collections (HashMap, ArrayList)
. Exception Handling
. Multithreading

Concepts Implemented:

. Encapsulation using classes
. Use of HashMap for fast data retrieval
. Custom Exception (InvalidFeeException)
. Thread class for asynchronous processing
. Menu-driven program using Scanner

Output:
Sample Run;

===== Smart Campus Menu =====

. Add Student
. Add Course
. Enroll Student
. View Students
. View Enrollments
. Process Enrollment (Thread)
. Search Student
. Exit

Output Screenshots already uploaded in the file section.

QUES 1. A developer is implementing student enrollments where each student can enroll in multiple courses. The system should allow quick lookup of a student and their enrolled courses. Which is the most optimal data structure?

ANSWER...B. HashMap<Student, ArrayList>

QUES 2. During enrollment, a student enters a negative course fee, causing incorrect processing. The developer wants to ensure invalid data is handled properly. What is the best approach?

ANSWER...C. Throw a custom exception like InvalidFeeException

QUES 3. The system simulates enrollment processing using a thread. However, multiple threads are accessing the same enrollment list, causing inconsistent results. What should be done?

ANSWER...B. Use synchronized block or thread-safe collection

QUES 4. A developer wants to enforce a rule that every type of course must implement a method calculateFee() but allow different implementations. Which concept should be used?

ANSWER..B. Interface
