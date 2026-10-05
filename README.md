# C++ Expense Tracker — Console, Credit Tracking & Qt GUI

[![C++](https://img.shields.io/badge/C%2B%2B-Expense%20Tracker-00599C?logo=c%2B%2B&logoColor=white)](https://isocpp.org/)
[![Qt](https://img.shields.io/badge/Qt-GUI-41CD52?logo=qt&logoColor=white)](https://www.qt.io/)
[![Stars](https://img.shields.io/github/stars/AlakhiarovSalekh/Expense-Tracker-Project?style=social)](https://github.com/AlakhiarovSalekh/Expense-Tracker-Project/stargazers)

A C++ expense-tracking project that evolved through three implementations: a cash-only console tracker, a cash-and-credit tracker, and a Qt Widgets GUI.

## Versions

### Base Expense Tracker

Mainly in `src/` and `inc/`.

- Record expenses with automatic entry dates
- Store descriptions and values
- Delete the most recent entry
- Summarize expenses by entry, day, month, or year
- Save and load CSV data
- Console UI with input validation

### Cash & Credit Expense Tracker

Located in `update/`.

- Extends the expense model with credit information
- Tracks item value
- Tracks cash/down payment
- Tracks remaining credit balance
- Summarizes expenses, cash payments, and credit balances
- Demonstrates inheritance and polymorphism

### Qt GUI Version

Located in `qtgui/`.

A Qt Widgets front end built around the expense-tracker logic.

## Concepts Demonstrated

- C++ object-oriented programming
- Inheritance and polymorphism
- STL containers
- Operator overloading
- File I/O and CSV persistence
- Date-based filtering and summaries
- Console input validation
- Qt Widgets

## Repository Structure

```text
inc/      Headers for the base implementation
src/      Base console implementation
update/   Cash + credit implementation
qtgui/    Qt Widgets GUI implementation
```

## Build Notes

This repository contains historical implementations from different stages of the project. Some console artifacts were originally built with Cygwin, while the GUI version was developed with Qt Creator.

Expect small portability/build adjustments on a modern compiler or operating system.

## Contributing

Portability fixes, build cleanup, tests, documentation, and focused modernization work are welcome.

## More Projects by Salekh

- [C++ Projects](https://github.com/AlakhiarovSalekh/Cpp-Projects) — structured C++ learning and data structures.
- [Banking System C++ CLI](https://github.com/AlakhiarovSalekh/BANKING-SYSTEM-CPP-CLI) — terminal banking application.
- [Inventory Management Desktop App](https://github.com/AlakhiarovSalekh/Inventory-App) — Python/PyQt business desktop application.

## Author

**Salekh Alakhiarov** · [GitHub](https://github.com/AlakhiarovSalekh)
