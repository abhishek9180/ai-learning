# 🧠 Local AI Assistant (RAG + Agents + Memory)

A fully local AI assistant built from scratch using Python, implementing:

* 🔍 Retrieval-Augmented Generation (RAG)
* 🤖 Agent-based tool usage
* 🧠 Memory (context-aware conversations)

> ⚡ Runs locally using open-source models (no paid APIs required)

---

# 🚀 Features

* ✅ Chat with AI using local LLM
* ✅ Ask questions based on your own data (RAG)
* ✅ AI can use tools (calculator, time, etc.)
* ✅ Maintains conversation memory
* ✅ Built without heavy frameworks (pure understanding-first approach)

---

# 🏗 Architecture

```
User Query
   ↓
Memory (context)
   ↓
RAG (retrieve knowledge)
   ↓
Agent Decision (tool or answer)
   ↓
Final Response
```

---

# 📂 Project Structure

```
ai-learning/
│
├── notebooks/
│   ├── 01_basic_chat.ipynb
│   ├── 02_prompt_engineering.ipynb
│   ├── 03_embeddings_vector_search.ipynb
│   ├── 04_rag_system.ipynb
│   ├── 05_agents_tool_usage.ipynb
│   ├── 06_memory_context.ipynb
│   └── 07_full_ai_system.ipynb
│
├── requirements.txt
└── README.md
```

---

# ⚙️ Prerequisites

Make sure you have:

* macOS / Linux / Windows
* Python 3.10+
* 8GB RAM recommended (for local models)

---

# 🧱 Step 1: Clone Repository

```
git clone https://github.com/your-username/ai-learning.git
cd ai-learning
```

---

# 🐍 Step 2: Create Virtual Environment

```
python3 -m venv venv
source venv/bin/activate      # Mac/Linux

# Windows
venv\Scripts\activate
```

---

# 📦 Step 3: Install Dependencies

Create a `requirements.txt` file:

```
jupyter
requests
sentence-transformers
faiss-cpu
numpy
```

Then install:

```
pip install -r requirements.txt
```

---

# 🤖 Step 4: Install Local LLM Runtime

Install **Ollama**:

```
brew install ollama        # Mac

# Linux:
curl -fsSL https://ollama.com/install.sh | sh
```

Start Ollama:

```
ollama serve
```

---

# 🧠 Step 5: Download Model

```
ollama pull mistral
```

👉 For low-memory systems:

```
ollama pull phi
```

---

# 📓 Step 6: Run Jupyter Notebook

```
jupyter notebook
```

Open:

```
notebooks/07_full_ai_system.ipynb
```

Run all cells and start chatting 🎉

---

# 💬 Example Usage

```
You:
> What is RAG?

AI:
RAG stands for Retrieval-Augmented Generation...
```

---

# 🧪 Development Flow

This project is built step-by-step:

| Module | Description                |
| ------ | -------------------------- |
| 01     | Basic LLM chat             |
| 02     | Prompt engineering         |
| 03     | Embeddings & vector search |
| 04     | RAG system                 |
| 05     | Agents (tool usage)        |
| 06     | Memory                     |
| 07     | Full AI system             |

---

# ⚠️ Known Limitations

* Local models may be slower
* Tool selection may not always be accurate
* Memory is limited (sliding window)
* No UI (CLI-based interaction)

---

# 🔥 Future Improvements

* Add Streamlit UI
* Improve RAG with chunking + better retrieval
* Add persistent memory (database)
* Multi-step agent reasoning
* API deployment

---

# 🧑‍💻 Tech Stack

* Python
* Ollama (local LLM runtime)
* Sentence Transformers (embeddings)
* FAISS (vector search)
* Jupyter Notebook

---

# 🙌 Contributing

Feel free to fork and improve the project.

---

# 📜 License

MIT License

---

# ⭐ Acknowledgement

Built as part of a hands-on journey to understand AI systems from scratch without relying heavily on frameworks.

---

# 💡 Author

Abhishek Jha
Senior Software Developer → AI Builder 🚀
