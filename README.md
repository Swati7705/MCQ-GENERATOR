# MCQ-GENERATOR
MCQ Generator is a Flask web app that creates multiple-choice questions from PDF, DOCX, or TXT files. It uses Google Gemini AI to generate questions with answer options and correct answers. Users can upload files, specify the number of questions, view results, and download them as TXT or PDF. It’s a useful tool for educators, students, and content creators to quickly generate quiz questions from study material.

---

Features

- Upload documents in PDF, DOCX, or TXT format
- Extracts content and generates MCQs using Google Gemini
- Displays MCQs in a styled, interactive interface
- Download questions as TXT or PDF files

---
Tech Stack

- **Backend:** Python, Flask
- **AI Integration:** Google Generative AI (`gemini-1.5-pro`)
- **PDF Handling:** `pdfplumber`, `fpdf`
- **DOCX Handling:** `python-docx`
- **Frontend:** HTML + Custom CSS

---

Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/mcq-generator.git
cd mcq-generator
