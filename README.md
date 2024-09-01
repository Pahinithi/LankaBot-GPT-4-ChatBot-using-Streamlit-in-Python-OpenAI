# LankaBot - GPT-4 ChatBot using Streamlit

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Screenshots](#screenshots)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

**LankaBot** is an AI-powered chatbot built using OpenAI's GPT-4 and Streamlit. This application provides an interactive interface where users can communicate with the chatbot, which can assist with various tasks, answer questions, and engage in conversation. The chatbot maintains conversation history to create a seamless and natural user experience.

## Features

- **Real-time Interaction**: Engage in real-time conversations with the GPT-4 model.
- **Conversation History**: Keeps track of the chat history within the session.
- **User-Friendly Interface**: A responsive and clean UI developed with Streamlit.
- **Easy Configuration**: Simple setup to get the chatbot running.

## Installation

Follow these steps to install and run the LankaBot on your local machine:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Pahinithi/LankaBot-GPT-4-ChatBot-using-Streamlit-in-Python-OpenAI
    cd LankaBot-GPT-4-ChatBot-using-Streamlit
    ```

2. **Navigate to the `src` directory**:

    ```bash
    cd src
    ```

3. **Install the required dependencies**:

    Ensure you have Python installed. Then, run:

    ```bash
    pip install -r ../requirements.txt
    ```

## Usage

1. **Configure your OpenAI API key**:

    - Open the `config.json` file located in the `src` directory.
    - Replace `"your key"` with your actual OpenAI API key.

2. **Run the application**:

    ```bash
    streamlit run main.py
    ```

3. **Interact with LankaBot**:

    - Open the provided local URL in your web browser to start chatting with LankaBot.

## Configuration

- **API Key**: Store your OpenAI API key in the `config.json` file located in the `src` directory:

    ```json
    {
        "OPENAI_API_KEY": "your key"
    }
    ```

## Screenshots

<img width="1728" alt="LLM02" src="https://github.com/user-attachments/assets/1e013223-b21f-4ffe-8f48-c82365d93888">


## Project Structure

Here is an overview of the project structure:

```
LankaBot-GPT-4-ChatBot-using-Streamlit/
│
├── requirements.txt        # List of dependencies
├── src/
│   ├── config.json         # Configuration file for API keys
│   └── main.py             # Main application script
│
└── README.md               # Project README file
```

## Technologies Used

- **Python**: Core programming language used for the application.
- **Streamlit**: Framework for creating the web application interface.
- **OpenAI API**: Provides the GPT-4 model for natural language processing and interaction.

## License

This project is licensed under the MIT License.

## Acknowledgements

- [OpenAI](https://openai.com) for the GPT-4 API.
- [Streamlit](https://streamlit.io) for making it easy to build interactive web applications.

