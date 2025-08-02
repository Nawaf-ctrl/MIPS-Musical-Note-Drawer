# 🎵 MIPS Musical Note Drawer

A MIPS assembly program that draws musical notes on the MARS bitmap display, offering interactive command-line control through syscall input.

---

## 🧠 Features

- Menu-driven command-line interface
- Allows user input for selecting:
  - Action: clear screen, draw stave lines, draw note, exit
  - Colour selection (minimum of 3 options)
- Dynamic screen colouring using syscall
- Supports multiple character inputs for notes (advanced mode)
- Gracefully handles invalid inputs

---

## 💻 Technologies Used

- MIPS Assembly Language
- MARS (MIPS Assembler and Runtime Simulator)
- Bitmap Display Tool
- Syscall for I/O interaction

---

## 🚀 How to Use

1. Open the project in **MARS**.
2. Enable **Bitmap Display** from `Tools > Bitmap Display`.
   - Set **Unit width & height**: `8`
   - Set **Display width & height**: e.g., `512x256`
3. Run the program.
4. Follow the on-screen menu:
   - Input an integer for the action (e.g., `0` for `cls`, `1` for `stave`, etc.)
   - Input another integer for the colour selection

---

## 🧾 Menu Options (Example)

| Option | Action        |
|--------|---------------|
| 0      | Clear screen  |
| 1      | Draw stave    |
| 2      | Draw note     |
| 9      | Exit program  |

> Colour choices may range from `1` to `3+`, depending on implementation.

---

## 🧱 Code Structure Highlights

- Uses syscall for I/O
- Modular design using labels and procedures
- Employs loops and branches for repeated interaction
- Well-commented and organized for clarity

---
