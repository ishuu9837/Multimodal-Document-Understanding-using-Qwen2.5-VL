# 📄 Multimodal Document Understanding using Qwen2.5-VL

## Overview

This project is an end-to-end **Multimodal Document Understanding** application built using **Qwen2.5-VL**, **EasyOCR**, and **Gradio**. It enables users to upload document images and ask natural language questions about their contents. The application combines OCR-based text extraction with Vision-Language reasoning to provide accurate responses for various document types.

---

## Features

* Upload document images (`.jpg`, `.jpeg`, `.png`)
* OCR-based text extraction using EasyOCR
* Visual Question Answering (VQA) using Qwen2.5-VL
* Natural language interaction with documents
* Interactive Gradio web interface
* GPU-accelerated inference using PyTorch

---

## Tech Stack

* Python
* PyTorch
* Hugging Face Transformers
* Qwen2.5-VL
* EasyOCR
* Gradio
* Pillow

---

## Project Workflow

```
                Document Image
                       │
                       ▼
                Image Preprocessing
                       │
                       ▼
                 EasyOCR Extraction
                       │
                       ▼
           Image + User Question
                       │
                       ▼
          Qwen2.5-VL Vision-Language Model
                       │
                       ▼
             Natural Language Response
                       │
                       ▼
               Gradio Web Interface
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/multimodal-document-understanding.git
cd multimodal-document-understanding
```

Install the required packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Open the Google Colab notebook.
2. Enable **GPU** (`Runtime → Change runtime type → GPU`).
3. Add your Hugging Face token.
4. Run all notebook cells.
5. Upload a document image.
6. Ask questions about the uploaded document.

---

## Example Questions

* Summarize this document.
* What is the invoice number?
* Who is the customer?
* What is the total amount?
* What is the issue date?
* List the important information from this document.

---

## Sample Output

**Question**

```
What is the invoice number?
```

**Answer**

```
Invoice Number: INV-1045
```

---

## Repository Structure

```
Multimodal-Document-Understanding/
│
├── Multimodal_Document_Understanding.ipynb
├── README.md
├── requirements.txt
├── sample_documents/
└── outputs/
```

---

## Applications

* Invoice Understanding
* Receipt Analysis
* Document Summarization
* Visual Question Answering (VQA)
* OCR-assisted Information Retrieval
* Intelligent Document Processing

---

## Future Enhancements

* PDF document support
* Multi-page document analysis
* Structured information extraction
* Batch document processing
* Retrieval-Augmented Generation (RAG)
* Fine-tuning for domain-specific documents

---

## Learning Outcomes

This project demonstrates practical experience with:

* Vision-Language Models (VLMs)
* Multimodal AI
* Optical Character Recognition (OCR)
* Hugging Face Transformers
* GPU-based Deep Learning Inference
* Interactive AI Application Development

---

## Author

**Y. Eswar**

* GitHub: https://github.com/ishuu9837
* LinkedIn: https://linkedin.com/in/eswar854

---

## License

This project is intended for educational and research purposes.
