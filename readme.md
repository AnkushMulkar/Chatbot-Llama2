# Chatbot using Llama 2

## Objective

The objective of this project is to create a chatbot using the Llama 2 language model powered by Replicate. The chatbot will be hosted on a Streamlit app and will interact with users in real-time, providing responses based on the input it receives. The chatbot aims to assist users by answering their queries effectively and efficiently.

## Techniques

The following techniques and tools are used in this project:

- **Streamlit**: A fast, open-source app framework for Machine Learning and Data Science projects.
- **Replicate**: A platform that allows you to version and iterate on machine learning models quickly.
- **Python**: The backend code for the app is written in Python, a popular programming language for web development and data science.
- **Llama 2 Language Models**: These are large language models that have been trained to generate human-like text based on the input they receive. Two versions are available: Llama2-7B and Llama2-13B.
- **Environment Variables**: To securely handle API tokens, they are stored as environment variables using `os.environ`.

## Features

- **Dynamic Model Selection**: Users can select between two Llama 2 models (7B and 13B) for different performance characteristics.
- **Adjustable Parameters**: Users can adjust parameters such as temperature, top_p, and max_length to influence the output of the language model.
- **Secure API Token Handling**: The Replicate API token is securely handled through Streamlit's secrets management and environment variables.
- **Interactive Chat Interface**: The Streamlit app offers an interactive chat interface where users can converse with the chatbot.
- **Chat History Management**: Users have the option to clear the chat history at any point.



## Conclusion

This Streamlit app leverages the power of Llama 2 language models to create an interactive chatbot. Users can have real-time conversations with the chatbot, with the flexibility to choose different models and adjust various parameters to tailor the chatbot's responses to their preferences. The app ensures secure handling of API tokens and provides a user-friendly interface for an engaging chat experience.
