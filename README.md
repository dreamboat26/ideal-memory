# Introduction

Welcome to the conversational chatbot repository utilizing HuggingFace's Zephyr 7B Alpha model. This README will guide you through setting up and utilizing the chatbot effectively.

## Overview

This chatbot is built using Zephyr 7B Alpha, which implements Direct Preference Optimization (DPO) for fine-tuning, resulting in superior conversational performance. It leverages various tools including Google Colab, ChromaDB, Langchain, and Gradio to create a seamless experience for engaging in conversations and extracting information from PDF documents.

## Features
- Effortless Conversation: Engage in conversations effortlessly with the chatbot powered by Zephyr 7B Alpha.
- Document Interaction: Upload PDF documents to Google Drive and seamlessly interact with their content through the chat interface.
- RAG Pipeline: Utilize the Retrieval Augmented Generation (RAG) pipeline for generating responses based on embedded document context.
- Gradio UI: Interact with the chatbot via an intuitive Gradio Chat UI, providing a user-friendly experience.

## Setup Instructions
Follow these steps to set up the chatbot environment and start conversing:
- Install Necessary Packages and Import Dependencies: Install required Python packages using pip and import necessary dependencies.
- Download the Model: Download the Zephyr-7B-Alpha model, preferably the sharded version for optimal performance.
- Connect Google Drive: Establish a connection between Google Drive and Google Colab to upload and access PDF documents.
- Upload Documents: Upload PDF files to a designated folder on Google Drive.
- Embed Documents in Vector Database: Load and segment documents into smaller text chunks, embedding them into Chroma DB using HuggingFace Embeddings and Langchain.
- Build RAG Pipeline: Construct a RAG pipeline using HuggingFace and Langchain.
- Create Gradio UI: Build a Gradio Chat UI and launch it, providing access to the chatbot in a new browser tab.

## Limitations
It's crucial to be aware of the following limitations when using the chatbot:
- Hallucinated Responses: The model may produce hallucinated responses, especially with domain-specific vocabulary.
- Response Times: Response times may vary, ranging from 15 to 30 seconds or longer.

## Tips for Usage
To optimize your experience with the chatbot, consider the following tips:
- If you encounter unusual or incomplete responses, adjust the prompt accordingly or append phrases like "explain," "explain in detail," or "elaborate."
- Keep in mind that while the responses may not be perfect, the chatbot adeptly extracts and abstracts information from provided context.

## Future Updates
In future updates, the following enhancements are planned:
- Integration of additional sources to the app for locating document chunks used by the model for generating responses.
- Continuous improvements to enhance conversational performance and reduce response times.

## Acknowledgments

Special thanks to HuggingFace for providing the Zephyr 7B Alpha model and the open-source community for developing the tools utilized in this project.

![3](https://github.com/dreamboat26/ideal-memory/assets/125608791/53dd289b-1472-45cd-b20a-4202c900fb9d)

![Capture](https://github.com/dreamboat26/ideal-memory/assets/125608791/fd0042d6-d99d-4b29-928b-b21e3fefda56)
