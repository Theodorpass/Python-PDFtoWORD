# Python-PDFtoWORD


This script extracts both text and images from a PDF file and converts the content into a Word document. It uses the **PyMuPDF** library to extract the text and images from the PDF and **python-docx** to create and save the Word document. The script supports handling images within the PDF, which are inserted into the Word document, alongside the extracted text.

## Requirements

To run this script, you need to install the following Python libraries:

```bash
pip install -r requirements.txt
```

1)   Clone or download this repository to your local machine.
git clone https://github.com/Theodorpass/PDF-to-Word.git


2)   Navigate to the project folder:
cd \Filepath\ PDF-to-Word


3) Install the required dependencies:

pip install -r requirements.txt


4)   Open the pdf_to_word.py script and modify the pdf_file and word_file paths to your specific files:
  pdf_file = r'C:\path\to\your\input.pdf'  # Replace with your input PDF file path
  word_file = r'C:\path\to\your\output.docx'  # Replace with your desired output Word file path


5)   Run the script:
    python pdf_to_word.py
