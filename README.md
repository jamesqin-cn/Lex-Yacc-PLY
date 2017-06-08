# Lex, Yacc, PLY

Examples on how to construct compilers using lex, yacc and Pyhon Lex-Yacc

* [ex1](src/ex1/) - a very simple calculator with support for addition, subtraction, multiplying, division and exponentiation, it also understands parentheses, order of operations and can work with basic alphanumeric variables

* [calc3](src/calc3/) - includes loops support (simple _WHILE_ without control statements) and simple conditionals, has 3 variations:
    * [interpreter](src/calc3/calc3a.c)
    * [compiler](src/calc3/calc3b.c) (to abstract ASM)
    * [grapher](src/calc3/calc3g.c) which builds a syntax tree

* [lex_example.py](src/jfk/main.py) - simple python expressions interpreter using Python Lex-Yacc

[Dokumentacja projektu](docs/dokumentacja.md)
