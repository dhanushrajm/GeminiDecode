# GeminiDecode: Multilanguage Document Extraction by Gemini Pro

## Overview

GeminiDecode is an AI-powered application designed for multilingual document extraction. Leveraging the capabilities of Google Gemini Pro, this project enables users to upload images of documents in various languages and receive structured information about the content, including invoices and other vital details.

## Features

- **Multilingual Support**: Extracts information from documents in different languages, including German and French.
- **AI-Powered Responses**: Utilizes Google Gemini Pro for intelligent interpretation of document content.
- **User-Friendly Interface**: Built with Streamlit for a seamless user experience.
- **Image Upload**: Allows users to upload document images for analysis.

## Technologies Used

- [Streamlit](https://streamlit.io/) - Framework for building the web application.
- [Google Generative AI](https://ai.google.com/products/gemini) - For accessing the GenerativeAI API.
- [python-dotenv](https://pypi.org/project/python-dotenv/) - For managing environment variables.
- [Pillow](https://pillow.readthedocs.io/en/stable/) - For image processing.
- [PyPDF2](https://pypi.org/project/PyPDF2/) - For PDF manipulation (if needed).
- [LangChain](https://python.langchain.com/) - For chaining together various components in the application.

## Installation

To set up the project locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/dhanushrajm/GeminiDecode.git
   cd GeminiDecode

## Required Libraries

1. Open a terminal and run this:
   ```bash
   pip install -r requirements.txt

## Generate a Google API key

- [Google API Key](https://ai.google.dev/gemini-api/docs/api-key) - For Generating the API Key.

## Run the app.py 

1. Open a terminal and run this to launch the application:
   ```bash
   streamlit run app.py

2. Open your browser and go to http://localhost:8501.

3. Upload a document image and provide a prompt to extract information.

