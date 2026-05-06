# 📋 Mark Statement Generator

A lightweight, browser-based tool to generate individual student mark statements from a class result Excel sheet — no installation, no server, no login required.

---

## 🚀 Live Demo

👉 **[Open the tool](https://imanabsarmah.github.io/mark-statement-generator)**

*(Replace the link above with your actual GitHub Pages URL after publishing)*

---

## ✨ Features

- Upload any `.xlsx` / `.xls` / `.csv` result sheet
- Auto-detects student name, roll number, subject columns
- Manually remap columns if auto-detection is off
- Displays individual mark statement with grades, percentage, and overall result
- Result badge automatically shows:
  - **PROMOTED** — passes all or fails only 1 subject
  - **PROMOTED UNDER CONSIDERATION** — fails exactly 2 subjects
  - **Withheld** — fails 3 or more subjects
- Co-scholastic activities section (optional)
- Print single student or bulk-print all students
- School logo support
- English / Hindi language toggle
- Works entirely in the browser — your data never leaves your device

---

## 📥 Getting Started

### 1. Download the sample template

👉 **[Download template.xlsx](template.xlsx)**

Fill in your students' marks — one row per student. You can:
- Rename `Subject 1`, `Subject 2`, etc. to actual subject names (e.g. English, Mathematics)
- Add or remove subject columns as needed
- Keep `Total`, `%age`, and `Result` columns — they are auto-calculated

### 2. Open the tool

Open the [live tool](https://imanabsarmah.github.io/mark-statement-generator) in any browser.

### 3. Fill in school details

Enter your school name, class, academic year, and examination name (e.g. *First Terminal Examination*).

### 4. Upload your file

Drag and drop your filled Excel file or click to browse.

### 5. Map columns & select student

The tool will auto-detect columns. Adjust if needed, then select a student from the dropdown to preview their statement.

### 6. Print

Click **Print Statement** for a single student, or **Print All** to generate statements for the entire class.

---

## 📂 File Structure

```
mark-statement-generator/
├── index.html       ← The main tool (open this in a browser)
├── template.xlsx    ← Sample result sheet template
└── README.md        ← This file
```

---

## 🛠 Tech Stack

Plain HTML + CSS + JavaScript — no frameworks, no dependencies except [SheetJS](https://sheetjs.com/) (loaded via CDN) for Excel parsing.

---

## 📄 License

Free to use for personal and educational purposes.
