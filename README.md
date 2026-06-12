<div align="center">

# 🩺 Fix My Code — The Code ER

**Five broken programs. Four languages. No documentation. One rule: minimal fixes only.**

*The Holberton debugging challenge — code walks in wounded, walks out working.*

[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=for-the-badge&logo=ruby&logoColor=white)](https://www.ruby-lang.org)
[![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)](https://en.wikipedia.org/wiki/C_(programming_language))
[![Holberton](https://img.shields.io/badge/Holberton-Challenge-E44D26?style=for-the-badge)](https://www.holbertonschool.com)

</div>

---

## 🧭 About this repository

The **Fix My Code Challenge** drops you into other people's code with zero
context and zero documentation — the code runs, but it's *wrong*, and your
job is to find the bug, fix it surgically, and touch nothing else.

The five patients:

| Patient | Language | The illness |
|---|---|---|
| `0-fizzbuzz.py` | Python | FizzBuzz with off-by-one logic |
| `1-print_square.js` | JavaScript | A square printer that doesn't square |
| `2-sort.rb` | Ruby | A sort that forgets to sort |
| `3-user.py` | Python | A User class validating nothing |
| `4-delete_dnodeint/` | C | Doubly-linked-list deletion — edge cases at head, tail and middle |

The C patient is the deep surgery: `delete_dnodeint_at_index` on a
doubly-linked list, where every fix is a pointer decision that either
heals the list or corrupts it. The `main.c` harness runs every delete
sequence; when it prints a clean list every time, the patient survives.

## 📚 The project

| Project | What it covers |
|---|---|
| [`challenge/`](challenge/README.md) | All five patients, admitted and treated — details inside |

## 🛠️ Environment

- Ubuntu 20.04 LTS · `python3`, `node`, `ruby`, `gcc`
- C compiled with `-Wall -Werror -Wextra -pedantic`

## 🚀 Triage

```bash
git clone https://github.com/Abdullayews/holbertonschool-Fix_My_Code_Challenge.git
cd holbertonschool-Fix_My_Code_Challenge/challenge
python3 0-fizzbuzz.py
gcc -Wall -Werror -Wextra -pedantic 4-delete_dnodeint/*.c -o dlist && ./dlist
```


## 👤 Author

**Muhəmməd Abdullayev** — Computer Engineering student · Qarabağ University & Holberton School

<p>
<a href="https://github.com/Abdullayews"><img src="https://img.shields.io/badge/GitHub-@Abdullayews-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
<a href="https://t.me/arasss08"><img src="https://img.shields.io/badge/Telegram-@arasss08-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="mailto:08abdullayevv@gmail.com"><img src="https://img.shields.io/badge/Email-08abdullayevv@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

> 🇦🇿 Part of my Holberton School journey — Foundations & Specializations, one repo at a time.

