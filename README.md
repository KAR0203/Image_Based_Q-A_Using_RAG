# 🧠 Image-Based Q&A Using RAG

This project enables users to ask questions about the contents of an image using a **Retrieval-Augmented Generation (RAG)** approach. It combines vision and language models to understand image context and answer questions accordingly.

---

## 📌 Features

- 📸 Upload an image (JPG/PNG)
- 🧾 Generate a descriptive caption using **BLIP-2**
- ❓ Ask questions about the image
- 🤖 Use **Sentence Transformers** to match your question to the context
- 🧠 Generate answers using a **Large Language Model (LLM)**

---

## 🚀 How It Works

1. **Upload Image**: The image is processed to extract a caption.
2. **Generate Context**: The image caption is passed to a sentence transformer.
3. **Ask Questions**: User can ask questions about the image content.
4. **Answer Generated**: A large language model answers the question based on the caption.

---

## 📂 Files Included

- `Image_based_Q&A (2).ipynb` – Main Jupyter Notebook with code.
- `README.md` – Project documentation.

---

## 📦 Requirements

Install dependencies with:

```bash
pip install transformers sentence-transformers torch streamlit
