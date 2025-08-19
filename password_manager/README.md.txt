# 🔐 Password Manager

A simple yet powerful **GUI-based Password Manager** built with **Python Tkinter**.  
It can generate strong random passwords, copy them to clipboard, and save login details securely into a local file.  

---

## ✨ Features
- 🎲 **Password Generator**: Creates strong random passwords with letters, numbers, and symbols.  
- 📋 **Auto-Copy to Clipboard**: Generated password is automatically copied using `pyperclip`.  
- 💾 **Save Passwords**: Stores website, email/username, and password into `data.txt`.  
- 🖥️ **User-Friendly GUI**: Built with Tkinter for an easy-to-use interface.  
- ⚠️ Prompts user before saving, ensuring no accidental entries.  

---

## 📂 Files in Project
- **main.py** → The main Password Manager script.  
- **logo.png** → Logo image displayed in the UI.  
- **data.txt** → Auto-created file where saved credentials are stored.  

---

## 🛠️ Tech & Tools
- **Python 3.x**  
- Libraries:  
  - `tkinter` (GUI)  
  - `random` (password generation)  
  - `pyperclip` (clipboard copy)  

---

## 🚀 How to Run
1. Install dependencies:
   ```bash
   pip install pyperclip
