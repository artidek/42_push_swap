# 42 Push Swap

[![42 Network](https://img.shields.io/badge/42-Network-blue)](https://42.fr/)
[![License: 42 Educational](https://img.shields.io/badge/license-42%20Educational-blue.svg)](#license)

## Table of Contents

- [About the Project](#about-the-project)
- [Subject Overview](#subject-overview)
- [Project Requirements](#project-requirements)
- [Algorithm & Data Structures](#algorithm--data-structures)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

---

## About the Project

**Push Swap** is a sorting algorithm project designed for the 42 curriculum. The main goal is to sort a stack of integers using a limited set of stack operations, optimizing for the least number of moves. This project emphasizes algorithmic thinking, data structure manipulation, and performance optimization, crucial skills in software engineering and competitive programming.

---

## Subject Overview

The **Push Swap** project consists of two programs:

1. **checker**: Validates a sequence of stack operations to determine if they result in a sorted stack.
2. **push_swap**: Generates the optimal sequence of operations to sort a stack of integers, minimizing the operation count.

### Key Features

- Custom stack implementation
- Algorithm optimization for minimal operation count
- Error handling for invalid input, duplicates, and overflows
- Efficient memory management (no memory leaks)
- Performance-focused design

---

## Project Requirements

- **Input**: A list of integers as program arguments
- **Output**: A sequence of stack operations (sa, sb, pa, pb, ra, rb, rra, rrb, rr, rrr) to sort the stack
- **Constraints**:
  - Only allowed stack operations
  - No built-in sorting functions
  - Must handle edge cases (duplicates, empty input, invalid characters)
  - Fastest possible sorting for large data sets (up to 500 numbers)
- **Evaluation Criteria**:
  - Correctness of sorting
  - Efficiency (number of moves)
  - Code quality and documentation

---

## Algorithm & Data Structures

This project uses a **custom algorithm based on the weights of moves** to determine the most efficient sequence of stack operations. Every possible move is weighted and evaluated to ensure that the overall sorting process uses the minimal number of operations. The algorithm is designed specifically for this project and is highly optimized for effectiveness.

### Data Structures

To achieve high performance and effectiveness, various data structures were used, including:

- **Linked lists**: Used for stack representation, allowing dynamic and efficient manipulation of elements.
- **Custom-optimized structures**: Tailored for fast access and modification, ensuring minimal overhead during operation calculations.

All data structures were carefully chosen and tuned to maximize speed and efficiency throughout the sorting process.

---

## Usage

```bash
# Compile
make

# Run push_swap with a sequence of integers
./push_swap 3 2 1 6 5 8

# Output: A list of stack operations to sort the input

# Run checker to validate a sequence of operations
echo -e "pb\nra\nsa\npa" | ./checker 3 2 1 6 5 8
```

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/artidek/42_push_swap.git
   cd 42_push_swap
   ```
2. **Build the project**
   ```bash
   make
   ```

---

## Contributing

Contributions are welcome! Please open issues or submit pull requests for bugs, enhancements, or optimizations.

---

## License

This project is part of the 42 Curriculum and is provided for educational purposes only. **Please do not plagiarize.**

---

*Keywords: C, sorting algorithm, stack, data structure, push_swap, optimization, performance, custom algorithm, move weights, memory management, 42 school, competitive programming, checker, input validation, code quality, software engineering*
