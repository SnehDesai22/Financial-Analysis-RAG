
# Intelligent Financial Analyst Chatbot using RAG and Machine Learning

## 📌 Project Overview
This project implements an **Intelligent Financial Analyst Chatbot** that leverages **Retrieval-Augmented Generation (RAG)** with Google's **Gemini LLM** to answer financial queries about Indian markets.  

## 🚀 Features
- **RAG Pipeline** for retrieving relevant financial data before generating responses.
- **Gemini LLM Integration** for intelligent and context-aware answers.
- **Indian Stock Market Focus** with historical and real-time data analysis.

## 🛠️ Tech Stack
- **Python 3.10+**
- **LangChain** for RAG pipeline
- **Gemini (Google LLM)** API for natural language processing
- **FAISS** for vector storage and retrieval

## 📂 Project Structure
```
Financial_analysis_RAG.ipynb   # Main Jupyter Notebook
data/                          # Contains historical stock data
models/                        # Saved ML models
README.md                      # Project Documentation
```

## ⚙️ Installation
```bash
git clone https://github.com/yourusername/financial-analysis-rag.git
cd financial-analysis-rag
pip install -r requirements.txt
```

## ▶️ Usage
1. Load the dataset.
2. Initialize the RAG pipeline with FAISS vector store.
3. Connect to the **Gemini LLM** API.
4. Ask financial questions in natural language.
5. Get intelligent answers enriched with historical and predictive data.

Example:
```python
query = "What is the projected growth of Reliance Industries for the next quarter?"
response = chatbot.ask(query)
print(response)
```

## 📊 Models Used
- **Vector Embeddings**: `sentence-transformers/all-mpnet-base-v2`
- **ML Model**: RandomForestRegressor (for price prediction)
- **RAG**: FAISS-based retriever + Gemini LLM

## 📌 Future Enhancements
- Integrate real-time stock market APIs.
- Add deep learning-based price forecasting.
- Improve retrieval accuracy with hybrid search.

## 📜 License
This project is licensed under the MIT License.
