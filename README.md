# Sparky Discord Bot

A Discord bot that uses RAG (Retrieval-Augmented Generation) via web scraping to provide specific answers about Arizona State University.

## Description:
    
This Discord bot uses the LangChain library to create a question-answering system.
It uses the Hugging Face Hub to download pre-trained models and embeddings,
and integrates with the Qdrant vector database for efficient search.
The bot also supports multi-step reasoning, allowing users to ask questions
that require multiple pieces of information from different sources. It also lists the citations used for the information

The bot also supports natural language inference (NLI) using the
Google Generative AI model. To use NLI, you must provide a
question and two options, and the bot will generate a third option
that is most likely to be the correct answer.

The current use for this bot is to provide answers to questions regarding arizona state university 

## Workflow

- The bot starts by connecting to the Qdrant vector database.
- It then retrieves relevant documents from the database using the ASU University's search terms.
- The bot uses the Hugging Face pipeline to generate answers based on the retrieved documents.
- If a user asks a question that requires multi-step reasoning, the bot will generate a series of answers, each based on the previous one.
- To handle natural language inference (NLI), the bot uses the Google Generative AI model.
- The bot is designed to handle a variety of questions related to ASU University, such as academic information, campus life, and student life.


## Features

- Uses LangChain library for question-answering capabilities
- Integrates with Hugging Face Hub for pre-trained models and embeddings
- Leverages Qdrant vector database for efficient search
- Supports multi-step reasoning for complex queries
- Provides citations for information sources
- Includes natural language inference using Google Generative AI
- Specializes in answering questions about Arizona State University

## Technical Stack

- LangChain for RAG implementation
- Hugging Face Hub integration
- Qdrant vector database
- Google Generative AI for NLI
- Discord.py for bot functionality

## Setup

1. Clone the repository
2. Install required dependencies
3. Configure environment variables
4. Run the bot using the provided Jupyter notebook

## Usage

The bot can be used in Discord servers to:
- Answer questions about ASU
- Provide multi-step reasoning for complex queries
- Generate natural language inferences
- Cite sources for provided information

## Development Status

This is a public repository with:
- Jupyter Notebook implementation
- 2 commits
- No releases published
- No packages published
- 0 stars and 0 forks

## License

Please refer to the repository for license information[1][2].

Citations:
[1] https://github.com/somwrks/Sparky-Discord-Bot
[2] https://github.com/somwrks/Sparky-Discord-Bot