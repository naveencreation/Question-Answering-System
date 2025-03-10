# 🚀 Question Answering System using NLP

This repository contains an implementation of a **Question Answering (QA) system** using **retrieval-based (BERT)** and **generative (FLAN-T5)** approaches. The system is built using **Python, Hugging Face Transformers, and Gradio** for an interactive UI.

---

## 📌 Features
✅ Uses **SQuAD dataset** for training and evaluation.  
✅ **Retrieval-based approach** using **DistilBERT** for extracting answers.  
✅ **Generative approach** using **FLAN-T5** for generating answers.  
✅ Implements a **Gradio-based web interface** for easy interaction.  
✅ Includes evaluation using **SQuAD metrics** for performance comparison.  

🔗 **Live Demo:** [Gradio Link] *(Replace with actual link)*  
📂 **Dataset:** [SQuAD](https://rajpurkar.github.io/SQuAD-explorer/)  
📜 **License:** MIT  

---

## ⚙️ Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/Question-Answering-System.git
cd Question-Answering-System
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Gradio UI
```bash
python app.py
```

---

## 📊 Model Details

### 📌 **Retrieval-Based Approach** (Extractive)
- Uses **DistilBERT** (`distilbert-base-cased-distilled-squad`)
- Extracts the most relevant answer from the provided context

### 📌 **Generative Approach** (Seq2Seq)
- Uses **FLAN-T5** (`google/flan-t5-small`)
- Generates answers based on context and question

---

## 🛠️ Evaluation
- Evaluated using **SQuAD metrics**
- Uses `evaluate` library for computing model performance

---

## 🖥️ Gradio UI
- Allows users to enter **questions & context**
- Provides both **retrieval-based** and **generative** answers

Example interface:
```
Enter your question: [__________]
Enter the context:  [__________]
[Generate Answer]

**Retrieval-Based Answer:** ...
**Generative Answer:** ...
```

---

## 💡 Future Improvements
🔹 Add support for multiple datasets (HotpotQA, Natural Questions)  
🔹 Fine-tune models for domain-specific QA tasks  
🔹 Improve UI with answer explanations & confidence scores  

---

## 🤝 Contributions
Feel free to **fork**, **raise issues**, or **submit PRs** to improve the system! 🚀  

---

## 📜 License
This project is licensed under the **MIT License**. You are free to use and modify it.  
