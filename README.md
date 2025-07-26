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

### 🔧 Step 1: **Install Python:** Download and install Python from [python.org](https://www.python.org/).

### 🔧 Step 2: **Clone the Repository:**
    ```bash
    git clone https://github.com/epiprokash/Bangla-RAG-Pipeline
    ```
### 🔧 Step 3: **Install Required Libraries:**
    ```bash
    pip install -r requirements.txt
    ```

## 🚀 Running the Pipeline

1. **Prepare Your Bangla pdf Corpus:** Create a pdf file (e.g., `bangla.pdf`) with the Bengali text you want to use.
2. **Extract the PDF text using OCR :**
    ```bash
    python OCR.py
    ```
3. **Run the RAG Pipeline using Extracted text**
     ```bash
    python RAG implementation.py
    ```
4. **Interact with the System:** Type your question and press Enter to get a response based on the retrieved information.
## Example

```bash
আপনার প্রশ্ন: কাকে অনুপমের ভাগ্য দেবতা বলে উল্লেখ করা হয়েছে?
উত্তর: মামাকে
```

