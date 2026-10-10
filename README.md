# LangChain Tutorial

This repository contains a collection of beginner-friendly LangChain notebooks covering core concepts such as agent creation, guardrails, tools, middleware, and message handling.

The notebooks are intended for learning and experimentation with LangChain in a practical, hands-on way.

## Project overview

The workspace includes the following notebooks:

- `chat_model.ipynb` — working with chat models and basic LLM interaction
- `Guardrail.ipynb` — protecting agents with middleware and safety checks
- `Langchain_Agent.ipynb` — creating and configuring LangChain agents
- `Langchain_Tools.ipynb` — using tools with agents
- `messages.ipynb` — understanding message structures and flows
- `Middleware.ipynb` — adding middleware to agents and applications

## Requirements

Before running the notebooks, make sure you have:

- Python 3.10 or newer
- An active virtual environment (recommended)
- API access to an LLM provider such as OpenAI
- Required Python dependencies installed

## Setup

1. Clone the repository.
2. Create and activate a virtual environment:

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
.venv\Scripts\activate      # Windows
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

If a `requirements.txt` file is not present, install the commonly used packages manually:

```bash
pip install python-dotenv langchain langchain-openai langgraph
```

4. Create a `.env` file in the project root and add your API keys, for example:

```bash
OPENAI_API_KEY=your_key_here
```

5. Open the notebooks in VS Code or Jupyter and run the cells in order.

## Important notes

- Some notebooks may require valid API keys and a working internet connection.
- The examples are meant for learning; you may need to adapt model names or library versions depending on your installed environment.
- If you see dependency errors, upgrade LangChain and related packages to the versions compatible with your Python installation.

## Learning flow

A good order to explore the project is:

1. `chat_model.ipynb`
2. `messages.ipynb`
3. `Langchain_Agent.ipynb`
4. `Middleware.ipynb`
5. `Langchain_Tools.ipynb`
6. `Guardrail.ipynb`

## Notes for contributors

This project is a tutorial workspace, so the notebooks are best kept clear, readable, and beginner-friendly. Prefer simple explanations, short comments, and well-structured sections when adding new examples.

## License

This project is intended for educational use unless otherwise specified by the original source or author.
