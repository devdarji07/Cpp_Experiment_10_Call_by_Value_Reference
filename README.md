# Function Calling Methods in C++

## 🎯 Aim
To study and implement different ways of calling functions in C++:
- Call by Value
- Call by Reference (using pointers)
- Pass by Reference (using references in C++)

---

## 📌 Objectives
- To understand how data is transferred between functions.  
- To differentiate between call by value, call by reference, and pass by reference.  
- To observe how changes inside a function affect or do not affect actual variables.  
- To develop a clear idea about memory management during function calls.  

---

## 📖 Theory
In programming, functions allow us to divide a large program into smaller, manageable blocks.  
When data is passed to a function, there are different ways in which it can be handled.  

### 🔹 Call by Value
- Copy of the actual parameter is passed.  
- Changes inside the function do **not** affect the original variable.  
- Example: swapping two numbers does not change the real values.  

### 🔹 Call by Reference (Pointers)
- Address of the variable is passed.  
- Function can directly modify original variables.  
- Requires careful pointer handling.  

### 🔹 Pass by Reference (References)
- Reference variable (alias) of actual variable is passed.  
- Safer and simpler than pointers.  
- Any change reflects directly on original variable.  

---

## 📊 Comparison Table

| Method             | What is Passed? | Changes Affect Original? | Memory Used | Ease of Use |
|--------------------|-----------------|--------------------------|-------------|-------------|
| Call by Value      | Copy of value   | ❌ No                    | More        | Very Safe   |
| Call by Reference  | Address         | ✅ Yes                   | Less        | Needs pointer care |
| Pass by Reference  | Reference       | ✅ Yes                   | Less        | Simple & Efficient |

---
