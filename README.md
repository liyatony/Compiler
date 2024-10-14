This repository contains several programs and documents related to compiler design using tools like LEX and YACC. It includes implementations for lexical analysis, parsing arithmetic expressions, and more.

Table of Contents
Features
Technologies
Installation
Usage
Contributing

Features
Lexical Analysis: Programs that count numbers, words, lines, and identify identifiers.
Parsing: YACC specifications for recognizing arithmetic expressions and identifiers.
Advanced Concepts: Programs for computing First and Follow sets, ε-closure of NFA, and implementing a calculator using LEX and YACC.

Technologies
Tools: LEX, YACC
Programming Language: C

Installation
Clone the repository:
git clone https://github.com/liyatony/Compiler.git
Navigate to the project directory:
cd Compiler
Ensure you have LEX and YACC installed.
Usage
Run any LEX or YACC file using:


lex file.l
yacc -d file.y
cc lex.yy.c y.tab.c -o output
./output


Contributing
Contributions are welcome! Please follow the standard process: fork, create a branch, make changes, and open a pull request.
