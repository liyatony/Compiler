# Compiler

This repository contains several programs and documents related to compiler design using tools like **LEX** and **YACC**. It includes implementations for lexical analysis, parsing arithmetic expressions, and more.

## Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)


## Features
- **Lexical Analysis**: Programs that count numbers, words, lines, and identify identifiers.
- **Parsing**: YACC specifications for recognizing arithmetic expressions and identifiers.
- **Advanced Concepts**: Programs for computing First and Follow sets, ε-closure of NFA, and implementing a calculator using LEX and YACC.

## Technologies
- **Tools**: LEX, YACC
- **Programming Language**: C

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/liyatony/Compiler.git
2. Navigate to the project directory:
   ```bash
   cd Compiler
3.Ensure you have LEX and YACC installed.
## Usage
To run any LEX or YACC file:
lex file.l
yacc -d file.y
cc lex.yy.c y.tab.c -o output
./output

## Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit (git commit -m "Description of changes").
Push the changes (git push origin feature-branch).
Open a pull request.
