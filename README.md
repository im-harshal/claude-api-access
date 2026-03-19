# Claude API Access

A collection of Jupyter notebooks exploring different ways to interact with the Claude API — built as hands-on exercises while learning the Claude API course.

## 📚 What's Inside

The `notebooks/` directory contains exercises covering:
- Connecting to the Claude API using an API key
- Sending requests and handling responses
- Experimenting with different prompting approaches

## 🚀 Getting Started

### Prerequisites
- Python (see `.python-version` for the required version)
- An [Anthropic API key](https://console.anthropic.com/)
- `uv` for dependency management

### Installation
```bash
git clone https://github.com/im-harshal/claude-api-access.git
cd claude-api-access
uv sync
```

### Setup

Create a `.env` file in the root directory and add your API key:
```
ANTHROPIC_API_KEY=your_api_key_here
```

> ⚠️ Never commit your API key. It's already covered by `.gitignore`.

### Running the Notebooks

Launch Jupyter and open any notebook from the `notebooks/` folder:
```bash
jupyter notebook
```

## 🛠️ Tech Stack

- Python
- [Anthropic Python SDK](https://github.com/anthropic/anthropic-sdk-python)
- Jupyter Notebooks
- uv (package manager)

## 📖 Resources

- [Anthropic API Docs](https://docs.anthropic.com)
- [Claude API Reference](https://docs.anthropic.com/en/api/getting-started)
