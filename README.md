# 🤖 AI Code Review Agent

An AI-powered code review agent that analyzes source code and provides feedback on bugs, security issues, performance, code style, and possible improvements.

The project uses **Ollama** to run an AI coding model locally, so you can review code without using a paid OpenAI API.

## ✨ Features

- 🔍 Detects bugs and correctness issues
- 🔐 Identifies potential security problems
- ⚡ Reviews performance and efficiency
- 📝 Checks code style and readability
- 💡 Suggests improvements and refactoring
- 📊 Provides an overall code quality rating
- 🖥️ Supports inline code snippets
- 📁 Supports reviewing code files
- 🆓 Uses Ollama for free local AI inference

## 🛠️ Technologies Used

- Python
- LangChain
- LangChain Ollama
- Ollama
- Qwen2.5-Coder
- python-dotenv

## 📂 Project Structure

```text
02-code-review-agent/
│
├── agent.py
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
└── venv/