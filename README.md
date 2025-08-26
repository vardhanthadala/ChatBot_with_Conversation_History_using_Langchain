# Building a Chatbot

This project demonstrates how to design and implement an **LLM-powered
chatbot** using [LangChain](https://www.langchain.com/). The chatbot can
have multi-turn conversations and remember previous interactions.

The notebook is structured as a **step-by-step tutorial** to help you
understand how conversational agents work. It covers: - Creating a
simple chatbot with an LLM. - Maintaining conversation history. - Using
message templates and prompts. - Loading environment variables (API
keys) securely.

------------------------------------------------------------------------

## Requirements

The notebook uses the following Python packages:

-   `langchain-core`
-   `langchain-community`
-   `python-dotenv`
-   `operator` (standard library)

Make sure you have a Python 3.9+ environment (recommended with `venv`).

------------------------------------------------------------------------

## Setup

1.  **Clone or download this project.**

2.  **Create and activate a virtual environment:**

    ``` bash
    python -m venv venv
    source venv/bin/activate      # Mac/Linux
    .\venv\Scripts\activate       # Windows
    ```

3.  **Install dependencies from `requirements.txt`:**

    ``` bash
    pip install -r requirements.txt
    ```

4.  **Set up environment variables:**

    Create a `.env` file in the project root and add your API keys.
    Example:

        OPENAI_API_KEY=your_api_key_here

------------------------------------------------------------------------

## Usage

1.  Launch Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

2.  Open the file:

        57399ddb-a02d-43c0-964e-f2e1f416b3be.ipynb

3.  Run the cells step by step to build and test the chatbot.

------------------------------------------------------------------------

## Notes

-   This tutorial focuses on **LLM-only conversations**.\
-   For more advanced concepts, check out:
    -   **Conversational RAG**: Integrating external data sources.
    -   **Agents**: Chatbots that can perform actions beyond
        conversation.
