# 🐚 Custom Bash Configuration

This repository contains a customized `.bashrc` configuration designed to improve terminal usability, productivity, and developer experience.

📄 Source configuration: see provided bashrc file

---

## ✨ Features

### 🎨 Enhanced Prompt
- Custom Bash prompt with:
  - Username and host
  - Current working directory
  - Git branch (if inside a repo)
  - Status indicator for last command

### 🔀 Git Integration
- Displays current Git branch automatically
- Shows dirty state (optional config)

### 🧠 Smart History Handling
- Avoid duplicate commands
- Append history instead of overwriting
- Increased history size:
  - `HISTSIZE=1000`
  - `HISTFILESIZE=2000`

### 📂 Improved CLI Experience
- Auto-adjust terminal size
- Colored output for:
  - `ls`
  - `grep`, `fgrep`, `egrep`

### ⚡ Useful Aliases
```bash
alias ll="ls -lah"
alias la="ls -A"
alias l="ls -CF"
alias gs="git status"
alias alert="notify-send --urgency=low ..."
