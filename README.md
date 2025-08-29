# 📚 RAG Document Q&A with Groq + Llama3 + HuggingFace Embeddings

This project is a **Retrieval-Augmented Generation (RAG) app** where you can ask questions about your PDFs.  
It uses:
- [Streamlit](https://streamlit.io/) → Web UI  
- [LangChain](https://www.langchain.com/) → Document loading, splitting, retrieval  
- [FAISS](https://github.com/facebookresearch/faiss) → Vector database  
- [HuggingFace](https://huggingface.co/) → Embeddings (`all-MiniLM-L6-v2`)  
- [Groq](https://groq.com/) → Llama3 inference  

---

## ⚙️ Setup

### 1. Clone & Create Environment
```bash
git clone https://github.com/yourusername/rag-groq-hf.git
cd rag-groq-hf

# Create virtual environment
python -m venv venv
venv\Scripts\activate     # On Windows
# or
source venv/bin/activate  # On Linux/Mac

