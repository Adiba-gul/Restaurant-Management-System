# 🍽️ Restaurant Management System (8086 Assembly)

This project is a **console-based Restaurant Management System** developed using **8086 Assembly Language (MASM/TASM syntax)**.  
It allows users to select food categories, choose menu items, enter quantity, and generate a final bill.

---

## 📌 Features

- Category-based menu system  
  - Breakfast  
  - Lunch  
  - Dinner  
  - Snacks  
  - Drinks  
- Menu item selection (1–8)  
- Quantity input (1–9)  
- Automatic total bill calculation  
- Navigation options:  
  - Main Menu  
  - Previous Menu  
  - Show Bill  
  - Exit  
- Proper input validation for wrong entries  

---

## 🛠️ Technologies Used

- **Language:** 8086 Assembly Language  
- **Assembler:** MASM / TASM  
- **Platform:** DOSBox / EMU8086  
- **Interrupts Used:**  
  - `INT 21h` – Input / Output  
  - `INT 10h` – Screen handling  

---

## 📂 Project Structure
Restaurant-Management-System/ │ ├── main.asm └── README.md
Copy code

---

## ⚙️ Program Workflow

1. Program starts with a welcome screen  
2. User selects a food category  
3. Selected category menu is displayed  
4. User selects item number and quantity  
5. Bill is calculated and added to total  
6. User can:  
   - Return to main menu  
   - Go back to previous category  
   - View final bill  
7. Program exits safely  

---

## 🧠 Concepts Implemented

- Macros for printing strings  
- Procedures (`proc / endp`)  
- Arrays for price storage  
- Loops and conditional jumps  
- ASCII to numeric conversion  
- Stack-based number printing  

---

## 🖥️ Sample Output
=============================== Welcome to our Restaurant!
=== Categories ===
Breakfast
Lunch
Dinner
Snacks
Drinks
Exit
Copy code

---

## 🚀 How to Run

1. Open **DOSBox** or **EMU8086**  
2. Load the file `main.asm`  
3. Assemble and run the program  
4. Follow on-screen instructions  

---

## 📖 Learning Outcome

This project helped in understanding:  
- Assembly language programming  
- Low-level input/output handling  
- Logical flow control  
- Modular programming using procedures  

---

## 👩‍💻 Author

**Adiba**  
BS Software Engineering Student  
SZABIST University
