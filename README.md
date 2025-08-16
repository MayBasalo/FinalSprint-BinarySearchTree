FinalSprint-BinarySearchTree-DSA
Binary Search Tree Visualizer

Overview
This project is a web application that allows users to input a series of numbers, constructs a binary search tree (BST) from these numbers, and displays the tree structure in JSON format. Users can also view previously submitted trees and their corresponding input values. The application is built with Spring Boot and uses PostgreSQL for data storage.

Features
1. User Input Interface
Route: /enter-numbers

Description: Displays an HTML page with:

An input field for users to enter a series of numbers.

A Submit button to process the numbers.

A Show Previous button to view previously stored trees.

2. Processing Route
Route: /process-numbers

Description:

Accepts a list of numbers from the user.

Constructs a BST from the numbers.

Returns the BST as a JSON representation.

Stores both the input numbers and resulting tree structure in the PostgreSQL database.

3. Display Previous Trees
Route: /previous-trees

Description: Retrieves and displays previously submitted trees along with their corresponding input numbers from the database.

4. Testing
Includes unit tests to ensure the functionality of the application.

5. Database
Stores all input numbers and their resulting tree structures in a PostgreSQL database named finalsprintDSA_db.

