# 🧑‍💻 Personal Data Collector

A beginner-friendly Python project that collects personal information from the user and displays:

✅ User Details  
✅ Data Types  
✅ Memory Addresses  
✅ Approximate Birth Year  

---

# 🚀 Features
- Interactive user input
- Uses `type()` and `id()`
- Birth year calculation
- Simple and easy to understand

---

# 🧠 Logic of the Program

1. The program asks the user to enter:
   - Name
   - Age
   - Height
   - Favourite Number

2. It stores the values in variables.

3. The program displays:
   - Entered value
   - Data type using `type()`
   - Memory address using `id()`

4. It calculates the approximate birth year using:

```python
birth_year = 2026 - age
```

5. Finally, it displays a thank-you message.

---

# ▶️ How to Run

```bash
python personal_data.py
```

---

# 💻 Code

```python
print("enter personal data")

name=input("enter your name:")
age=int(input("enter your age:"))
height=float(input("enter your height:"))
favourite_number=int(input("enter your favourite number:"))

print("here is the information we collected")

print("name:", name)
print("type:",type(name))
print("address:",id(name))

print("age:", age)
print("type:",type(age))
print("address:",id(age))

print("height:",height)
print("type:",type(height))
print("address:",id(height))

print("favourite_number:",favourite_number)
print("type:",type(favourite_number))
print("address:",id(favourite_number))

birth_year=2026-age

print("approx_birth year:",birth_year)
print("age:",age)

print("thank you for using our data, good bye!")
```

---

# 💻 Example Output

```text
enter personal data

enter your name:Sakshi
enter your age:18
enter your height:1.65
enter your favourite number:7

here is the information we collected

name: Sakshi
type: <class 'str'>
address: 140703847239568

age: 18
type: <class 'int'>
address: 9793632

height: 1.65
type: <class 'float'>
address: 140703847253232

favourite_number: 7
type: <class 'int'>
address: 9793312

approx_birth year: 2008
age: 18

thank you for using our data, good bye!
```

---

# 📚 Concepts Used
- Variables
- User Input
- Type Casting
- `type()` Function
- `id()` Function
- Arithmetic Operations

---

# 🌟 Author
Sakshi Patel

✨ Simple Python mini project for beginners.
