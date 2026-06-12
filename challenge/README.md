<div align="center">

# 🩺 The Challenge — five patients, five languages

**Broken code walks in; working code walks out. No context, no docs — just bugs.**

[![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)](https://python.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat-square&logo=ruby&logoColor=white)](https://www.ruby-lang.org)
[![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Holberton](https://img.shields.io/badge/Holberton-Challenge-E44D26?style=flat-square)](https://www.holbertonschool.com)

</div>

---

## 📖 About this project

The Fix My Code challenge drops you into *someone else's* code with zero
documentation and one instruction: make it work. Five programs, four
languages — Python, JavaScript, Ruby and C — each with a bug that hides
behind "it compiles" or "it runs".

The deepest surgery is `4-delete_dnodeint`: a C doubly-linked list whose
`delete_dnodeint_at_index` mishandles edge cases at the head, tail and
middle of the list. Classic pointer work — one fix that fixes everything,
or breaks everything.

## 🎯 Concepts covered

- Reading code before fixing it — no docs, no hints
- Python: FizzBuzz that isn't quite FizzBuzz
- JavaScript: printing squares that don't square
- Ruby: a sort that forgets to sort
- C: pointer surgery on doubly-linked lists
- Edge-case thinking: empty lists, index 0, single nodes

## 📂 Files

| File | What it does |
|---|---|
| [`0-fizzbuzz.py`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/0-fizzbuzz.py) | Python — FizzBuzz with off-by-one logic; the patient in bed 1 |
| [`1-print_square.js`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/1-print_square.js) | JavaScript — a square printer that draws the wrong shape |
| [`2-sort.rb`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/2-sort.rb) | Ruby — a sort implementation that doesn't quite sort |
| [`3-user.py`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/3-user.py) | Python — a User class with validation that validates nothing |
| [`4-delete_dnodeint/add_dnodeint_end.c`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/add_dnodeint_end.c) | C — appends a node at the tail |
| [`4-delete_dnodeint/delete_dnodeint_at_index.c`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/delete_dnodeint_at_index.c) | C — the star patient: deletion at index, edge cases and all |
| [`4-delete_dnodeint/free_dlistint.c`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/free_dlistint.c) | C — frees the whole list |
| [`4-delete_dnodeint/lists.h`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/lists.h) | C — the list type & prototypes |
| [`4-delete_dnodeint/main.c`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/main.c) | C — test harness exercising the deletes |
| [`4-delete_dnodeint/print_dlistint.c`](https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge/tree/main/challenge/4-delete_dnodeint/print_dlistint.c) | C — prints the list, node by node |

## ⚙️ Requirements

- 🐧 Ubuntu 20.04 LTS
- 📦 Interpreters for each language (python3, node, ruby, gcc)
- 🔒 Rule of the challenge: minimal fixes, no rewrites

## 🚀 Try it yourself

```bash
python3 0-fizzbuzz.py
node 1-print_square.js 4
gcc -Wall -Werror -Wextra -pedantic 4-delete_dnodeint/*.c -o dlist && ./dlist
```

---

✍️ **Muhəmməd Abdullayev** · [![GitHub](https://img.shields.io/badge/@Abdullayews-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Abdullayews) · one of the projects in **[holbertonschool-Fix_My_Code_Challenge](../README.md)**
