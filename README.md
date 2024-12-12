# in-memory-database
Overview
This project implements an in-memory key-value database supporting transactional operations such as begin_transaction, put, get, commit, and rollback. It adheres to the specified interface and handles edge cases such as missing transactions.

How to Run
Clone the repository:
bash
Copy code
git clone <repository_url>
Navigate to the project directory:
bash
Copy code
cd <project_directory>
Run the code:
bash
Copy code
python inmemory_db.py

Write-up
To make this assignment an official coursework assignment:

Clarify that the get function works outside of a transaction and explain its behavior when keys are missing.
Add test cases that validate edge conditions.
Provide a sample grading rubric that emphasizes clean exception handling and proper transaction isolation.
Require integration tests to simulate a real-world application of the in-memory database.
