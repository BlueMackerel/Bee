# Bee Programming Language Interpreter

## Overview
`bee` is an interpreter for the Bee programming language. It provides functionality to parse and execute user-defined scripts.

## Requirements
To run this interpreter, you need download this repo.

## Usage
Run a Bee script using the following command:

```sh
bee <filename>
```

Or start the REPL mode to enter commands interactively:

```sh
bee
```

## Features
- Custom language interpretation
- Support for string and numerical operations
- File input/output handling
- Basic error handling system

## Bee Language Syntax

### Comments(This is only valid in file code.)

```bee

# This is a Comment

#*

This is a Comment , too.
*#

```


### Variable Declaration
```bee
x = 10
name = "Bee"
```

### Operators
```bee
sum = 5 + 3
product = 4 * 2
```

### Conditional Statements
```bee
if x > 5 then
    ConsoleWrite("x is greater than 5.\n")
else then
    ConsoleWrite("x is 5 or less.")
end
```

### Loops
```bee
while x > 0 then
    ConsoleWrite(Format("{0}\n",[x]))
    x = x - 1
end
```

### Functions
```bee
fun add(a, b)
    return a + b
end

result = add(3, 4)
ConsoleWrite(Format("{0}\n",[result]))
```




## Contribution
To contribute to this project, follow these steps:
1. Fork this repository.
2. Create a new branch for modifications.
3. Commit and push your changes.
4. Submit a pull request (PR).

## License
This project is licensed under the MIT License.
