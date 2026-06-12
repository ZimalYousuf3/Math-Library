# 🔢 Math Library — C++ OOP 

A simple C++ math library built using **Object-Oriented Programming (OOP)** concepts like inheritance, function overloading, and operator overloading.

---

## 📁 Files

| File | Description |
|------|-------------|
| `mathlib.h` | Header file — contains `Number` and `Adv_Number` classes |
| `Math_Library.cpp` | Main file — demonstrates all features of the library |

---

## 🏗️ Class Structure

Number  (Base Class)
└── Adv_Number  (Derived Class — adds operator overloading)
└── Custom_Num  (User-defined class — extends Adv_Number)
---

## ✅ Features

### `Number` Class (Base)
- `add(y)` / `add(y, z)` — Addition with 1 or 2 values
- `subtract(y)` / `subtract(y, z)` — Subtraction
- `multiply(y)` / `multiply(y, z)` — Multiplication
- `divide(y)` / `divide(y, z)` — Division with divide-by-zero protection
- `get_val()` — Print and return the stored value

### `Adv_Number` Class (Derived)
- Operator overloading: `+`, `-`, `*`, `/`
- Unary operator: `++`
- Stream operators: `>>` (input) and `<<` (output)

---

## ▶️ How to Run

### Using g++ (Command Line)
```bash
g++ Math_Library.cpp -o mathlib
./mathlib
```

### Using Visual Studio / Dev-C++
1. Add both files to your project
2. Build and run `Math_Library.cpp`

---

## 💡 Concepts Used

- **Inheritance** — `Adv_Number` extends `Number`
- **Function Overloading** — Same function name, different parameters
- **Operator Overloading** — Custom behavior for `+`, `-`, `*`, `/`, `++`
- **Friend Functions** — For `>>` and `<<` stream operators
- **Encapsulation** — Data stored in `protected` variable `x`

---

## 🧪 Sample Output

Enter Value: 10
testing addition: 44
testing subtraction: -24
testing multiplication: 340
testing division:
Math Error
0
---

## 👩‍💻 Author

**Zimal Yousuf**  
BSCS Student | GitHub: [@ZimalYousuf3](https://github.com/ZimalYousuf3)
