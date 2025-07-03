# 🍺 What is Homebrew?

### 📘 Overview

**Homebrew** is a **package manager** for macOS.

It makes it super easy to **install**, **update**, and **manage** software on your Mac — especially developer tools that aren’t available in the App Store.

> Without Homebrew: You’d need to manually download apps, move them into folders, and configure them.
>  
> With Homebrew: Just type a single command in the terminal and you're done. ✅

---

## 🧠 Why Was Homebrew Created?

Installing developer tools on macOS used to be a pain:

- You had to download `.zip` or `.dmg` files from websites
- Drag apps into `/Applications`
- Deal with complex manual setup

**Homebrew was created in 2009** to fix this — by bringing the simplicity of **Linux-style package managers** (like `apt` or `yum`) to macOS.

---

## ⌛ A Little History

- 🧑‍💻 Homebrew was created by **Max Howell** in 2009
- It became the **de facto** tool for macOS developers
- It is open-source and maintained by a large community
- Works via the terminal and installs tools into `/opt/homebrew` on Apple Silicon Macs

---

## 🧪 What Can Homebrew Do?

- Install software
- Manage versions and dependencies
- Keep tools up to date
- Uninstall tools cleanly

---

## 🧠 Analogy: App Store for Developers

Think of **Homebrew** as the **App Store**, but for developer tools.

- Instead of searching and clicking, you just type:
  
```bash
brew install tree
```

## ⚙️ Installing Homebrew (macOS)

Open your terminal(cmd+space then type terminal and hit enter) and run:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

After installation, follow the instructions it prints — it will tell you to add some lines to your shell config (`.zprofile` or `.zshrc`).

To verify it's working:
```bash
brew --version
```

✅ If it prints a version number — you're ready!

## Install Visual Studio Code

**Visual Studio Code (VS Code)** is a **free**, **open-source**, and **lightweight** code editor developed by Microsoft.

It’s one of the most popular tools used by professional developers today — and for good reason: it’s fast, powerful, and highly customizable.

Run the below command to install VS Code

```bash
brew install --cask visual-studio-code
```


## ✅ Summary

- **Homebrew** is the go-to package manager for developers on macOS.
- It simplifies installing, updating, and managing tools like VS Code.
- You'll be using Homebrew regularly throughout your developer journey.