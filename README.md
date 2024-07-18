1.Clone the Repository:
git clone https://github.com/lightcode/8bit-computer.git
2.Understand the 8-bit CPU Architecture
Navigate to the rtl/ directory and focus on key files such as machine.v
3.Design a Simple High-Level Language (SimpleLang)
Variable declarations (var x: int;)
Assignments (x = 10;)
Arithmetic operations (y = x + 5;)
Conditionals (if (x > 0) { ... } else { ... })
4.Create a Lexer
Keywords: 'var', 'if', 'else'
Operators: '=', '+', '-', '*', '/'
Identifiers: 'x', 'y', 'result'
Literals: '10', 'true', 'false'
5.Develop a Parser
Generate Abstract Syntax Tree (AST):
Implement a parser to build an Abstract Syntax Tree (AST) from the tokens produced by the lexer.
Ensure the parser handles syntax errors gracefully and constructs a valid AST reflecting the structure of the SimpleLang code.
6. Generate Assembly Code
 Eg: use 'ADD' for addition
 7. Integrate and Test
Compile and Test:
Integrate the lexer, parser, and code generator into a single compiler program.
Compile SimpleLang programs to assembly code using your compiler.
Test the generated assembly code by running it on the 8-bit CPU simulator.
Verify that programs execute correctly and produce expected results
8. Documentation and Presentation
Document Design and Implementation:

Document the design choices, including the grammar, AST structure, and assembly code mappings.
Provide a clear explanation of how the compiler translates SimpleLang to assembly code for the 8-bit CPU.
Prepare Presentation:

Prepare a presentation to demonstrate the working of the compiler.
Include examples of SimpleLang programs, their corresponding assembly code, and their execution on the 8-bit CPU simulator.
Discuss challenges faced, optimizations made, and future improvements.
