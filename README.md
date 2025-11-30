🔍 Lexical Analyzer in C
A simple and efficient lexical analyzer written in C. It reads a source code file and breaks it into meaningful tokens such as keywords, identifiers, operators, numbers, and symbols.
⭐ Features

Detects keywords, identifiers, operators, numbers, symbols

Ignores whitespace and comments

Displays tokens in a clean readable format

Easy-to-understand C implementation
Input
int a = 10;
float b = a + 5;
output
Keyword      : int
Identifier   : a
Operator     : =
Number       : 10
Symbol       : ;
Keyword      : float
Identifier   : b
Operator     : =
Identifier   : a
Operator     : +
Number       : 5
Symbol       : ;

/lexical
 ├── main.c
 ├── lexer.c
 ├── lexer.h
 ├── sample.txt
 └── README.md
🧠 Concepts Demonstrated

Lexical analysis

Token classification

Finite state logic

File handling in C

Basic compiler front-end design
