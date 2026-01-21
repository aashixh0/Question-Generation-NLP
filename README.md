# **Accurate Question Generation using NLP, RAG, and Hugging Face**  

This project focuses on generating highly accurate and context-aware questions using **Natural Language Processing (NLP)**, **Retrieval-Augmented Generation (RAG)**, and **Hugging Face models**. It is designed to enhance automated question creation for educational purposes, quizzes, and knowledge assessment tools.  

## **Overview**  
The Question Generation system processes PDF documents and automatically generates contextually relevant questions using advanced language models and semantic search. It supports multiple languages including English, Hindi, and Sanskrit, making it versatile for diverse educational and domain-specific applications.

## **Key Features**  
- **Multi-Language Support** – Generate questions in English, Hindi, and Sanskrit with language-specific text processing.
- **Retrieval-Augmented Generation (RAG)** – Leverages semantic search to retrieve contextual knowledge, improving question relevance and accuracy.  
- **PDF Processing** – Efficiently extracts and processes text chunks from PDF documents while maintaining context.
- **Hugging Face Integration** – Uses state-of-the-art transformer models for precise and coherent question generation.  
- **Web Interface** – User-friendly Flask-based web application with file upload capabilities.
- **Custom Datasets** – Adaptable for various domains and knowledge areas.  

## **Technologies Used**  
- **Python** – Core programming language.
- **Flask** – Web application framework for user interface.
- **Hugging Face Transformers** – Advanced language models for question generation.
- **NLP Libraries** – For text processing and semantic understanding.  
- **Retrieval-Augmented Generation (RAG)** – Combines retrieval and generation for enhanced quality.
- **PDFPlumber** – PDF extraction and text processing.
- **Scikit-Learn** – Machine learning utilities for text processing.

## **Installation**  
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd NLP
   ```

2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

## **Usage**  
1. Open the web application in your browser.
2. Select your preferred language (English, Hindi, or Sanskrit).
3. Upload a PDF document.
4. Enter your prompt or question type preference.
5. The system generates contextually relevant questions based on the document content.

## **Project Structure**  
- `app.py` – Main Flask application and routing.
- `english_final.py` – English language question generation module.
- `hindi_final.py` – Hindi language question generation module.
- `sanskrit_final.py` – Sanskrit language question generation module.
- `requirements.txt` – Project dependencies.

## **How It Works**  
1. **PDF Processing** – Extracts and chunks text from uploaded PDF documents.
2. **Semantic Retrieval** – Uses RAG to search for contextually relevant information.
3. **Question Generation** – Generates accurate questions using language models conditioned on retrieved context.
4. **Language Processing** – Applies language-specific NLP techniques for optimal results.

This project aims to improve AI-driven question generation by combining retrieval and generation techniques, making it a valuable tool for education, automated assessment, and knowledge testing across multiple languages.
