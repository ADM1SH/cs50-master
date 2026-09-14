# CS50 Master Curriculum Collection

[![Course: CS50x](https://img.shields.io/badge/Course-CS50x_Computer_Science-red.svg)](https://cs50.harvard.edu/x/)
[![Course: CS50P](https://img.shields.io/badge/Course-CS50P_Python-blue.svg)](https://cs50.harvard.edu/python/)
[![Course: CS50W](https://img.shields.io/badge/Course-CS50W_Web_Programming-green.svg)](https://cs50.harvard.edu/web/)
[![Languages](https://img.shields.io/badge/Languages-C%20%7C%20Python%20%7C%20SQL%20%7C%20JS-orange.svg)](https://github.com/ADM1SH/cs50-master)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

A comprehensive master archive encompassing all completed projects, problem sets, and capstones across the three Harvard CS50 certificates: CS50x, CS50P, and CS50W.

## Description
This master repository organizes an extensive progression through computer science, from low-level C memory pointers and assembly architecture to object-oriented Python scripting and full-stack dynamic web applications with Django and modern JavaScript.

### Tracks Included
1. **Introduction to Computer Science (CS50x)**:
   * Low-level programming in C11: memory allocation (`malloc`, `free`), pointers, arrays, data structures (linked lists, hash tables, tries).
   * Algorithms: asymptotic efficiency, recursion, sorting algorithms (Bubble, Selection, Merge).
   * Relational databases: SQL queries, normalization, SQLite integration.
2. **Introduction to Programming with Python (CS50P)**:
   * Idiomatic Python 3: functions, loops, regex, exceptions, unit testing with `pytest`, object-oriented design (`@property`, inheritance, operator overloading).
3. **Web Programming with Python and JavaScript (CS50W)**:
   * Dynamic full-stack web applications using Python, Django, SQLite/PostgreSQL, JavaScript (ES6+), HTML5, and CSS3.
   * RESTful APIs, asynchronous AJAX/Fetch requests, user authentication, sessions, and responsive single-page applications.

## Directory Structure
```text
cs50-master/
├── Introduction_To_Computer_Science/           # CS50x problem sets, labs, and C/Python/SQL projects
├── Introduction_To_Programming_with_Python/    # CS50P modular Python problem sets and test suites
├── Web_Programming_With_Python_And_JavaScript/ # CS50W Django applications, frontend JS, and APIs
└── README.md                                   # Master collection documentation
```

## Requirements
* C: `clang` or `gcc` (C11 standard)
* Python: version 3.10 or higher
* Database: SQLite3
* Web Framework: Django 4.0+
* Package Manager: `pip`

## Installation & Setup
Clone the master repository:
```bash
git clone https://github.com/ADM1SH/cs50-master.git
cd cs50-master
```

To run a Django web project from CS50W:
```bash
cd Web_Programming_With_Python_And_JavaScript/<project_directory>
pip install -r requirements.txt
python3 manage.py migrate
python3 manage.py runserver
```

## Usage
* Run C problem sets:
  ```bash
  cd Introduction_To_Computer_Science/Week1
  clang -O2 -Wall -o hello hello.c
  ./hello
  ```
* Run Python problem sets:
  ```bash
  cd Introduction_To_Programming_with_Python/Week0
  python3 hello.py
  ```
* Run automated tests with pytest:
  ```bash
  pytest
  ```

## Support
Open an issue on the repository issue tracker:
https://github.com/ADM1SH/cs50-master/issues

## Roadmap
* [x] Complete CS50x curriculum and certificate requirements.
* [x] Complete CS50P Python curriculum with unit tests.
* [x] Complete CS50W full-stack Django projects.
* [x] Archive and cross-index all problem sets and solutions.

## Contributing
1. Fork the repository.
2. Create a branch: `git checkout -b feature/additional-test-cases`.
3. Ensure code conforms to PEP 8 for Python and C11 standards for C.
4. Submit a Pull Request.

## Authors and Acknowledgment
* **Adam Anwar** (ADM1SH) - Student author and developer.
* **David J. Malan, Brian Yu, and Harvard CS50 Staff** - Curriculum creators.

## License
MIT License. See `LICENSE` for details.

## Project Status
Completed master academic archive. Maintained as a comprehensive reference across foundational and full-stack software development.
