
# 📚 DeepRead CLI
> **Chat with your documents, privately and locally.**

DeepRead CLI is a high-performance RAG (Retrieval-Augmented Generation) tool that allows you to transform static PDF documents into an interactive local knowledge base. 

### ✨ Features
- 🔒 **100% Private:** No data ever leaves your machine. No OpenAI/Anthropic keys required.
- ⚡ **Optimized Inference:** Powered by Quantized Llama-3 (GGUF) for high-speed performance on standard CPUs.
- 📂 **Smart Ingestion:** Automatically chunks and embeds PDFs into a local vector store.
- 💻 **Dev-First CLI:** Clean, terminal-based interface for rapid document querying.

### 🛠️ Tech Stack
- **Language:** Python 3.10+
- **LLM:** Llama-3-8B (via `llama-cpp-python`)
- **Vector DB:** ChromaDB
- **Embeddings:** HuggingFace Sentence-Transformers
- **Orchestration:** LangChain
