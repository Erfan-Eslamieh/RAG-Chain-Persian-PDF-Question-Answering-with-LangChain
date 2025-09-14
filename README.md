# 📌 RAG & Chain: Persian PDFs Question Answering with LangChain

## 📖 Overview
This repository demonstrates a **Retrieval-Augmented Generation (RAG)** pipeline combined with **Chain mechanisms** using the LangChain framework.  
The workflow integrates **Persian PDF documents** (downloaded from the Central Bank of Iran) into a vector store and enables **question answering** with accurate, context-driven results.

The project highlights:
- How to load, clean, and process Persian text from PDFs  
- How to build a **Vector Database (FAISS)**  
- How to combine **retrieval + generation** for better responses  
- How to structure reasoning with **Chains** in LangChain  

---

🧠 **Features**
- Automatic PDF download and parsing  
- Persian text cleaning & preprocessing  
- Chunking documents into embeddings  
- FAISS-based vector storage & retrieval  
- LangChain integration with OpenAI / LLMs  
- Chain workflow for structured reasoning  

---

📁 **File Structure**
- `RAG_and_Chain.ipynb` → Main notebook including:  
  - Library installation  
  - PDF download and parsing  
  - Text cleaning functions  
  - Vector store creation with FAISS  
  - RAG implementation with Chain-based QA  

---

🚀 **How to Use**

1. Clone the repository:
```bash
git clone https://github.com/Erfan-Eslamieh/RAG_and_Chain.git
```
2. Navigate to the folder:
```bash
cd RAG_and_Chain
```
3.pip install -r requirements.txt
```bash
pip install -r requirements.txt
```
Or install manually:
```bash 
pip install langchain langchain-openai langchain-community faiss-cpu PyPDF2 pypdf pymupdf pdfplumber requests
```
4.Run the notebook:
```bash
jupyter notebook RAG_and_Chain.ipynb
```

---

📚 **Workflow Overview**

✅ **Step 1: Data Loading**  
- PDFs are downloaded from the Central Bank of Iran and parsed into text.  

✅ **Step 2: Preprocessing**  
- Text is cleaned and normalized (extra spaces, punctuation issues, Persian-specific fixes).  

✅ **Step 3: Vectorization**  
- Text chunks are converted into embeddings and stored in FAISS vector database.  

✅ **Step 4: RAG Pipeline**  
- When a query is given, relevant chunks are retrieved and passed to the LLM.  

✅ **Step 5: Chaining**  
- A structured chain ensures step-by-step reasoning: retrieval → context integration → answer generation.  

---

✨ **Key Features & Benefits**  
- ✔ Persian language support (PDF parsing & cleaning)  
- ✔ End-to-end RAG workflow with LangChain  
- ✔ Chain-based reasoning for better answer accuracy  
- ✔ Practical hands-on notebook for real-world use cases  

---
## 👨‍💻 Author
**Erfan Eslamieh**  
M.Sc. in Cognitive Science – Specializing in Generative AI, Machine Learning, and Deep Learning  
📧 [erfan.cognitive.work@gmail.com]  
🔗 [![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/erfan-eslamieh) [![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=flat&logo=kaggle&logoColor=white)](https://www.kaggle.com/erfaneslamieh)
