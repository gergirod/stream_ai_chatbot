# AI Bot using Streamlit

This Streamlit application serves as an interface for an AI-powered chatbot. It integrates with OpenAI's language model to provide conversational responses based on user input.

## Features

- Users can engage in a conversation with the AI chatbot.
- Chat history is displayed in real-time.

## Requirements

- Python 3.7 or later
- Streamlit
- langchain_core
- langchain_openai

## Installation

1. **Clone this repository:**

    ```bash
    git clone https://github.com/your_username/your_repository.git
    cd your_repository
    ```

2. **Install the required dependencies:**

    ```bash
    pip install streamlit langchain-core langchain-openai python-dotenv
    ```

3. **Set up environment variables:**
    - Create a `.env` file in the root directory.
    - Add your OpenAI API key to the `.env` file:

    ```
    OPENAI_API_KEY=your_openai_api_key
    ```

4. **Run the Streamlit application:**

    ```bash
    streamlit run app.py
    ```

## How it Works

The application uses Streamlit for the user interface and integrates with various libraries for the AI functionalities:

- `langchain_core`: Provides message structures for human and AI messages, and output parsers.
- `langchain_openai`: Integrates with OpenAI's GPT models for language generation.
- `dotenv`: Loads environment variables, including the OpenAI API key.

The conversation history is stored in the Streamlit session state to maintain context between interactions.
