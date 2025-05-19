# 🤖 RAG-Based LLM AI Chatbot

A powerful Streamlit-based application designed to simplify document management by leveraging advanced machine learning and language models. The chatbot supports document upload, embedding generation, and interactive conversations, offering an intuitive and efficient user experience. 🚀

---

## 📌 Table of Contents

* [Features](#features)
* [Tech Stack](#tech-stack)
* [Getting Started](#getting-started)
* [Installation](#installation)
* [Running the App](#running-the-app)
* [Contributing](#contributing)
* [Useful Links](#useful-links)

---

## ✨ Features

* **📂 Upload Documents:** Easily upload and preview your PDF files directly within the app.
* **🧠 Create Embeddings:** Generate high-quality embeddings for efficient document retrieval.
* **🤖 Chatbot Interface:** Seamlessly interact with documents using an intelligent chatbot, powered by RAG (Retrieval-Augmented Generation) techniques.
* **🌟 User-Friendly Interface:** A sleek and responsive UI with a modern design for an enhanced user experience.
* **📧 Contact:** Easily reach out to the developer or contribute to the project on GitHub.

---

## 🛠️ Tech Stack

The Document Buddy App leverages state-of-the-art technologies to deliver efficient document management and chatbot interactions:

* **LangChain:** Orchestrates interactions between embedding generation, vector storage, and chatbot processing.
* **Unstructured:** Facilitates robust PDF text extraction and preprocessing.
* **BGE Embeddings (HuggingFace):** Generates semantic embeddings for efficient information retrieval.
* **Qdrant:** A local vector database running via Docker, enabling fast and scalable embedding storage and retrieval.
* **LLaMA 3.2 via Ollama:** Serves as the local language model to power chatbot responses, ensuring contextual and intelligent outputs.
* **Streamlit:** Builds the interactive web application, allowing users to upload documents, create embeddings, and chat seamlessly.

---

## 🚀 Getting Started

Follow these instructions to set up and run the Document Buddy App on your local machine.

### Clone the Repository

```bash
git clone https://github.com/dev28616/RAG-Based-LLM-Chatbot.git
cd RAG-Based-LLM-Chatbot
```

### Create a Virtual Environment

**Option 1: Using venv**

* **Windows:**

  ```bash
  python -m venv venv
  venv\Scripts\activate
  ```

* **macOS and Linux:**

  ```bash
  python3 -m venv venv
  source venv/bin/activate
  ```

**Option 2: Using Anaconda**

* **Create the environment:**

  ```bash
  conda create --name Chatbot python=3.10
  conda activate Chatbot
  ```

---

## 💾 Installation

Install the required dependencies:

```bash
pip install -r requirements.txt
```

---

## 🏃 Running the App

Start the Streamlit application:

```bash
streamlit run new.py
```

If your main file has a different name (e.g., `app.py`), replace `new.py` accordingly.
Access the application via:

```
http://localhost:8501
```

---

## 🤝 Contributing

Your contributions are highly valued! To get involved:

1. **Fork the repository.**
2. **Clone your fork:**

   ```bash
   git clone https://github.com/dev28616/RAG-Based-LLM-Chatbot.git
   cd RAG-Based-LLM-Chatbot
   ```
3. **Create a new branch:**

   ```bash
   git checkout -b feature/YourFeatureName
   ```
4. **Make your changes and commit:**

   ```bash
   git commit -m "Add Your Feature Description"
   ```
5. **Push your changes:**

   ```bash
   git push origin feature/YourFeatureName
   ```
6. **Open a Pull Request** from your fork to the original repository.

---

## 🔗 Useful Links

* [Streamlit Documentation](https://docs.streamlit.io/)
* [LangChain Documentation](https://langchain.readthedocs.io/)
* [Qdrant Documentation](https://qdrant.tech/documentation/)
* [ChatOllama Documentation](https://github.com/langchain-ai/langchain-llms#ollama)
