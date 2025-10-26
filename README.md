# Python-to-C Translator (Lex & Yacc Project)

This project implements a simple compiler that translates a **Python-like** indentation-based language into **C** code using **Lex** and **Yacc**.

## 🧩 Features
- Supports variable assignments
- Supports `if`, `elif`, and `else` blocks
- Handles integers, floats, and strings
- Uses indentation (tabs) to detect code blocks (Python-style)
- Automatically declares variables with inferred types

## ⚙️ Usage
```bash
make
./translator example_input.txt
