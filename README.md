# Password Manager (Tkinter)

A clean and simple **Password Manager** built with Python and Tkinter. The app lets you generate secure passwords, save website credentials locally, and automatically copy passwords to the clipboard.

---

## 🚀 Features

### 🔐 Secure Password Generator

- Generates strong random passwords using letters, numbers, and symbols.
- Automatic clipboard copy using `pyperclip`.
- Randomized length for improved security.

### 📝 Credential Storage

- Saves entries in `data.txt` using:

  ```
  website | email | password
  ```

- Prevents saving when fields are empty.
- Shows confirmation dialog before adding credentials.

### 🖥️ Tkinter GUI

- Clean and intuitive layout.
- Logo displayed via `Canvas`.
- Buttons for generating and saving passwords.
- Default email pre-filled.

---

## 📂 Project Structure

```
password_manager_tkinter/
│
├── main.py           # Application logic and UI
├── data.txt          # Saved credentials (ignored by Git)
├── logo.png          # App logo
├── .gitignore        # Excludes sensitive/files
├── requirements.txt  # Pinned Python dependencies
└── README.md         # Project README (this file)
```

---

## ▶️ How to Run

1. Install dependencies:

   ```bash
   pip install pyperclip
   ```

2. Run the application:

   ```bash
   python main.py
   ```

---

## 📦 Dependencies

- Tkinter (built-in)
- pyperclip

---

## ⚠️ Security Note

This project is for learning purposes. Credentials are saved in plain text and **should not be used for real passwords**.

---

## 👤 Author

Created by **Mevaser Zehoray** as part of the 100 Days of Python course.
