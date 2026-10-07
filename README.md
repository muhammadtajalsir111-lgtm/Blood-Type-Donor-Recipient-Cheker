# 🩸 Blood Type Donor & Recipient Checker

A beginner-friendly Python terminal program designed to provide instant blood compatibility guidance. This tool helps users determine exactly who they can donate to and who they can receive blood from, based on standard medical compatibility rules.

---

## 📌 About the Project

This project was built as a hands-on exercise to apply core Python fundamentals in a practical, real-world scenario. It demonstrates the use of:

- User input handling (`input`)
- Conditional logic (`if / elif / else`)
- Functions (`def`)
- Clean, readable code structure

The goal is simple: make blood compatibility information accessible to anyone, instantly.

---

## ✨ Key Features

- **Donation Path:** If you want to donate, simply enter your blood type, and the program instantly lists all compatible recipient types.
- **Receiving Path:** If you need to receive blood, input your blood type to see a list of all safe donor types.
- **User-Friendly Input:** Asks clear questions (yes / no) to guide you through the correct medical scenario.
- **Comprehensive Compatibility:** Covers all major blood groups, including both positive (+) and negative (-) Rh factors.
- **Input Validation:** Handles invalid entries gracefully, ensuring the program never crashes.

---

## 🧠 How It Works

The program utilizes a `types_of_blood()` function and conditional logic (`if`, `elif`, `else`) to map your specific blood type to standard medical compatibility rules.

- **Donor logic:** Determines which blood types can safely receive your blood (e.g., O- can donate to all types).
- **Recipient logic:** Determines which blood types are safe to receive from (e.g., AB+ can receive from all types).

---

## 📊 Blood Type Compatibility Chart

| Blood Type | Can Donate To | Can Receive From |
| :---: | :--- | :--- |
| **O+** | O+, A+, B+, AB+ | O+, O- |
| **O-** | All blood types | O- |
| **A+** | A+, AB+ | A+, A-, O+, O- |
| **A-** | A+, A-, AB+, AB- | A-, O- |
| **B+** | B+, AB+ | B+, B-, O+, O- |
| **B-** | B+, B-, AB+, AB- | B-, O- |
| **AB+** | AB+ | All blood types |
| **AB-** | AB+, AB- | AB-, A-, B-, O- |

---

## 💻 Usage Example
