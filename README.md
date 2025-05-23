# Vaultix 🔐  
**Your Personal Modern Password Manager**

Vaultix is a sleek, cross-platform password manager built with **PyQt6**, designed to securely store and manage your login credentials — including usernames, passwords, emails, and website URLs — all in one local, base64-encoded environment.

---

## 🌟 Features

- 🧠 **Secure Storage**  
  Keep all your credentials safe in local, base64-encoded `.vault` files

- 🔑 **Modern User Interface**  
  Clean design with smooth animations and a responsive layout

- 🎨 **Dark & Light Mode**  
  Easily toggle between dark and light themes

- 🔐 **Smart Password Generator**  
  Generate secure, memorable or complex passwords with a single click

- 🔄 **Multi-Database Support**  
  Create and switch between multiple vault files

- 🌐 **Website Integration**  
  Save URLs and open them directly from the app

- 🖥️ **Cross-Platform**  
  Runs on Windows, macOS, and Linux thanks to PyQt6

---

## 📋 Requirements

- Python 3.6 or higher  
- PyQt6  
- (Optional) `pyperclip` for clipboard support (auto-installed)

---

## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/vaultix.git
cd vaultix
```

Install the dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python main.py
```

---

## 💻 Usage

### 🔧 Creating a Database
1. Click on **"Create Database"**
2. Enter a name (the `.vault` extension is added automatically)

### ➕ Adding Accounts
1. Select a database from the dropdown
2. Enter the account’s name, email, password, and website URL
3. Click **"Add Account"** to save

### 🔁 Managing Accounts
- Generate passwords with the built-in generator
- Edit existing entries via **"Edit Password"**
- Copy any field to clipboard with a single click
- Open websites directly from stored URLs

### 🎨 Interface Controls
- Toggle between dark/light mode using the theme button  
- Resize panels via the drag-able splitter

---

## 🔒 Security Note

Vaultix uses **base64 encoding** for storing your data — this provides a basic level of obfuscation. While it's not encryption, it protects casual snooping and is suitable for personal use.  
**All data is stored locally.**

---

## 🛠️ Contributing

We welcome contributions!  
Feel free to open an issue, suggest a feature, or submit a pull request.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).
