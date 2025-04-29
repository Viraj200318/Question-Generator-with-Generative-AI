# Question-Generator-with-Generative-AI

This project is a **Python-based Jupyter Notebook application** that uses a Generative AI model to automatically generate interview questions. It currently supports topics including:

- Python
- C++
- Java
- Full Stack Development

## Features

- Generates up to 20 unique interview questions per topic
- Uses Generative AI for creativity and diversity in questions
- Easy to extend to new topics
- Jupyter Notebook interface for quick interaction

## Requirements

- Python 3.8 or above
- OpenAI API key (or equivalent for another supported AI provider)
- Here Generative AI is Gemini model (Gemini 2.0 Flash)

## Setup Instructions

1. **Clone this repository or download the notebook:**

2. **Set your API Key:**
import os
os.environ["OPENAI_API_KEY"] = "your-api-key-here"

You must set your OpenAI API key (or equivalent if using another model). You can do this by creating an environment variable or directly in the notebook.
