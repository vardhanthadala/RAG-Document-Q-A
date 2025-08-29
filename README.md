# 📚 RAG Document Q&A with Groq + Llama3 + HuggingFace Embeddings

This is a **Retrieval-Augmented Generation (RAG) app** built with:
- [Streamlit](https://streamlit.io/) → Web UI  
- [LangChain](https://www.langchain.com/) → Document loading, splitting, retrieval  
- [FAISS](https://github.com/facebookresearch/faiss) → Vector database  
- [HuggingFace](https://huggingface.co/) → Sentence embeddings  
- [Groq](https://groq.com/) → Llama3 inference  

You can **ask questions** about your PDFs, and the app will retrieve relevant chunks and answer using Groq’s Llama3 model.

---

## ⚙️ Setup

### 1. Clone & Install
```bash
git clone https://github.com/yourusername/rag-groq-hf.git
cd rag-groq-hf
python -m venv venv
venv\Scripts\activate    # On Windows
# or: source venv/bin/activate  (Linux/Mac)
pip install -r requirements.txt
