# Time to Seconds Converter (C++)

This C++ program uses a class to take time in hours, minutes, and seconds from the user and then converts it into total seconds. It also displays the formatted time (hh:mm:ss).

## Language
C++

## Description
- The program defines a `Time` class with private variables for hours, minutes, seconds, and total seconds.
- It includes methods to get time input, convert it into total seconds, and display both the original and converted time.

## Sample Output
Enter time:
Hours? 1
Minutes? 30
Seconds? 15
The time is = 01:30:15
Time in total seconds: 5415

## How to Run
1. Save the code in a file named `time_converter.cpp`
2. Compile and run:
```bash
g++ time_converter.cpp -o time
./time
What I Learned
Creating and using C++ classes

Separating logic into class methods

Using setw and setfill for pretty time formatting

Calculating time in seconds from hh:mm:ss
