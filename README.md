# 🌿 Ayurbot: Personalized Ayurvedic Remedies with AI

Ayurbot is an AI-powered chatbot that delivers **personalized Ayurvedic home remedies** based on your unique body constitution (*Dosha*). It uses a **Retrieval-Augmented Generation (RAG)** pipeline to extract knowledge from authentic Ayurvedic texts, combining the power of **ancient healing** with **modern NLP**.

---

## 🧠 Features

### 🔍 Dosha Diagnosis
Take a quick, interactive **5-question quiz** to determine your Ayurvedic body type:  
**Vata**, **Pitta**, or **Kapha**.

### 📚 Knowledge Base
Ayurbot retrieves remedies from trusted Ayurvedic sources:

- *The Complete Book of Ayurvedic Home Remedies* – Dr. Vasant Lad  
- *Charaka Samhita* – Acharya Charaka & Dridhabala  
- *The Everyday Ayurveda Cookbook* – Kate O'Donnell, Cara Brostrom

### 🌿 Personalized Remedies
Based on your dosha, Ayurbot offers **natural home remedies** and suggestions for diet, lifestyle, and balance.

### 💬 Chat Interface
A sleek, modern **chat UI** with a calming **black-green herbal theme**, designed for intuitive interaction.

### ⚡ Fast & Accurate Search
Uses **FAISS** for high-speed semantic retrieval across embedded Ayurvedic content.

---

## 🛠️ Tech Stack

| Layer         | Tools Used                                                                 |
|---------------|-----------------------------------------------------------------------------|
| **Frontend**  | HTML, CSS *(custom black-green theme)*                                     |
| **Backend**   | Flask (Python)                                                              |
| **LLM**       | Mistral via Ollama                                                          |
| **Embeddings**| `all-MiniLM-L6-v2` (Hugging Face)                                           |
| **Vector DB** | FAISS (Facebook AI Similarity Search)                                       |
| **PDF Parsing** | PyMuPDF                                                                   |
| **Chunking**  | LangChain's `RecursiveCharacterTextSplitter`                                |
| **Prompting & RAG** | LangChain `RetrievalQA` for dynamic answer generation                |

---
**Screenshots**

#Portfolio Page

![image](https://github.com/user-attachments/assets/22d1e546-b171-4683-9b2d-e1a3a60121e6)

#Portfolio Page with button for quiz

![image](https://github.com/user-attachments/assets/b2ccae76-63f3-4885-8db1-53d37b47caf8)

#quiz page

![image](https://github.com/user-attachments/assets/5963cf59-612e-4812-9859-dd7095da8de9)
#chat page
![image](https://github.com/user-attachments/assets/4dcce4c6-25cc-45be-bc07-9f91aeaff623)




