# Git and Visual Studio Code Setup Guide

## 📥 Step 1: Download and Install Git

1. Go to the official Git website: https://git-scm.com/downloads
2. Choose your operating system (Windows, macOS, or Linux).
3. Download and run the installer.
4. During installation, accept the default settings unless you know what to change.
5. After installation, open a terminal or command prompt and run:

   ```bash
   git --version
   ```

   ✅ If it prints a version, Git was installed successfully.

---

## 🖥️ Step 2: Download and Install Visual Studio Code

1. Go to the official VS Code website: https://code.visualstudio.com/
2. Click **Download** for your OS.
3. Run the installer and follow the setup instructions.
4. Launch Visual Studio Code.

---

## ⚙️ Step 3: Configure Git in Visual Studio Code

1. Open VS Code.
2. Open the **Command Palette** (press `Ctrl+Shift+P` or `Cmd+Shift+P`).
3. Type `Git: Clone` to clone a repository, or:
4. Open a terminal in VS Code (`` Ctrl+` ``) and run:

   ```bash
   git config --global user.name "Damola313"
   git config --global user.email "ariyodamola3@gmail.com"
   ```

---

## 🧑‍💻 Step 4: Clone a GitHub Repo (or Push Your Own)

### 🔄 To Clone:

### 🚀 To Push Your Code:

1. Initialize Git if you haven’t already:

   ```bash
   git init
   ```

2. Add all files:

   ```bash
   git add .
   ```

3. Commit the changes:

   ```bash
   git commit -m "Initial commit"
   ```

4. Add your GitHub remote:

   ```bash
   git remote add origin https://github.com/username/repo.git
   ```

5. Push your code:

   ```bash
   git push -u origin master
   ```

   > 🔁 Use `main` instead of `master` if your GitHub repo uses `main` branch.

---

### 🔄 Sceenshoot: ![alt text](<Screenshot 2025-04-25 165449.png>)
## ✅ Done!

You're now set up to work with Git and VS Code and push your projects to GitHub.
