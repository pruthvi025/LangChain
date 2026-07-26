# LangChain Learning & AI Agents 🦜🔗

Welcome to the **LangChain Learning** repository! This repository contains practical guides, Jupyter notebooks, and scripts for learning LangChain, integrating various Large Language Models (LLMs), creating custom tools, and building autonomous AI agents.

---

## 📁 Repository Structure

```text
langchain-learning/
├── updated_LangChain/
│   ├── 1-langchain_intro.ipynb       # Intro to LangChain & building basic AI agents with tools
│   ├── 2-ModelIntegration.ipynb     # Model integration across OpenAI, Google Gemini, Groq, etc.
│   └── 3-tools.ipynb                # Creating and using custom tools with LangChain agents
├── 4-messages.ipynb                  # Handling messages, system prompts, and conversation state
├── main.py                           # Python entry point script
├── pyproject.toml                    # Project configuration and dependency specifications
├── requirements.txt                  # List of Python dependencies
└── README.md                         # Project documentation
```

---

## 🚀 Features & Highlights

- **Multi-Model Integrations**: Connect seamlessly to top AI providers:
  - OpenAI (`gpt-4.1`, `gpt-4o`)
  - Google Gemini (`gemini-2.5-flash`, `langchain-google-genai`)
  - Groq (`langchain-groq`)
  - Vertex AI & OpenRouter
- **Custom Tools & Agents**: Define Python functions as tools and bind them to agents powered by LangGraph / LangChain.
- **Message Management**: Work with `SystemMessage`, `HumanMessage`, `AIMessage`, and chat history management.
- **Modern Python Tooling**: Managed with `uv` and Python 3.13+.

---

## 🛠️ Getting Started

### 1. Prerequisites

Make sure you have **Python 3.13+** installed. You can also use [`uv`](https://github.com/astral-sh/uv) for fast package management.

### 2. Installation

Clone the repository and set up a virtual environment:

```bash
# Clone the repository
git clone https://github.com/pruthvi025/LangChain.git
cd LangChain

# Create and activate virtual environment (using standard venv or uv)
python -m venv .venv

# On Windows (PowerShell):
.venv\Scripts\Activate.ps1

# Install dependencies
pip install -r requirements.txt
# OR using uv:
# uv sync
```

### 3. Environment Setup

Create a `.env` file in the root directory and add your API keys:

```env
OPENAI_API_KEY=your_openai_api_key_here
GOOGLE_API_KEY=your_google_api_key_here
GROQ_API_KEY=your_groq_api_key_here
```

> **Note**: Never commit your `.env` file to version control. It is already added to `.gitignore`.

---

## 💻 Running the Code

### Running Jupyter Notebooks
Launch Jupyter Notebook or VS Code / Jupyter Lab to explore the tutorials in order:

```bash
jupyter notebook
```

1. **`updated_LangChain/1-langchain_intro.ipynb`**: Introduction to LangChain and basic agent creation.
2. **`updated_LangChain/2-ModelIntegration.ipynb`**: Comparing and invoking models using `init_chat_model`.
3. **`updated_LangChain/3-tools.ipynb`**: Building custom tools.
4. **`4-messages.ipynb`**: Advanced message handling.

### Running standard Python script

```bash
python main.py
```

---

## 📜 License

This repository is for educational and learning purposes.
