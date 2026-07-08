# Langchain-Memory-Management

# README

This Colab notebook demonstrates how to use the `langchain-groq` library with the Groq API for conversational AI tasks. It explores different approaches to managing chat history and conversation flow.

## Contents:

1.  **Installation**: Installs necessary `langchain` and `langchain-groq` libraries.
2.  **API Key Setup**: Securely retrieves the Groq API key from Colab's secrets manager.
3.  **Basic Chat (Without Memory)**: Shows a simple chat interaction without maintaining conversation history.
4.  **Chat with Manual Memory Management**: Demonstrates how to manually append `HumanMessage` and `AIMessage` objects to a list to simulate conversation memory.
5.  **Chat with LangChain Memory Management**: Illustrates the use of `RunnableWithMessageHistory` from `langchain-core` to automatically manage conversation history for different users (sessions).

## How to Use:

*   **Set up Groq API Key**: Ensure you have a Groq API key and have added it to Colab's secrets manager under the name `GROQ_API_KEY`.
*   **Run Cells Sequentially**: Execute the cells in order to see the progression from simple, memoryless chat to more advanced memory management with LangChain.
