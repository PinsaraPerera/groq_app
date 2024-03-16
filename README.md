# Groq Simple Chat App

Groq Simple Chat App is a simple chat application created using Streamlit. It utilizes a large language model (LLM) to generate responses to user input.

## Features

- Real-time user input and LLM-generated responses
- Simple and intuitive user interface
- Customizable LLM parameters

## Getting Started

To run the Groq Simple Chat App, follow these steps:

1. Clone the repository:

```
git clone https://github.com/PinsaraPerera/groq_app.git
```

2. Navigate to the project directory:

```
cd groq_app
```

3. Install the required dependencies:

```
pip install -r requirements.txt
```

4. Run the Streamlit app:

```
streamlit run app.py
```

5. Interact with the chat application in your web browser.

## Customizing LLM Parameters

The LLM parameters can be customized by modifying the `params.json` file. The following parameters are available:

- `temperature`: Controls the randomness of the LLM's responses.
- `max_length`: Controls the maximum length of the LLM's responses.
- `top_k`: Controls the number of top candidates considered for the LLM's responses.
- `top_p`: Controls the cumulative probability of the top candidates considered for the LLM's responses.
