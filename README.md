# PDF Summarizer using LLaMA Model

This project is a Streamlit-based web application that allows users to upload a PDF document and generate a concise summary using the LLaMA model. It leverages `PyPDF2` for PDF text extraction and `transformers` from Hugging Face for text summarization.

## Features
- **PDF Upload**: Users can upload PDF files for text extraction.
- **Text Extraction**: Extracts and displays the content of the PDF.
- **Summarization**: Summarizes the extracted text using a pre-trained LLaMA model.
- **User-Friendly Interface**: Interactive and simple interface powered by Streamlit.

## Technologies Used
- **Streamlit**: For building the web interface.
- **PyPDF2**: For reading and extracting text from PDF files.
- **Transformers (Hugging Face)**: For tokenization and model loading.
- **LLaMA Model**: A pre-trained language model used for text summarization.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/pdf-summarizer.git
   cd pdf-summarizer
