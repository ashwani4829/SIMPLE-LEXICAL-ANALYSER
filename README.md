# Lexical Analyzer in C

**Author:** Ashwani Dwivedi
**Intern ID:** CT04DG1794
**Company:** CODTECH IT SOLUTIONS
**Mentor:** Neela Santosh
**Domain:** C Programming
**Duration:** 4 Weeks

---

## Overview

A simple lexical analyzer in C that reads a source code file and breaks it into tokens: keywords, identifiers, operators, and numbers. Logic is implemented manually using standard C functions.

---

## Features

* Detects keywords, identifiers, numbers, operators
* Handles multi-character tokens
* Ignores whitespace and newlines
* Uses `ungetc()` for proper token parsing

---

## Technologies Used

* C Language
* `stdio.h`, `stdlib.h`, `string.h`, `ctype.h`

---

## File Structure

```
lexical_analyzer.c   # Main program  
input.c              # Sample input file  
README.md            # Documentation  
```

---

## Compile & Run

```bash
gcc lexical_analyzer.c -o lexer
./lexer
```

Enter the input file name when prompted (e.g., `input.c`).

---

## Key Learnings

* Tokenization and classification logic
* File I/O and character-level scanning
* Fundamentals of compiler front-end design
