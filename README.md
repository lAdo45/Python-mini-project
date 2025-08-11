# Python-mini-project

This repository contains three beginner-friendly Python projects developed for practice and skill-building. Each project focuses on basic Python concepts like conditionals, loops, functions, and random number generation.

1️⃣ Number Guessing Game 🎯

A simple interactive game where the computer randomly selects a number within a predefined range, and the player has to guess it.

How it works:

The program generates a random number (e.g., between 1 and 100).

The player inputs their guess.

The program gives hints — "Too High" or "Too Low" — until the correct number is guessed.

Tracks the number of attempts taken by the player.

Concepts used: random module, loops, conditionals, and user input handling.

Objective: Practice logic building and understand how to implement feedback loops in games.

2️⃣ Library Management System – Python Project
This Library Management System is a console-based Python application that helps manage the operations of a library efficiently. It uses Object-Oriented Programming (OOP) concepts such as classes, objects, and methods to simulate a real-world library environment.

The system is designed with two main classes:

1. Library Class
   
This class manages the core library functionalities, including maintaining a collection of books and handling book transactions.

Key Methods:

__init__ – Initializes the library with a predefined list of available books.

display_available_books() – Displays the list of books currently available in the library.

lend_book(book_name, student) – Allows a student to borrow a book if it is available. Removes the book from the available list and adds it to the student's borrowed list.

add_book(book_name) – Adds a new book to the library’s collection.

return_book(book_name, student) – Handles the return process by removing the book from the student's borrowed list and adding it back to the library.

2. Student Class
   
This class represents a student interacting with the library. Each student can borrow, return, and keep track of books they have taken.

Key Methods:

__init__ – Initializes the student with a name and an empty list of borrowed books.

borrow_book(book_name) – Requests a book from the library.

return_book(book_name) – Returns a borrowed book to the library.

3. Main Program Flow
   
The main part of the application provides a menu-driven interface for smooth user interaction.
It allows the user to:

View all available books

Borrow a book

Return a book

Add a new book to the library

Exit the program

The program continuously runs until the user chooses to exit, making it easy for library managers or students to perform multiple operations in one session.

Features of the Project:
✅ Simple and interactive command-line interface
✅ Demonstrates OOP principles in Python
✅ Supports adding and returning books dynamically
✅ Handles cases where books are unavailable
✅ Easily extendable for real-world applications

3️⃣ Rock-Paper-Scissors Game ✊📄✂️

A classic hand game simulation where the user competes against the computer.

How it works:

The player selects either Rock, Paper, or Scissors.

The computer randomly picks its move.

The winner is determined based on standard rules:

Rock beats Scissors

Scissors beats Paper

Paper beats Rock

If both choose the same, it’s a draw.

Concepts used: random module, conditional logic, and string comparisons.

Objective: Understand game logic implementation and decision-making in programs.
