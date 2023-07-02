# Content-Creator-GPT



This is a Python application that allows you to ask questions about it using natural language. The application uses a LLM and OpenAI API to generate a content for any social media like YouTube about your topic.

## How it works

The "Content creator GPT" is an application that utilizes the OpenAI API and Laungchain GPT to generate content for social media platforms like YouTube. It incorporates user chat history and retrieves relevant data from Wikipedia. Built using Streamlit, the application allows users to enter their messages or topics, which are then processed by the OpenAI API to generate tailored content. The application maintains consistency by considering the user's previous chat messages and leverages information from Wikipedia to enhance the content generation process. The generated content is presented back to the user through the Streamlit interface, providing an efficient and personalized way to create engaging content for social media platforms.


## Installation

To install the repository, please clone this repository and install the requirements:

```
pip install -r requirements.txt
```

You will also need to add your OpenAI API key to the `.env` file.

## Usage

To use the application, run the `main.py` file with the streamlit CLI (after having installed streamlit): 

```
streamlit run app.py
```
