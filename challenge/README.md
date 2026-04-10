# challenge

## Description

This project consists of debugging and fixing existing code written in multiple programming languages.

The objective is to analyze the provided source code, understand the expected behavior, identify the issues, and apply targeted fixes without rewriting the entire implementation.

It reflects real-world situations where developers need to work with existing codebases, legacy logic, or partially broken programs.

## Educational Context

This project was completed as part of the Holberton School curriculum.

It focuses on debugging methodology, code review, and minimal corrective changes across different languages and problem types.

## Project Tasks

### `0-fizzbuzz.py`
Fixes a Python implementation of FizzBuzz.

Issue addressed:
- incorrect handling of numbers divisible by both 3 and 5

Expected behavior:
- multiples of 3 → `Fizz`
- multiples of 5 → `Buzz`
- multiples of both 3 and 5 → `FizzBuzz`

---

### `1-print_square.js`
Fixes a JavaScript script intended to print a square of a given size.

Issue addressed:
- incorrect dimensions causing the output to exceed the expected square size

Expected behavior:
- print a square of exactly `size x size`

---

### `2-sort.rb`
Fixes a Ruby script intended to sort command-line arguments.

Issue addressed:
- incorrect ordering of the provided values

Expected behavior:
- sort arguments correctly

---

### `3-user.py`
Fixes a Python `User` class related to password validation.

Issue addressed:
- incorrect password verification logic

Expected behavior:
- `is_valid_password()` should return `True` only for the correct password

---

### `4-delete_dnodeint/`
Fixes a C implementation of deletion in a doubly linked list.

Files included:
- `add_dnodeint_end.c`
- `delete_dnodeint_at_index.c`
- `free_dlistint.c`
- `lists.h`
- `main.c`
- `print_dlistint.c`

Issue addressed:
- incorrect node deletion behavior causing invalid list output

Expected behavior:
- delete the node at the given index while preserving list integrity

## Languages Used

- Python
- JavaScript
- Ruby
- C

## Requirements

- All files are compiled or interpreted on **Ubuntu 20.04 LTS**
- Allowed editors: `vi`, `vim`, `emacs`
- All files must end with a new line
- A `README.md` file is required at the root of the project

## Debugging Approach

Each task follows the same general process:

1. run the provided code
2. compare the actual output with the expected output
3. inspect the source code
4. identify the root cause of the issue
5. apply the smallest possible fix
6. test the corrected version

## Learning Outcomes

Through this project, the following skills were practiced:

- reading and understanding unfamiliar code
- debugging across multiple languages
- identifying logical and structural issues
- applying precise fixes instead of rewriting code
- validating expected behavior through testing

## Real-World Relevance

This project simulates common engineering situations such as:

- fixing legacy code
- reviewing code written by others
- diagnosing incorrect output quickly
- working across different technologies

These are essential skills in software development, DevOps, and cybersecurity.

## Author

Pierre-Yves
