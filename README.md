🍽️ Restaurant Management System (8086 Assembly)
This project is a console-based Restaurant Management System developed using 8086 Assembly Language (MASM/TASM syntax).
It allows users to select food categories, choose items, enter quantity, and generate a final bill.
📌 Features
📋 Category-based Menu System
Breakfast
Lunch
Dinner
Snacks
Drinks
🧾 Dynamic Bill Calculation
Select item (1–8)
Enter quantity (1–9)
Automatic total price calculation
🔄 Navigation Options
Go to Main Menu
Go to Previous Category
Show Final Bill
Exit Program
❌ Input Validation
Handles invalid menu and quantity inputs gracefully
🛠️ Technologies Used
Language: 8086 Assembly Language
Assembler: MASM / TASM
Platform: DOSBox / EMU8086
Interrupts Used:
INT 21h (Input/Output)
INT 10h (Screen handling)
📂 Program Structure
Copy code

Restaurant-Management-System/
│
├── main.asm        # Main source code
├── README.md       # Project documentation
⚙️ How It Works
Program starts with a Welcome Screen
User selects a Food Category
Menu items are displayed
User selects:
Item number
Quantity
Price is calculated and added to total
User can:
Go back
Continue ordering
View final bill
Program exits safely
🧠 Key Concepts Implemented
Macros (print macro)
Procedures (proc / endp)
Arrays for price storage
Loops and conditional jumps
ASCII to numeric conversion
Stack usage for number printing
🖥️ Sample Output
Copy code

===============================
   Welcome to our Restaurant!
===============================

=== Categories ===
1. Breakfast
2. Lunch
3. Dinner
4. Snacks
5. Drinks
6. Exit
🚀 How to Run
Open DOSBox or EMU8086
Load the main.asm file
Assemble and run the program
Follow on-screen instructions
📖 Learning Outcome
This project helped in understanding:
Low-level programming
Assembly language logic
User input handling
Modular program design using procedures
👩‍💻 Author
   Adiba gul
BS Software Engineering Student
📍 SZABIST University
