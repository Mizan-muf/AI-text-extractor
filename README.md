# AI-text-extractor
A Gemini Text extractor using the flash 1.5 model to extract from pdf to word file
This Python script uses **Gemini AI** (Google's generative model) to process a PDF file and output a well-formatted DOCX file. The content of the PDF is analyzed, with any spelling or grammar issues corrected, mathematical expressions and code snippets formatted, and the document organized with appropriate headings and subheadings. The script allows you to easily upload a PDF, process it, and save the results to a DOCX file with the help of a simple graphical user interface (GUI) for selecting input and output directories.

## Features
- **Spelling & Grammar Correction**: Automatically fixes any spelling and grammar issues in the text.
- **Formatting**: Ensures that the text is formatted for clarity and readability.
- **Mathematical Expressions & Code**: Recognizes and formats equations and code snippets with proper syntax highlighting.
- **Easy-to-use Interface**: Utilizes `tkinter` to select input PDF files and output folders.
- **Headings & Subheadings**: Organizes the content using docx headings to improve the structure.

## Prerequisites
Before you can use this script, make sure you have the following installed:
- Python 3.x
- Required Python packages:
  - `google-generativeai`
  - `docx`
  - `tkinter` (usually comes pre-installed with Python)

You can install the required dependencies by running the following command:

```bash
pip install google-generativeai python-docx
