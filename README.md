# Number Triangle Pattern in C++

A beginner-friendly C++ program that demonstrates pattern printing using nested loops.

This project generates a **Number Triangle Pattern**, where each row contains consecutive numbers starting from `1` up to the current row number.

---

## 📌 Features

* Prints a number triangle pattern
* Uses nested `for` loops
* Demonstrates dynamic loop boundaries
* Beginner-friendly implementation
* Helps understand pattern-based programming

---

## 🛠️ Technologies Used

* C++
* Standard Input/Output (`iostream`)

---

## 📂 Problem Statement

Given an integer `N`, print a triangle pattern where the `i-th` row contains numbers from `1` to `i`.

### Example

For:

```txt
N = 5
```

Output:

```txt
1
1 2
1 2 3
1 2 3 4
1 2 3 4 5
```

---

## 📸 Screenshot

<img width="1207" height="786" alt="Screenshot 2026-06-20 074556" src="https://github.com/user-attachments/assets/05828478-d13d-4f1c-9fd3-6e04025e78e7" />

Example folder structure:

```txt
project-folder/
│
├── main.cpp
├── README.md
└── screenshots/
    └── output.png
```

---

## 💻 Source Code

```cpp
void nTriangle(int n) {

    for(int i = 1; i <= n; i++) {

        for(int j = 1; j <= i; j++) {
            cout << j << " ";
        }

        cout << endl;
    }
}
```

---

## ▶️ How to Run

1. Compile the program:

```bash
g++ main.cpp -o main
```

2. Run the executable:

```bash
./main
```

3. Enter the value of `N`.

---

## 📸 Example Output

### Input

```txt
4
```

### Output

```txt
1
1 2
1 2 3
1 2 3 4
```

---

## 📖 Learning Concepts

This project helps beginners understand:

* Nested loops
* Pattern printing
* Number sequences
* Loop control statements
* Iteration logic
* Algorithmic thinking

---

## 🔍 Pattern Explanation

The outer loop controls the rows:

```cpp
for(int i = 1; i <= n; i++)
```

The inner loop prints numbers from `1` to the current row number:

```cpp
for(int j = 1; j <= i; j++)
```

As the row number increases, one additional number is printed, forming a triangle pattern.

---

## ⏱️ Complexity Analysis

### Time Complexity

```txt
O(N²)
```

### Space Complexity

```txt
O(1)
```

Only loop variables are used.

---

## 👨‍💻 Author

Developed as a beginner-friendly C++ practice project for learning nested loops, number patterns, and problem-solving techniques.
