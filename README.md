# PDF/TXT Knowledge-base QA using Chroma DB, LangChain, and Mistral LLM

This repository contains a demo jupyter that imports PDF / TXT documents, chunks them up, stores their embeddings in a database, and then allows users to prompt the database with questions to retrieve the most relevant documents. This is achieved through a combination of Chroma DB, LangChain, and Mistral LLM.

## Installation

1. Clone the repository:

    ```bash
    git clone git@github.com:Nico404/knowledge_QA.git
    ```

2. Install the required dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Configuration

- Ensure that you Mistral AI API key is set in the `MISTRAL_KEY` environment variable.
