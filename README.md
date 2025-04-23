# 🧠 AI Medical Chatbot with RAG (Retrieval-Augmented Generation)

An intelligent medical chatbot designed to assist users with accurate, context-aware responses using Retrieval-Augmented Generation (RAG). The chatbot leverages Hugging Face Transformers for natural language processing, Faiss for efficient vector similarity search, and Mistral for conversational interactions, all presented through a clean Streamlit interface.

## 🚀 Features

- 🧬 **RAG Pipeline**: Combines document retrieval and generative models to provide accurate medical responses.
- 🔍 **Contextual Search**: Uses Faiss for fast and precise document retrieval from a medical knowledge base.
- 💬 **Conversational Interface**: Interactive chat UI built with Streamlit.
- 📚 **Custom Knowledge Base**: Medical documents or FAQs embedded for personalized responses.
- 🔗 **Modular Architecture**: Easy to expand or integrate with other AI services.

## 🛠️ Tech Stack

- **Frontend**: [Streamlit](https://streamlit.io/)
- **Backend**: Python
- **NLP Model**: Hugging Face Transformers (`sentence-transformers`, `mistral`)
- **Vector Database**: Faiss CPU
- **Embedding Models**: Sentence-BERT
- **RAG Components**: Custom retriever + generative response builder

## 💡 How It Works

1. **User Query** → Input through Streamlit UI
2. **Retriever** → Finds relevant documents using Faiss + Sentence-BERT
3. **Generator** → Mistral model generates response based on retrieved docs
4. **Output** → Displayed as human-like conversational reply



