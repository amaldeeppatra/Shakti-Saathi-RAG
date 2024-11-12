# Shakti-RAG
- Generative AI Solution Supporting FAQs for Shakti Saathi Product

## Project Structure

This project is organized into several key files, each serving a specific purpose in the FastAPI application. Below is a breakdown of each file:

- **`main.py`**  
  The entry point of the FastAPI application. It defines the API routes and orchestrates the various components of the system, managing request handling and overall application flow.

- **`chroma_utils.py`**  
  Contains utility functions for interacting with the Chroma vector store. This includes operations for indexing documents and performing similarity searches, enabling efficient retrieval of related information.

- **`db_utils.py`**  
  Responsible for database operations, including storing and retrieving chat history and document metadata. This file abstracts database interactions to keep the main application code clean and maintainable.

- **`langchain_utils.py`**  
  Encapsulates the LangChain-specific logic, such as creating the Retrieval-Augmented Generation (RAG) chain and configuring the language model. This modularity makes it easier to update or modify language model settings.

- **`pydantic_models.py`**  
  Defines Pydantic models used for request and response validation, ensuring type safety and clear API contracts. These models standardize the data structure for API interactions.

- **`requirements.txt`**  
  Lists all the Python packages required for the project. This file enables easy setup of the environment by installing dependencies with a single command.
