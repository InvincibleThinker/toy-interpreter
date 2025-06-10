# 🐫 OCaml Lambda Calculus Interpreter

A minimal interpreter for a lambda calculus-inspired language, written in **OCaml**, featuring:

- First-class functions
- Closures with environment capture
- Function application
- Native interop for side effects

This project was built as part of my exploration of OCaml and functional programming.

---

## 🔧 Features

- 📦 **Custom Expression Types**: Variables, Abstractions, Applications
- 🧠 **Closures**: Functions capture their lexical environment
- 🔁 **Recursive Evaluation**: Supports function self-application
- 🧩 **Native Functions**: Integrates native OCaml functions for printing

---

## 🧠 Core Concepts Demonstrated

| Concept                | How It’s Used                           |
| ---------------------- | --------------------------------------- |
| First-Class Functions  | Functions as values using `Abstraction` |
| Closures               | `Closure` variant stores context        |
| Lexical Scoping        | Environments preserved in `Context.t`   |
| Higher-Order Functions | Function accepting/applying functions   |
| Native Interop         | Side-effecting `print_hello_world` hook |

---
