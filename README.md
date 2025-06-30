# ⏱️ Time to Seconds Converter (C++)

This C++ program uses a class to take time input in hours, minutes, and seconds, and converts it into total seconds. It also displays the time in a formatted `hh:mm:ss` style.

---

## 💻 Language

C++

---

## 📋 Description

- Defines a `Time` class with private members: hours, minutes, seconds, and total seconds.
- Includes methods to:
  - Take input from the user
  - Convert time into total seconds
  - Display formatted time (`hh:mm:ss`) using `setw()` and `setfill()`

---

## 🧪 Sample Output

Enter time:

Hours? 1

Minutes? 30

Seconds? 15

The time is = 01:30:15

Time in total seconds: 5415

---

## 🛠️ How to Run

1. Save the file as `time_converter.cpp`

2. Compile using g++:
```bash
g++ time_converter.cpp -o time

3. Run the program:
./time

🌱 What I Learned

Creating and using classes in C++

Organizing logic into class methods

Using setw and setfill for neat formatting

Converting hh:mm:ss into total seconds
