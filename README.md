
# ChatCEA Notebook

This notebook contains code for processing documents, performing retrieval tasks using LangChain, and interacting with external tools such as Nougat. The goal is to process and store documents, which can then be retrieved for analysis using various search strategies.

## Sections

1. **Introduction and Setup**: Setting up the environment and API keys.
2. **Import Libraries**: Loading necessary libraries for document processing and API interactions.
3. **Define Helper Functions**: Functions for running external tools and processing tasks.
4. **Initialize Vector Stores and Retrieval Systems**: Setup of vector stores and search systems for document retrieval.
5. **Document Ingestion and Processing**: Functions for loading and adding documents to the system.
6. **Running Retrieval and Analysis**: Executing the retrieval tasks and analyzing results.

## Dependencies

To run this notebook, you will need the following Python packages:

```bash
pip install BCEmbedding PyPDF2 concurrent.futures langchain.document_loaders langchain.retrievers langchain.retrievers.multi_vector langchain.storage langchain.text_splitter langchain_community.chat_models langchain_community.vectorstores langchain_core.documents langchain_core.output_parsers langchain_core.prompts langchain_core.runnables langchain_openai os ragas ragas.llms.base ragas.metrics subprocess time tqdm uuid
```

## Usage

1. Ensure that you have set up the required API keys for OpenAI and other necessary services.
2. Run each cell to process documents and execute retrieval tasks.
