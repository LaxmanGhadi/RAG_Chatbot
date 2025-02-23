# RAG Chatbot

This repository contains a Retrieval-Augmented Generation (RAG) chatbot implementation using LangChain and ChromaDB. The chatbot is designed to retrieve relevant documents and generate responses using OpenAI's language models.
This chatbot is completely made using Google Colab .

## Features
- Retrieves relevant data from a dataset before generating responses.
- Utilizes ChromaDB as a vector database.
- Leverages LangChain for efficient document processing.
- Uses OpenAI's GPT models for response generation.

## Installation

Before running the chatbot, install the required dependencies:

```bash
pip install -U langchain-community
pip install langchain_openai
pip install unstructured
pip install chromadb
```

## Data Preparation
Ensure your dataset is placed in the `Data` folder. If the data needs to be downloaded, follow the instructions in the notebook to retrieve and store it properly.

## Usage
Run the Jupyter Notebook (`RAG_Chatbot.ipynb`) to execute the chatbot pipeline step by step.

## Repository Structure
```
├── Data/            # Folder for storing dataset files
├── RAG_Chatbot.ipynb  # Jupyter Notebook with chatbot implementation
├── README.md        # Project documentation
```

## License
This project is open-source and available under the MIT License.

## Acknowledgments
- [LangChain](https://github.com/hwchase17/langchain)
- [ChromaDB](https://github.com/chroma-core/chroma)

