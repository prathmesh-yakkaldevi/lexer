# Lex Specification for Tokenizing Source Code

This Lex specification file defines patterns and tokens for tokenizing source code. It can be used in conjunction with a parser generator like Yacc to build a compiler or interpreter.

# Token Definitions
The Lex specification defines various patterns and associates them with corresponding tokens. Here are some of the tokens defined in this specification:<br>
* **Keywords**: auto, break, case, char, const, continue, default, do, double, else, enum, extern, float, for, goto, if, int, long, register, return, short, signed, sizeof, static, struct, switch, typedef, union, unsigned, void, volatile, while
* **Operators**: ==, !=, <=, >=, &&, ||, =, +, -, *, /, %, <, >, ++, --<br>
* **SPECIAL SYMBOL**: ,, ;, (, ), {, }<br>
* **Constants**: Integer constants, floating-point constants<br>
* **Identifiers**: User-defined identifiers<br>
