<div align="center">

<img src="assets/C.png" alt="C Programming Banner" width="100%" style="border-radius: 15px; box-shadow: 0 10px 30px rgba(0,0,0,0.2);"/>

<h1>⚡ C Programming — From Basics to Mastery</h1>

<p><b>Code • Logic • Implementation</b></p>

<p><i>Master C with deep understanding of logic, memory, and performance.</i></p>

<br/>

<p>
  <img src="https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/Compiler-GCC-A42E2B?style=for-the-badge&logo=gnu&logoColor=white"/>
  <img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-10b981?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Beginner-Friendly-6366f1?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Interview-Focused-f59e0b?style=for-the-badge"/>
</p>

</div>

---

## 🚀 Introduction

**C** is a general-purpose, procedural programming language developed by Dennis Ritchie at Bell Labs in 1972. It remains one of the most influential languages ever created — the foundation of operating systems, embedded systems, and modern programming languages.

**Why learn C?**

- It teaches you *how computers actually work* — memory, pointers, hardware interaction
- Every major language (Python, Java, C++, Rust) borrows concepts from C
- Essential for systems programming, OS development, and embedded engineering
- Sharpens your problem-solving and logical thinking like no other language

**Real-world importance:**

- Linux kernel, Windows NT, macOS core — all written in C
- Embedded systems, IoT devices, microcontrollers run C
- High-performance applications demand C-level control
- Competitive programming and interview prep rely heavily on C fundamentals

---

## 🎯 Learning Goals

| Goal | What You'll Achieve |
|------|---------------------|
| **Strong Fundamentals** | Variables, data types, operators, control flow — rock solid |
| **Memory Management** | Understand stack, heap, malloc, calloc, free — no leaks |
| **Problem Solving** | Build logic-first thinking with real coding challenges |
| **System-Level Understanding** | Pointers, file I/O, process memory — how it all connects |

---

## 📚 Complete Roadmap

| # | Module | Topics | Status |
|---|--------|--------|--------|
| 01 | **Basics** | Variables, Data Types, I/O, Operators | 🟢 Start Here |
| 02 | **Control Flow** | if/else, switch, ternary | 🟢 Core Logic |
| 03 | **Loops** | for, while, do-while, break, continue | 🟢 Iteration |
| 04 | **Functions** | Declaration, definition, scope, recursion | 🟡 Modular Code |
| 05 | **Arrays & Strings** | 1D/2D arrays, string functions, manipulation | 🟡 Data Handling |
| 06 | **Pointers** | Address, dereferencing, pointer arithmetic, double pointers | 🔴 Critical |
| 07 | **Structures** | struct, union, typedef, nested structs | 🟡 Custom Types |
| 08 | **File Handling** | fopen, fread, fwrite, fclose, modes | 🟡 Persistence |
| 09 | **Memory Allocation** | malloc, calloc, realloc, free, memory leaks | 🔴 Advanced |
| 10 | **Data Structures in C** | Linked List, Stack, Queue, Trees | 🔴 Mastery |

---

## 📂 Folder Structure

```
buildInC/
├── assets/
│   └── C.png
├── src/
│   ├── basics/
│   │   ├── hello_world.c
│   │   ├── variables.c
│   │   └── operators.c
│   ├── control-flow/
│   │   ├── if_else.c
│   │   └── switch_case.c
│   ├── loops/
│   │   ├── for_loop.c
│   │   ├── while_loop.c
│   │   └── patterns.c
│   ├── functions/
│   │   ├── basics.c
│   │   └── recursion.c
│   ├── arrays/
│   │   ├── 1d_array.c
│   │   └── 2d_array.c
│   ├── strings/
│   │   ├── string_basics.c
│   │   └── string_functions.c
│   ├── pointers/
│   │   ├── pointer_basics.c
│   │   ├── pointer_arithmetic.c
│   │   └── double_pointer.c
│   ├── structures/
│   │   ├── struct_basics.c
│   │   └── union.c
│   ├── file-handling/
│   │   ├── read_file.c
│   │   └── write_file.c
│   └── data-structures/
│       ├── linked_list.c
│       ├── stack.c
│       └── queue.c
└── README.md
```

---

## 💡 Concepts Covered

<table>
<tr>
<td width="50%">

**Core Concepts**
- 📌 Variables & Data Types (`int`, `float`, `char`, `double`)
- 📌 Operators (arithmetic, logical, bitwise, relational)
- 📌 Conditionals (`if`, `else if`, `switch`)
- 📌 Loops (`for`, `while`, `do-while`)
- 📌 Functions (parameters, return types, scope)
- 📌 Recursion (base case, call stack, backtracking)

</td>
<td width="50%">

**Advanced Concepts**
- 🔴 **Pointers** — the heart of C (address, deref, arithmetic)
- 🔴 **Memory Allocation** — `malloc`, `calloc`, `realloc`, `free`
- 📌 Structures & Unions (custom data types)
- 📌 File Handling (read, write, append, binary)
- 📌 Strings (char arrays, `string.h` functions)
- 📌 Data Structures (Linked List, Stack, Queue, Tree)

</td>
</tr>
</table>

> 🔴 **Pointers** deserve special attention — they are what separates a C beginner from a C programmer. Every pointer concept here is explained with diagrams, logic, and code.

---

## 🧠 Code + Logic Approach

Every concept in this repository follows a structured learning pattern:

```
📖 Concept Explanation  →  🧠 Logic Breakdown  →  💻 Code Implementation  →  ⚠️ Edge Cases  →  ✅ Best Practices
```

| Layer | What It Means |
|-------|---------------|
| **Logic Explanation** | Understand *why* before *how* — mental model first |
| **Code Implementation** | Clean, minimal, readable C code with inline comments |
| **Edge Cases** | What breaks the code? Null pointers, overflow, empty input |
| **Best Practices** | Memory safety, naming conventions, avoiding undefined behavior |

---

## ⚙️ Setup & Run Code

**Prerequisites:** GCC compiler installed on your system.

```bash
# Install GCC (macOS)
brew install gcc

# Install GCC (Ubuntu/Debian)
sudo apt install gcc

# Verify installation
gcc --version
```

**Compile and run any program:**

```bash
# Compile
gcc program.c -o program

# Run
./program

# Compile with warnings (recommended)
gcc -Wall -Wextra program.c -o program

# Compile with debugging info
gcc -g program.c -o program
```

**Example — Hello World:**

```c
#include <stdio.h>

int main() {
    printf("Hello, C World!\n");
    return 0;
}
```

```bash
gcc hello_world.c -o hello_world
./hello_world
# Output: Hello, C World!
```

---

## 📊 Progress Tracker

Track your learning journey — check off each topic as you complete it:

**Fundamentals**
- [ ] Hello World & Basic I/O
- [ ] Variables & Data Types
- [ ] Operators & Expressions
- [ ] Type Casting

**Control Flow**
- [ ] if / else if / else
- [ ] switch / case
- [ ] Ternary Operator

**Loops**
- [ ] for loop
- [ ] while loop
- [ ] do-while loop
- [ ] break & continue
- [ ] Nested loops & patterns

**Functions**
- [ ] Function declaration & definition
- [ ] Pass by value
- [ ] Recursion
- [ ] Scope & lifetime

**Arrays & Strings**
- [ ] 1D Arrays
- [ ] 2D Arrays
- [ ] String basics (char arrays)
- [ ] String functions (`strlen`, `strcpy`, `strcmp`)

**Pointers** 🔴
- [ ] Pointer basics & address-of operator
- [ ] Dereferencing
- [ ] Pointer arithmetic
- [ ] Pointers & arrays
- [ ] Double pointers
- [ ] Pointers to functions

**Memory Management** 🔴
- [ ] Stack vs Heap
- [ ] `malloc` & `calloc`
- [ ] `realloc`
- [ ] `free` & avoiding memory leaks

**Structures**
- [ ] `struct` basics
- [ ] Nested structures
- [ ] `union`
- [ ] `typedef`

**File Handling**
- [ ] `fopen` / `fclose`
- [ ] `fprintf` / `fscanf`
- [ ] `fread` / `fwrite`
- [ ] File modes (r, w, a, rb, wb)

**Data Structures in C** 🔴
- [ ] Singly Linked List
- [ ] Doubly Linked List
- [ ] Stack (array & linked list)
- [ ] Queue (array & linked list)
- [ ] Binary Search Tree

---

## 🏆 Why This Repo is Different

| Feature | This Repo |
|---------|-----------|
| **Logic-First** | Every concept starts with *why*, not just *how* |
| **Clean Code** | Minimal, readable, well-commented C programs |
| **Beginner Friendly** | No assumed knowledge — starts from absolute zero |
| **Interview Focused** | Covers patterns and problems asked in top tech interviews |
| **Edge Cases Covered** | Real-world pitfalls, not just happy-path examples |
| **Structured Roadmap** | Clear progression from basics to advanced — no confusion |

---

## 🤝 Contribution

Contributions are welcome! If you want to add examples, fix bugs, or improve explanations:

1. Fork the repository
2. Create a new branch — `git checkout -b feature/your-topic`
3. Add your code with proper comments and logic explanation
4. Commit — `git commit -m "Add: topic name"`
5. Push — `git push origin feature/your-topic`
6. Open a Pull Request

**Contribution Guidelines:**
- Follow the existing folder structure
- Every `.c` file should have a brief comment block explaining the concept
- Code must compile cleanly with `gcc -Wall`
- Keep it beginner-friendly — explain, don't just code

---

## 📄 License

This project is licensed under the **MIT License** — free to use, share, and modify.

---

<div align="center">

**⚡ Built for learners who want to understand C, not just write it.**

*From your first `printf` to dynamic memory and data structures — this is your complete C journey.*

<br/>

<img src="https://img.shields.io/badge/Language-C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
<img src="https://img.shields.io/badge/Made%20with-❤️%20%26%20Logic-ff6b6b?style=for-the-badge"/>
<img src="https://img.shields.io/badge/Open%20Source-MIT-10b981?style=for-the-badge"/>

</div>
