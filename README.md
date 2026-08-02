# 🔍 Find Largest & Smallest Element in Array

> A clean and beginner-friendly C++ program that finds the largest and smallest elements in a user-defined integer array using separate comparison loops.

---

## 📋 Overview

This program demonstrates basic array traversal and comparison logic. It takes an array of integers as input, identifies the maximum and minimum values using independent loops, and displays both results.

---

## 🧮 Program Logic & Execution Flow

1. The user is prompted to enter the size of the array.
2. The user enters the array elements.
3. The program initializes `max = arr[0]`.
4. A `for` loop traverses the array to find the largest element:
   - If `max < arr[i]`, update `max = arr[i]`.
5. The program initializes `min = arr[0]`.
6. A `for` loop traverses the array to find the smallest element:
   - If `min > arr[i]`, update `min = arr[i]`.
7. The largest and smallest elements are displayed.

---

## 💻 Sample Input / Output

**Input:**
Enter the size of the array : 5
Enter the elements of the array : 10 25 3 18 7


**Output:**
Largest element : 25
Smallest element : 3


**Input:**
Enter the size of the array : 4
Enter the elements of the array : -5 0 12 -2


**Output:**
Largest element : 12
Smallest element : -5


---

## 🛠️ How to Compile and Run (Windows & Linux)

Follow the instructions below based on your operating system.

### 🪟 For Windows Users (Using MinGW/G++ or any C++ compiler)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ find_min_max.cpp -o find_min_max.exe` |
| **2. Run** | `find_min_max.exe` |

> **Note:** If `g++` is not recognized, make sure MinGW is installed and added to your System PATH.

---

### 🐧 For Linux / macOS Users (Terminal)
| Step | Command |
| :---: | :--- |
| **1. Compile** | `g++ find_min_max.cpp -o find_min_max` |
| **2. Run** | `./find_min_max` |

> **Prerequisite:** Ensure GCC/G++ is installed on your system. (On Linux: `sudo apt install g++` | On macOS: `xcode-select --install`)

---

## 📂 Project Structure
cpp-find-largest-smallest-array/
│
├── find_min_max.cpp # Main source code file
└── README.md # Project documentation (this file)


---

## 👩‍💻 Author

**Iqra Maqsood Mughal**  
*C++ Developer | Programming Enthusiast*

---

## 📅 Date

**August 2, 2026**

---

## 📄 License

This project is open-source and intended for educational purposes.
