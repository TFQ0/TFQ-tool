# TFQ-tool  
**is a command-line utility for extracting text from various file formats, including text files, PDFs, Word documents, spreadsheets, and code files in popular programming languages.**  
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PyPI Version](https://img.shields.io/pypi/v/tfq-tool)](https://pypi.org/project/tfq-tool/)

![](https://via.placeholder.com/800x200.png?text=TFQ_tool+Demo) <!-- Add real screenshot later -->

## Features ✨
- 📂 **Multi-format support**: PDF, Word, Excel, TXT, and 8+ code formats
- ⚡ **Parallel processing**: Multi-threaded extraction for bulk operations
- 🛡️ **Robust error handling**: Clear error messages and file validation
- 📦 **Auto-output naming**: Generates organized output files/directories

## Installation 💻

### From PyPI (Recommended)




1. Download from pipx

     ```bash
     pipx install tfq-tool

1. Download from pip

   ```bash
   pip install tfq-tool




2. Used by repository
   ```bash
      git clone https://github.com/tfq0/TFQ-tool.git
      cd tfq-tool
      pip install -r requirements.txt
      python tfq-tool.py



3. Usage 🛠️

    ```bash

         "Basic Command"
          tfq-tool [FILES] [OPTIONS] 

         "Single file extraction" 
         tfq-tool document.pdf --output results.txt 

         "Batch processing with 4 threads"
         tfq-tool *.pdf *.docx --threads 4 --output ./extracted_texts


         "Force overwrite existing files"  
         tfq-tool data.xlsx --output output.txt --force



## Options⚙️


- **Flag	Description**
- -o, --output	Output path (file or directory)
- -t, --threads	Thread count (default: 1)
- -v, --verbose	Show detailed processing logs
- -f, --force  	Overwrite files without confirmation

