# ⚙️ C Classical Algorithms Console Application

A single-file, menu-driven C program that serves as a practical implementation toolkit for several classical algorithms and number theory problems. This project demonstrates modular programming, efficient algorithm design, and robust user input handling in a console environment.

## ✨ Technical and Algorithmic Concepts Demonstrated

* **Modular Design:** Utilizes clear function prototypes and implementation (`mainMenu`, `firstQuest`, `isPrime`, etc.) to create a clean, organized, and maintainable structure.
* **Classical Algorithms:** Efficient implementation of foundational CS problems:
    * **Fibonacci Sequence:** Iterative approach using `unsigned long long int` to handle large numbers.
    * **Prime Number Check:** Optimized check using a loop up to $\sqrt{n}$ for efficiency.
* **Input Handling:** Robust validation of user input, including checking for integers vs. floats and ensuring inputs meet minimum required values.
* **Number Theory:** Implementation logic for defining and identifying  Perfect Numbers (where the sum of proper positive divisors equals the number).
* **Recursion/Iteration:** Implementation of **FizzBuzz** and other patterns using loops and conditional logic.

---

## 📁 Application Structure

The program is broken down into a main menu and five distinct quests (functions), each focused on a specific problem:

| Quest | Algorithm/Concept | Output |
| :--- | :--- | :--- |
| **1. Hidden Code** | FizzBuzz | Prints a sequence modified by multiples of 3 and 5. |
| **2. Numeric Mayhem** | Fibonacci Sequence | Prints the first *n* numbers in the sequence. |
| **3. Maze System** | Prime Summation | Calculates the sum of all prime numbers $\leq n$. |
| **4. Sorcery** | Perfect Numbers | Checks if an input number is a Perfect Number. |

## 🚀 How to Compile and Run

This project requires a standard C compiler (like GCC or Clang).

1.  **Compile the file:**
    ```bash
    gcc -o algotool ex_2.c -lm 
    # The -lm flag is required for the math.h dependency (pow function).
    ```
2.  **Execute the program:**
    ```bash
    ./algotool
    ```
    *The program will launch the main menu, allowing the user to select and run each quest.*
