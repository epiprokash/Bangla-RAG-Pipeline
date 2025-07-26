# 📚 Multilingual RAG System (Bangla + English)

This project implements a **Multilingual Retrieval-Augmented Generation (RAG) System** that can understand queries in both **Bangla** and **English**, retrieve relevant context from a Bengali textbook (PDF), and generate grounded answers.

---

## ✅ Objective

To build a lightweight and accurate RAG system that:
- Accepts user queries in Bangla and English
- Extracts relevant information from a PDF-based Bangla book (`HSC26 Bangla 1st Paper`)
- Generates accurate answers grounded in retrieved knowledge

---

## 🚀 Setup Instructions

### 🔧 Step 1: Environment Setup

```bash
# OCR and PDF processing
!apt-get install -y poppler-utils tesseract-ocr tesseract-ocr-ben

# Python Libraries
!pip install pdf2image pytesseract
!pip install transformers sentence-transformers faiss-cpu nltk torch sacremoses
