# 🚀 DevTools: A Suite of Developer Productivity Tools

Welcome to **DevTools**, a powerful suite of command-line tools designed to make developers' lives easier. This project is a collection of utilities that streamline common tasks in web development, Git workflows, configuration management, and more. Each tool can be used independently or as part of this unified toolkit.

## 🌟 Overview

DevTools is organized as a hybrid monorepo, where each tool is housed in its own folder with the potential for independent development, versioning, and deployment. This structure allows for easy scalability and flexibility, enabling you to pick and choose the tools you need.

### 📁 Project Structure
```
devtools/
├── easy-git/             # Simplify Git operations with an interactive CLI
├── structurer/           # Generate and manage project folder structures
├── dotfiles/             # Manage and sync your dotfiles effortlessly
├── todo-list-tui/        # Terminal-based To-Do list manager
├── config-generator/     # Generate configuration files for popular tools
├── shared/               # Shared utilities and resources (used across tools)
└── README.md             # You're here!
```

---

## 🛠️ Tools Included

### 1. **easy-git**
Simplify your Git workflow with interactive commands for staging files, committing changes, and managing branches. Perfect for both beginners and seasoned Git users.

### 2. **structurer**
Automate the creation of standardized project structures for frontend, backend, or full-stack development. Get started with a clean, organized codebase in seconds.

### 3. **dotfiles**
A tool to manage, backup, and sync your dotfiles across multiple systems. Keep your development environment consistent, no matter where you are.

### 4. **todo-list-tui**
A terminal-based To-Do list manager with a sleek and intuitive interface. Organize your tasks, set priorities, and boost your productivity—all within your terminal.

### 5. **config-generator**
Quickly generate configuration files for popular development tools like `nvim`, `git`, `tmux`, and more. Save time setting up your environment with pre-defined templates.

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

# Generating a project structure
./devtools structurer create my-awesome-project
```

---

## 📚 Documentation

Detailed documentation for each tool can be found in its respective directory:

- [easy-git](./easy-git/README.md)
- [structurer](./structurer/README.md)
- [dotfiles](./dotfiles/README.md)
- [todo-list-tui](./todo-list-tui/README.md)
- [config-generator](./config-generator/README.md)

---

## 🤝 Contributing

We welcome contributions! If you have ideas for new tools or improvements to existing ones, feel free to open an issue or submit a pull request.

### Steps to Contribute
1. Fork the repository.
2. Create a new branch: `git checkout -b feature/new-tool`.
3. Make your changes and commit them: `git commit -m 'Add new feature'`.
4. Push to the branch: `git push origin feature/new-tool`.
5. Open a pull request.

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

---

## 📬 Contact

For questions, suggestions, or feedback, please open an issue or reach out to us at [allouchomar1@gmail.com](mailto:allouchomar1@gmail.com).

---

Happy coding! 🚀
