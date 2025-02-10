# Healthcare Assistant Chatbot

This is a simple AI-powered healthcare chatbot built using Streamlit and Hugging Face's `transformers` library. The chatbot provides basic responses to healthcare-related queries and can generate text-based answers using a pre-trained language model.

## Features
- Provides responses to common healthcare-related queries such as symptoms, appointments, and medications.
- Utilizes a pre-trained `distilgpt2` model for natural language processing.
- Simple and interactive user interface built with Streamlit.

## Installation
To set up and run the chatbot locally, follow these steps:

### Prerequisites
Make sure you have Python installed on your system.

### Clone the Repository
```bash
 git clone <your-repository-url>
 cd <your-repository-name>
```

### Install Dependencies
Use the following command to install all required dependencies:
```bash
 pip install -r requirements.txt
```

## Running the Chatbot
Run the following command to start the chatbot application:
```bash
streamlit run app.py
```

## Dependencies
The following dependencies are required for this project:
- `streamlit`
- `transformers`
- `tensorflow`
- `nltk`
- `tf-keras`

These dependencies are listed in the `requirements.txt` file.

## Usage
1. Launch the chatbot using `streamlit run app.py`.
2. Enter your query in the text input field.
3. Click the **Submit** button to receive a response from the chatbot.

## Contributing
If you wish to contribute to this project, feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Streamlit](https://streamlit.io/)
- [Hugging Face Transformers](https://huggingface.co/transformers/)
- [NLTK](https://www.nltk.org/)

