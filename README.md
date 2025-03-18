# ML Toolkit

A collection of useful machine learning and AI utilities, tools, and experiments.

## Projects

### OCR Project

Tools for extracting text from PDF documents using Mistral AI's OCR capabilities.

#### Contents
- `ocr.ipynb`: Jupyter notebook demonstrating how to use Mistral AI's OCR API for both online (arXiv) and local PDF files
- `llm.txt`: Sample OCR output from a scientific paper (Evo 2 genome modeling paper)

#### Setup
1. Install the required packages:
   ```
   pip install -r requirements.txt
   ```
2. Create a `.env` file with your API keys:
   ```
   MISTRAL_API_KEY=your_api_key_here
   ```

#### Usage
The notebook demonstrates two main OCR approaches:
1. Processing PDFs directly from arXiv URLs
2. Processing local PDF files

### Future Projects

Additional machine learning and AI utilities will be added to this repository over time.

## General Setup

Each subproject may have its own dependencies. Common dependencies are listed in the main `requirements.txt` file.

## Contributing

Feel free to add new tools and utilities to this repository as needed.

## Note

The repository does not include any PDF files or API keys as they are excluded in the `.gitignore` file. 