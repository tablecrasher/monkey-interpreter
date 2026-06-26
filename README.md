# Monkey Interpreter
A fully functional interpreter for the Monkey programming language, written in Go.

## Demo
https://github.com/user-attachments/assets/4909d89e-e96e-4222-8c1c-4069eb46f832

## Features
- Lexer, parser, AST, and tree-walking evaluator
- Data types: integers, strings, booleans, arrays, hashes
- First-class functions and closures
- Interactive REPL

## How It Works
Source code flows through four stages: the **lexer** converts raw text into
tokens, the **parser** consumes those tokens and builds an AST, and the
**evaluator** walks the AST to produce values represented as **objects**.
The object system also maintains an environment for variable bindings, enabling
closures. The **REPL** wires these stages together in a loop.
