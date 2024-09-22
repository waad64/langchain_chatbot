# Coco Chatbot

## Overview

This repository contains a chatbot application built using Streamlit and the LangChain framework, powered by OpenAI's API. The Coco chatbot is designed to facilitate interactive conversations and provide helpful responses based on the context of the chat history.

## Features

- **Interactive UI**: User-friendly interface built with Streamlit.
- **Contextual Conversations**: Maintains chat history for coherent interactions.
- **Real-time Responses**: Utilizes OpenAI's language model for instant replies.

## Prerequisites

- Python 3.7 or higher
- An OpenAI API key
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/waad64/langchain_chatbot.git
   cd langchain_chatbot
   ```

2. Install the required packages:

   ```bash
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:

   Create a `.env` file in the root directory and add your API key:

   ```plaintext
   OPENAI_API_KEY=your_openai_api_key
   ```

## Usage

Run the Streamlit application:

```bash
streamlit run app.py
```

Open your web browser and navigate to `http://localhost:8501` to interact with the chatbot.

## Code Explanation

- **Imports**: The code imports necessary libraries, including Streamlit, LangChain components, and environment variable management.
- **Environment Variables**: Loads the OpenAI API key from a `.env` file.
- **Chat History**: Uses Streamlit's session state to maintain chat history.
- **Response Generation**: Defines a function that constructs prompts and generates responses using OpenAI's language model.
- **User Interaction**: Handles user input and displays chat messages in the Streamlit interface.



