# PDF Tax Document Processor

A Python tool for extracting and processing tax withholding information (Bukti Potong PPh) from PDF documents. The script handles Indonesian tax documents (Bukti Potong PPh 22/23) with structured data extraction and cleaning.

## Features

- 📄 PDF text extraction using pdfplumber
- 🔍 Advanced text cleaning and formatting:
  - Merges separated characters/numbers
  - Handles special tax document formats
- 🏷️ Key data extraction:
  - Taxpayer NPWP and name
  - Tax type (PPh 22/23)
  - Withholding amounts
  - Document numbers and dates
- 📊 Data organization into structured Excel format
- 🛠️ Robust error handling for inconsistent document formats

## Requirements

- Python 3.7+
- Required packages:
  ```bash
  pip install pdfplumber pandas openpyxl
