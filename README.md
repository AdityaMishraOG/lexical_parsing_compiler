# Lexical Parsing Compiler
- A simple Python compiler for verifying adherence of user-entered strings to context-free grammar rules. 
- It uses the CYK Algorithm for parsing and validating the input string against a Context-Free Grammar (CFG) in Chomsky Normal Form (CNF).  

Note: One has the opportunity to experiment with a diverse range of grammars, allowing for extensive testing and analysis of different syntactic structures.

## Features
1. **Tokenization (Lexical Analysis):** The project involves implementing tokenization using Finite State Automata (FSAs) to recognize and classify tokens like identifiers, keywords, integers, floating-point numbers, and symbols. This is a foundational step in any compiler to break down the source code into meaningful units.    
2. **Syntactic Analysis:** It performs syntactic analysis based on provided grammar rules. This step checks the correctness of the program structure according to the specified grammar. It involves parsing the sequence of tokens to ensure they conform to the grammar rules (e.g., statements, conditions, operations).
3. **Error Handling:** The implementation handles detecting and reporting both lexical and syntactic errors. Error handling is a critical aspect of compiler construction to provide meaningful feedback when the source code does not meet language specifications or grammar rules.
4. **Output:** The compiler is expected to produce structured output that identifies each token type and its corresponding value. This output format helps in verifying the correctness of tokenization and parsing phases.

## Assumption
The program does not handle negative numbers in the input string.