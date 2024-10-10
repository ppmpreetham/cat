# CAT(WIP)
Cat is a simple, Lisp-like programming language written in python for cats to code.

## Key Features
- **Lisp-inspired Syntax:** CAT uses parentheses to group expressions and operators, similar to Lisp, making it ideal for recursive processing and simple expression parsing.
- **Customizable Operators:** CAT supports basic arithmetic, comparison, and logical operators, such as `+`, `-`, `*`, `/`, `and`, `or`, and more.
- **Control Structures:** Support for conditional statements like `if`, `then`, and `else`, allowing for flexible logic flows.
- **Custom Commands:** Introduces whimsical commands like `meow` for output, making coding more fun and engaging.
- **Simple Evaluation Model:** The language uses a recursive evaluation function to process and evaluate expressions.

## Syntax Overview
CAT expressions are enclosed in parentheses, where the first item is the function or operator, followed by the arguments.

### Example Expressions
```lisp
(meow "Hello, World!")
(+ 1 2)  # Addition
(* 3 4)  # Multiplication
(if (> 5 3) (meow "Yes") (meow "No"))
```
