# Python Calculator V1  
*(English version below)*
---

![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

## 🧭 Contents
- [🇷🇺 Русская версия](#-русская-версия)
- [Описание](#описание)
- [Возможности](#возможности)
- [Пример работы](#пример-работы)
- [Запуск](#запуск)
- [Цель проекта](#цель-проекта)
- [🇬🇧 English version](#-english-version)
- [Description](#description)
- [Features](#features)
- [Example](#example)
- [Files](#files)
- [Run](#run)
- [Project goal](#project-goal)

  
## 🇷🇺 Русская версия

### Описание
Учебный мини-проект на Python: простой интерактивный калькулятор, поддерживающий операции  
`+`, `-`, `*`, `/` и красивое форматирование больших чисел (тонкие пробелы, удаление хвостовых нулей).

Калькулятор работает в цикле.  
Пустой ввод на любом шаге — завершение программы.


## Возможности

- операции: `+`, `-`, `*`, `/`
- корректная обработка ошибок:
  - пустой ввод
  - неверный оператор
  - деление на ноль
- красивый вывод:
  - тонкие пробелы между разрядами (например: `1 234 567`)
  - автоматическое удаление хвостовых нулей (`5.50000 → 5.5`)
  - отображение целых чисел без дроби


### Пример работы
```bash
Простой калькулятор (+ - * /). Пустой ввод на любом шаге — выход.

a:  4.5
op: +
b:  1
=  5.5

a:  1000000
op: +
b:  2500000
=  3 500 000
```

### Файлы
- calculator.py — основная программа
- README.md — описание проекта


## Запуск

```bash
python calculator.py
```

Или открыть файл в Jupyter Notebook.

### Цель проекта
Отработать:
- input()
- циклы while
- условия if/elif/else
- обработку ошибок без try/except
- форматирование строк через f-строки и rstrip()

---

## 🇬🇧 English Version

###  Description
This is an educational mini-project: an interactive Python calculator supporting
+, -, *, / and clean formatted numeric output.

The calculator runs in a loop.
Empty input at any step — the program exits.


### Features:
| Feature | Description |
|--------|-------------|
| Operations | `+`, `-`, `*`, `/` |
| Error handling | Empty input, invalid operator, division by zero |
| Formatting | Thin spaces, trimmed zeros, pretty integers |

### Example:

```bash
Simple calculator (+ - * /). Empty input — exit.
a:  4.5
op:  +
b:  1
=  5.5

a:  1000000
op: +
b:  2500000
=  3 500 000
```


### Files
- calculator.py — main program
- README.md — documentation

### Run

```bash
python calculator.py
```
Or open the notebook file.


### Project goal
- Practice:
  - input()
  - loops (while)
  - conditions (if/elif/else)
  - basic error handling
  - f-string formatting
