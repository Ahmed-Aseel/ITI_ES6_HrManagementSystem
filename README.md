# 🧑‍💼 TypeScript HR Management System

A scalable Human Resources system built with **TypeScript OOP principles**. This project models real-world HR operations such as user authentication, employee management, salary validation, promotions, team hierarchies, and reporting — using clean, typed TypeScript code.

---

## 📦 Features

- ✅ Abstract `User` class with authentication and role support
- ✅ `Employee` and `Manager` subclasses with salary, promotion, and team logic
- ✅ `Department` class to manage employee groupings
- ✅ `HR` utility class for:
  - User ID generation
  - Email validation
  - Tax calculation
  - Reporting
- ✅ Proper use of:
  - `abstract classes`
  - `interfaces`
  - `enums`
  - `getters/setters`
  - `static methods`
  - `access modifiers`

---

## 🛠 Classes Overview

### `User` (Abstract)
- Common user properties and auth logic
- Enforces `getRole()` implementation

### `Employee` (extends `User`)
- Salary validation (`>= 3000`)
- Promotion support
- Salary after tax computation

### `Manager` (extends `Employee`)
- Manages a team of employees
- Provides team reporting

### `Department`
- Adds and tracks employees
- Calculates department size

### `HR` (Utility)
- `generateUserId()`
- `isEmailValid()`
- `calculateTax()`
- `generateReport()`