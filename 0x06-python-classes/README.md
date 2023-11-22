# Project Title: Python - Classes and Objects

## Overview
In this project, I've delved into object-oriented programming using classes and objects in Python. The focus has been on understanding attributes, methods, properties, as well as concepts like data abstraction, data encapsulation, and information hiding.

## Project Structure

### Tests ✔️
- **tests:** This folder contains test files provided by Holberton School to validate the functionality of the implemented classes.

### Tasks 📃

#### 0. My first square
- **File:** `0-square.py`
- **Description:** Python class `Square` that defines a square.

#### 1. Square with size
- **File:** `1-square.py`
- **Description:** Python class `Square` that builds on `0-square.py` with a private instance attribute `size` and instantiation with size.

#### 2. Size validation
- **File:** `2-square.py`
- **Description:** Python class `Square` that builds on `1-square.py` with size validation:
  - Instantiation with optional size: `def __init__(self, size=0)`
  - Raises `TypeError` if size is not an integer.
  - Raises `ValueError` if size is less than 0.

#### 3. Area of a square
- **File:** `3-square.py`
- **Description:** Python class `Square` that builds on `2-square.py` with a public instance attribute `area` that returns the current square area.

#### 4. Access and update private attribute
- **File:** `4-square.py`
- **Description:** Python class `Square` that builds on `3-square.py` with properties to retrieve and set the private instance attribute `size`.

#### 5. Printing a square
- **File:** `5-square.py`
- **Description:** Python class `Square` that builds on `4-square.py` with a public instance method `my_print` that prints the square with the character `#` to standard output (prints an empty line if size == 0).

#### 6. Coordinates of a square
- **File:** `6-square.py`
- **Description:** Python class `Square` that builds on `5-square.py` with a private instance attribute `position` and properties to retrieve and set it.
  - Instantiation with optional size and position: `def __init__(self, size=0, position=(0, 0))`
  - Raises `TypeError` if position is not a tuple of two integers.

#### 7. Singly linked list
- **File:** `100-singly_linked_list.py`
- **Description:** Python classes `Node` and `SinglyLinkedList` that define a node of a singly-linked list and the list itself.
  - `Node` class:
    - Private instance attributes: `data` and `next_node`.
    - Instantiation with data and next_node.
    - Raises `TypeError` if data is not an integer or next_node is not a Node or None.
  - `SinglyLinkedList` class:
    - Private instance attribute: `head`.
    - Instantiation.
    - Public instance method `sorted_insert(value)` that inserts a new Node into the correct sorted position in the list (increasing order).

#### 8. Print Square instance
- **File:** `101-square.py`
- **Description:** Python class `Square` that builds on `6-square.py` with a `__str__` method to set printing of a Square instance equivalent to `my_print()`.

#### 9. Compare 2 squares
- **File:** `102-square.py`
- **Description:** Python class `Square` that builds on `101-square.py` with methods `__eq__`, `__ne__`, `__lt__`, `__le__`, `__gt__`, and `__ge__` to enable usage of Square instances with logical operators based on the square area.

#### 10. ByteCode -> Python #5
- **File:** `103-magic_class.py`
- **Description:** Python function matching exactly a bytecode provided.

## Usage
To test and use these classes, refer to the test files in the `tests` folder.

## Author
Wambui Gachora
