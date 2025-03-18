# OCR Project

This repository contains code for extracting text from PDF documents using Mistral AI's OCR capabilities.

## Contents

- `ocr.ipynb`: Jupyter notebook demonstrating how to use Mistral AI's OCR API for both online (arXiv) and local PDF files
- `llm.txt`: Sample OCR output from a scientific paper (Evo 2 genome modeling paper)

## Setup

1. Clone this repository
2. Install the required packages:
   ```
   pip install mistralai python-dotenv
   ```
3. Create a `.env` file with your Mistral API key:
   ```
   MISTRAL_API_KEY=your_api_key_here
   ```

## Usage

The notebook demonstrates two main OCR approaches:
1. Processing PDFs directly from arXiv URLs
2. Processing local PDF files

You can run the notebook cell by cell to see how the OCR process works and how to access the extracted text.

## Note

The repository does not include any PDF files or API keys as they are excluded in the `.gitignore` file. 