# 📚 Wikipedia RAG Application

A **Retrieval-Augmented Generation (RAG)** based application that answers user questions by retrieving relevant information from Wikipedia pages using **LlamaIndex**, **OpenAI**, and **Streamlit**.

---

## 🚀 Features

- Retrieves context from selected Wikipedia articles.
- Uses `llama-index` to build a **Vector Store Index**.
- Embeds data using OpenAI's `text-embedding-3-small`.
- Answers questions using OpenAI's `gpt-4o-mini` model.
- Built with an interactive **Streamlit UI**.

---

## 🧠 Technologies Used

- [Streamlit](https://streamlit.io/) – Web UI
- [LlamaIndex](https://www.llamaindex.ai/) – Indexing & RAG
- [OpenAI API](https://platform.openai.com/docs) – LLM and Embeddings
- [WikipediaReader](https://docs.llamaindex.ai/en/stable/api_reference/readers/integrations/WikipediaReader/) – Load data from Wikipedia
- [dotenv](https://pypi.org/project/python-dotenv/) – Environment variable management

---

## 📄 Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/wiki-rag-app.git
cd wiki-rag-app

