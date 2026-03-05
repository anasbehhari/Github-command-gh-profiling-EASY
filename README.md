# 🚀 gh-config

A simple **Windows batch script** to manage multiple Git profiles easily from the command line.

This tool helps developers quickly switch between different Git identities (for example: work, personal, or open-source accounts) without manually editing Git configuration files.

---

## 📌 Features

- Create multiple Git profiles
- Switch between profiles instantly
- List all available profiles
- Delete unused profiles
- Simple command-line interface
- Lightweight and easy to use

---

## 📖 Description

When working with multiple Git accounts, developers often need to change their **username and email configuration** depending on the project they are working on.

The `gh-config` script simplifies this process by allowing you to create and manage multiple Git profiles and switch between them with a single command.

This avoids repeatedly running manual Git configuration commands such as:

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

---

## ⚙️ Requirements

Before using this script, make sure you have:

- Git installed
- Windows Command Prompt or PowerShell
- Basic Git knowledge

---

## 📥 Installation

1. Download the file:

   gh-config.bat

2. Save it to a convenient location, for example:

   C:\gh-config

3. (Optional but recommended) Add the folder to your **System PATH** so you can run the command from anywhere.

Example PATH location:

   C:\gh-config

After adding it to PATH, restart your terminal.

---

## 💻 Usage

Open **Command Prompt** or **PowerShell** and run:

gh-config

This will display the list of available Git profiles.

---

## 🧪 Commands

Create a new profile:

gh-config create

Switch to a profile:

gh-config use [profile_name]

Example:

gh-config use work

List all profiles:

gh-config list

Delete a profile:

gh-config delete [profile_name]

Example:

gh-config delete personal

Default command (lists profiles):

gh-config

---

## 📂 Example

gh-config create
Enter profile name: work
Enter email: work@email.com
Enter username: Work User

gh-config use work

gh-config list

Output example:

Available profiles:
- work
- personal

---

## 🚀 Why Use gh-config

Managing multiple Git identities manually can be time-consuming and error-prone.

This tool allows you to:

- Switch Git accounts instantly
- Avoid committing with the wrong identity
- Simplify development workflows
- Improve productivity when working across multiple projects

---

## 👨‍💻 Author

Anas Behhari

GitHub:
https://github.com/anasbehhari

---

## ⭐ Support

If you find this project useful, consider giving the repository a **star** on GitHub.
