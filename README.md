# 🚀 DevTools: A Suite of Developer Productivity Tools (Work in progress)

Welcome to **DevTools**, a powerful suite of command-line tools designed to make developers' lives easier. This project is a collection of utilities that streamline common tasks in web development, Git workflows, configuration management, and more. Each tool can be used independently or as part of this unified toolkit.

## 🌟 Overview

DevTools is organized as a hybrid monorepo, where each tool is housed in its own folder with the potential for independent development, versioning, and deployment. This structure allows for easy scalability and flexibility, enabling you to pick and choose the tools you need.

### 📁 Project Structure
```
devtools/
├── easy-git/             # Simplify Git operations with an interactive CLI
└── README.md             # You're here!
```

---

## 🛠️ Tools Included

### 1. **easy-git**
Simplify your Git workflow with interactive commands for staging files, committing changes, and managing branches. Perfect for both beginners and seasoned Git users.

---

## 📦 Getting Started

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/devtools.git
cd devtools

# Initialize submodules (if using submodules)
git submodule update --init --recursive
```

### Usage

Each tool is self-contained. Navigate to a specific tool's directory to see its usage instructions:

```bash
cd easy-git
python3 main.py  # or ./easy-git if it's a shell script
```

Alternatively, you can run each tool from the root directory using the `devtools` command (if you have a unified CLI interface):

```bash
./devtools easy-git
./devtools structurer
```

### Example
```bash
# Using the easy-git tool
./devtools easy-git commit
```

---

## 📚 Documentation

Detailed documentation for each tool can be found in its respective directory:

- [easy-git](./easy-git/README.md)

---

## 📬 Contact

For questions, suggestions, or feedback, please open an issue or reach out to us at [allouchomar1@gmail.com](mailto:allouchomar1@gmail.com).

---

Happy coding! 🚀
