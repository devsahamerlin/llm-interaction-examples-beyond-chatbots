# LLM Interaction Examples

Various interactions with Large Language Models (LLMs) beyond simple chatbots.

## Setup

1.  **Install uv:**
    ```shell
    curl -LsSf https://astral.sh/uv/install.sh | sh
    ```

2.  **Create a virtual environment and install dependencies:**
    ```shell
    uv venv .venv
    source .venv/bin/activate
    uv add tiktoken langchain langchain-openai langchain-ollama python-dotenv
    ```

3.  **Set your OpenAI API key:**
    ```shell
    export OPENAI_API_KEY='your_api_key_here'
    ```

## Features Demonstrated

The `sma.ipynb` notebook covers the following examples:

*   **Tokenization:** Understanding how text is tokenized using `tiktoken`.
*   **LLM Interaction:**
    *   Querying the OpenAI API (`gpt-4o`).
    *   Running local models with Ollama (`gemma3:1b`).
*   **Advanced Use Cases:**
    *   Image generation based on a text prompt.
    *   Image analysis and description.
    *   Structured data extraction (JSON) from unstructured text for useful analysis.
