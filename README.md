# PyPassword Generator 🔐

This project is a secure password generator developed during **Section 5** of the **"100 Days of Code™: The Complete Python Pro Bootcamp"** by **Angela Yu** on Udemy.

## 🎯 Project Objective
The goal was to create a program that generates strong, randomized passwords based on user preferences. It demonstrates the importance of randomization in cybersecurity.

## 🕹️ Features
* **Customizable Complexity:** Users can choose exactly how many letters, symbols, and numbers they want in their password.
* **High Entropy:** The program doesn't just pick random characters; it shuffles the entire final sequence to ensure there is no predictable pattern (e.g., all letters followed by all symbols).
* **Dynamic Generation:** Works with a wide range of characters, including uppercase, lowercase, numbers, and special symbols.

## 🛠️ Technical Implementation
* **Lists:** Storage of character sets for letters, numbers, and symbols.
* **`for` Loops & `range()`:** Used to iterate and select the specific number of characters requested by the user.
* **`random.choice()`:** To pick a random element from the character lists.
* **`random.shuffle()`:** A key step that reorders the list of characters to increase password strength.
* **Console Interactivity:** Using `input()` and formatted strings (`f-strings`) for a smooth user experience.

## 📋 How to Use
1. Run the script in your terminal.
2. Input the number of letters you desire.
3. Input the number of symbols you want to include.
4. Input the number of numeric digits.
5. The program will output a secure, randomized password.

---

**Course:** 100 Days of Code™: The Complete Python Pro Bootcamp  
**Instructor:** Angela Yu (Udemy)  
**Developed by:** Rusu Ioana
