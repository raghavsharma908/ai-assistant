# Python Tkinter Chat Assistant with SQLite History

A premium, modern dark-themed desktop chat assistant built entirely in Python using standard GUI and storage libraries (`tkinter` and `sqlite3`). 

## ✨ Key Features
* **Modern Dark Theme**: Customized HSL-tailored Catppuccin color scheme, rounded-appearing conversation bubble layout, and custom sidebar animations.
* **Persistent Chat History**: Relational SQLite storage locally saving conversation threads, enabling restoration and dynamic toggling.
* **Smart Session Naming**: Automatically titles saved threads using parsed snippets from your first message.
* **Empty State Handling**: Elegant styling prompting a clean welcome when history or databases are empty.
* **Cross-Platform Compatibility**: Uses built-in Windows high DPI process scaling to guarantee crisp rendering on high-resolution monitors.

## 🛠️ Tech Stack & Architecture
* **Frontend**: Pure Python `tkinter` & `ttk` style overrides.
* **Database**: Local `sqlite3` relational engine.
* **Modular Clean Code**: Organized strictly in small, isolated functions for maintainable code structure.

## 🚀 Running Locally
You can run the application directly from the terminal with no third-party package dependencies required:
```powershell
python ai,py
```
*(Yes, using the literal filename `ai,py` containing a comma!)*
