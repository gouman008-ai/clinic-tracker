# 🏥 Hospital Patient Registration & Follow-up Tracker

A browser-based **terminal-style hospital management system** built using **HTML, CSS, and JavaScript**.  
It simulates a **C-program-like interface** where users can manage patient records and visit history interactively.

---

## 📌 Features

- 👤 Register new patients
- 🩺 Add visit records (diagnosis & prescription)
- 🔍 Search patient by ID
- 📜 View patient visit history
- 📊 Track frequent visitors
- 📋 List all patients
- 💾 Save & load data using `localStorage`
- 💻 Terminal-style UI for interactive experience

---

## 🖥️ Demo Interface
- Link: *https://gouman008-ai.github.io/clinic-tracker/*
- Command-line inspired UI inside the browser
- Input commands using the text field
- Press **Enter** or click **Send**

---

## ⚙️ Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- Browser localStorage (for persistence)

---

## 📂 Project Structure
hospital-tracker/
│
├── index.html # Main application file
└── README.md # Project documentation
---

## 🚀 How to Run

1. Download or clone the repository
2. Open the `index.html` file in any browser
3. Start interacting with the system

---

## 🧭 Menu Options

Register New Patient
Add Visit Record
Search Patient by ID
Show Visit History for Patient
Show Visit Count / Frequent Visitors
List All Patients
Save Data
Exit

---

## 🧠 Data Model

### Patients
```js
{
  patientID: Number,
  name: String,
  age: Number,
  phone: String
}
Visits
{
  visitID: Number,
  patientID: Number,
  date: String,
  diagnosis: String,
  prescription: String
}
🔐 Validation Rules
Patient ID must be unique and positive
Age must be between 1–120
Phone number must be 10 digits
Date format: DD-MM-YYYY
💾 Data Persistence
Data is stored in browser using localStorage
Automatically loads on refresh
Manual save option available
⭐ Special Highlights
Simulates C programming logic (scanf-style flow) using JavaScript state machine
Clean separation of:
UI handling
State management
Data logic
Lightweight and runs entirely in the browser
⚠️ Limitations
No backend/database (client-side only)
Data tied to browser storage
No authentication
🔮 Future Improvements
Add backend (Node.js / Firebase)
Export data as CSV/PDF
UI enhancements (themes, dashboard)
Patient edit/delete functionality
📄 License

This project is open-source and free to use for learning purposes.
