<div align="center">

# Codeforces Solutions

### A growing archive of competitive programming solutions

A personal collection of accepted solutions to problems from Codeforces, organized for easy lookup and written primarily in C++. The archive spans thousands of problems and continues to grow with ongoing practice.

![C++](https://img.shields.io/badge/Primary-C++17-00599C?logo=cplusplus&logoColor=white)
![Solutions](https://img.shields.io/badge/Solutions-5000%2B-brightgreen)
![Languages](https://img.shields.io/badge/Languages-16-blue)
![Platform](https://img.shields.io/badge/Platform-Codeforces-1F8ACB)
![License](https://img.shields.io/badge/License-MIT-yellow)

</div>

---

## Table of Contents

- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Naming Convention](#naming-convention)
- [Languages](#languages)
- [Building and Running](#building-and-running)
- [Educational Section](#educational-section)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

---

## Overview

This repository contains accepted solutions to programming problems from Codeforces. Solutions are grouped by problem identifier so a specific problem can be located quickly. The vast majority are written in C++ and submitted with the 32-bit GNU C++17 compiler, with a handful of solutions in other languages for variety and experimentation.

## Repository Structure

Solutions are bucketed by problem number. Top-level folders cover ranges of one hundred problems, and each contains subfolders that narrow the range further by tens.

```
project39/
├── 0000/ 0100/ 0200/ ... 2100/    Problem number buckets
│   └── 00/ 10/ 20/ ... 90/        Sub-buckets by tens
│       └── <problem><index>.<ext> Individual solutions
├── edu/                           Educational section solutions
├── LICENSE
└── README.md
```

For example, the solution to problem 100A lives at `0100/00/100a.cpp`, and problem 256C would live under `0200/50/256c.cpp`.

## Naming Convention

Each file is named by its problem number followed by the problem index within the round, using the file extension of the language it is written in.

| Example | Meaning |
| --- | --- |
| `100a.cpp` | Problem 100, index A, in C++ |
| `102b.cpp` | Problem 102, index B, in C++ |
| `100a.pike` | Problem 100, index A, in Pike |

## Languages

C++ is the primary language, complemented by solutions in a range of other languages.

| Language | Solutions |
| --- | --- |
| C++ | 4991 |
| Kotlin | 26 |
| Q# | 23 |
| Befunge | 8 |
| Pike | 7 |
| Roco | 7 |
| Tcl | 4 |
| Picat | 4 |
| Io | 4 |
| C | 2 |
| J, Factor, COBOL, FALSE, Ada | 1 each |

## Building and Running

Most solutions are single-file C++ programs that read from standard input and write to standard output. Compile and run any solution with a C++ compiler:

```bash
g++ -std=c++17 0100/00/101a.cpp -o solution
./solution
```

On Windows, run the generated `solution.exe`. Provide the problem input through standard input, either by typing it or piping a file.

## Educational Section

The `edu` directory holds solutions to problems from the Codeforces Educational section, organized into its own numbered subfolders following the same single-file, single-problem approach.

## Contributing

This is a personal practice archive, but suggestions and discussion are welcome. Feel free to open an issue to point out a cleaner approach or a bug in a specific solution.

## License

This project is released under the MIT License. See the LICENSE file for details.

## Author

Created by [Kumar44developer](https://github.com/Kumar44developer).
