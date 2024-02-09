# Multiple PDFs Q&A Application

This Streamlit application processes multiple PDF documents, extracts text, generates vector stores using FAISS (Facebook AI Similarity Search), and utilizes conversational AI for question-answering capabilities.

## Features

- **PDF Text Extraction:** Upload PDF files to extract text content.
- **Text Splitting:** Split extracted text into smaller chunks for vectorization.
- **Vectorization:** Generate FAISS vector stores from text chunks.
- **Conversational AI:** Ask questions based on the extracted text and receive answers.

## Requirements

- Python 3.10
- Streamlit
- PyPDF2
- FAISS
- All the required libraries are given requirements.txt file

## Installation

1. Clone the repository:

    ```vs code
    git clone https://github.com/MohanT3110/multiple-pdfs-qna.git
    ```

2. Make an venv environment:
    '''vs code
    Go to Terminal --> New Terminal --> Powershell to command prompt -->
    conda create -p venv python==3.10
    conda activate venv/
    pip install -r requirements.txt
    '''
3. Get your Google API Key from https://makersuite.google.com/app/apikey --> Select "Create API key in new project"
    copy the key and paste in .env file

## Usage

1. Run the Streamlit app:

    ```vs code
    Note: CTRL+Shift+P--> Select Interpreter, Select any conda interpreter

    Go to Terminal --> New Terminal --> Powershell to command prompt -->
    conda activate venv/
    streamlit run app.py
    ```

2. Access the app in your web browser at `http://localhost:8501`.

3. Use the sidebar to upload PDF documents.

4. Ask questions related to the uploaded PDFs in the provided text input field.

5. Click the 'Get Answer' button to retrieve answers based on the uploaded documents and asked questions.

## Folder Structure

- `app.py`: Main application file.
- `README.md`: Instructions and information about the application.
- `requirements.txt`: List of Python dependencies.

