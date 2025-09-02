# GitHub Copilot Tips

This repository contains strategies to use GitHub Copilot efficiently for vibe coding.

## Modes

- **Ask:** Interact with Copilot by asking questions or requesting code suggestions.
- **Edit:** Modify, refactor, or improve existing code automatically.
- **Agent:** Specify context or scope (workspace, file, terminal) to tailor responses and interact with the whole project.

## Shortcuts

### Code Suggestions
- `Tab` — Accept suggestion
- `Esc` — Reject suggestion
- `Alt+]` (Windows/Linux) or `Option+]` (Mac) — Cycle through alternatives
- `>` / `<` — Arrow keys to cycle suggestions

### VS Code Chat Extension
- Inline (works in both editor & terminal):
  - `Ctrl+I` (Windows/Linux)
  - `Cmd+I` (Mac)

## Command Types

### Slash Commands
- `/explain` — Explain selected code
- `/suggest` — Suggest code based on context
- `/tests` — Generate unit tests for selected function/class
- `/comment` — Convert comments into code snippets
- `/fix` — Fix errors highlighted in code
- `/docs` — Add documentation for code
- `/clear` — Clear chat session
- `/generate` — Generate code to answer a question
- `/help` — Get help on using Copilot chat
- `/optimize` — Analyze and improve runtime of selected code
- `/setupTests` — Create unit tests at workspace level
- `/fixTestFailure` — Attempt to fix failing unit tests

### Agent Commands
- `@workspace` — Agent aware of entire workspace (use `#codebase` for more features)
- `@terminal` — Agent interacts with terminal
- `@file` — Focus on a specific file
- `@directory` — Consider a specific directory
- `@vscode` — Interact with VS Code features
- `@github` — Code search and access enterprise knowledge bases

**Examples:**
- `@workspace Document how to run this project for new developers in README.md.`
- `@terminal How do I fix the error message I'm seeing?`
- `@file Refactor this function in main.py.`
- `@directory Optimize scripts in the utils directory.`

### Context Commands
- `#<file or folder name>` — Choose a file/folder as context
- `#codebase` — Add relevant workspace content as context
- `#editor` — Add currently open editor as context
- `#terminalSelection` — Add active terminal's selection
- `#terminalLastCommand` — Add active terminal's last command
- `#githubRepo` — Search the GitHub repository

### Quick Actions (Inline)
- `Modify` — Modify code inline
- `Review` — For code review

## Reference

- [GitHub Copilot Learning Path](https://learn.microsoft.com/en-us/training/courses/gh-300t00)
- [Accelerate Development using Copilot](https://learn.microsoft.com/en-us/training/paths/accelerate-app-development-using-github-copilot/)