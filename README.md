# Multi Agent Playground

This demonstrates the workflow using different agents to compare stock options and summarize the findings. Here we're using llama3.3, yfinancetools, groq, and phidata.

## Installation

1. **Install Python using Homebrew:**

    ```bash
    % brew install python
    ```

2. **Create a virtual environment that will be used:**

    ```bash
    % mkdir ~/.virtualenvs
    % python -m venv $HOME/.virtualenvs/ai_playground
    % source $HOME/.virtualenvs/ai_playground/bin/activate
    % python -m pip install phi
    ```

3. **Install dependencies:**

    ```bash
    % pip install -r requirements.txt
    ```

## Usage

1. Create an API key in https://console.groq.com. I have created my API keys in groq and have placed them in .env file.

2. Run the file `agent.py` using:

```bash
% python agent.py
```
