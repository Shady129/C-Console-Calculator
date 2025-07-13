# 🧮 C# Console Calculator

A **simple C# console application** demonstrating **Object-Oriented Programming (OOP)** concepts by building a calculator that:

✅ Adds  
✅ Subtracts  
✅ Multiplies  
✅ Divides (with zero-checking)  
✅ Clears/Resets

It displays the **current operation, the number used, and the result** after each operation in the console.

---

## ✨ Features

- **Encapsulation:** Uses private fields (`_Result`, `_LastNumber`, `_LastOperation`) for clean data management.
- **Formatted Output:** Uses `Console.WriteLine` with placeholders for clear output.
- **Safe Division:** Handles division by zero without crashing.
- **Beginner-Friendly:** Helps learn classes, methods, and state management in C#.

---

## 🚀 How It Works

1️⃣ Create a `clsCalculator` object:
```csharp
clsCalculator calculator = new clsCalculator();
