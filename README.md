# RAG-Demo-App-
# 🤖 RAG Demo: Vector Database + LLM (Streamlit + ChromaDB + SkillCaptain API)

A simple but powerful **Retrieval-Augmented Generation (RAG)** demo app built using  
**Streamlit**, **ChromaDB**, and the **SkillCaptain LLM API**.

This project shows how **Vector Databases** and **LLMs** can work together to deliver
context-aware and grounded AI responses — just like modern chatbots do internally (e.g., ChatGPT + memory).

---

## 🚀 Features

✅ **Add Knowledge Base:**  
Upload or write custom documents that are stored in ChromaDB vectors.

✅ **Vector Search:**  
Perform semantic similarity search to find the most relevant documents.

✅ **Ask Questions (RAG):**  
Use context from retrieved documents to generate more accurate and grounded responses.

✅ **Compare Responses:**  
See the difference between **RAG-based** and **Direct LLM** responses.

✅ **Streamlit UI:**  
Interactive, beginner-friendly, and clean interface for learning how RAG works.

---

## 🏗️ Tech Stack

| Component | Technology Used |
|------------|----------------|
| Frontend | [Streamlit](https://streamlit.io) |
| Backend | [Python 3](https://www.python.org) |
| Vector Database | [ChromaDB](https://www.trychroma.com) |
| LLM API | [SkillCaptain LLM Endpoint](https://skillcaptain.app) |
| Environment Management | [python-dotenv](https://pypi.org/project/python-dotenv/) |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/YourUsername/RAG-Vector-DB-LLM.git
cd RAG-Vector-DB-LLM


2️⃣ Create a virtual environment

python -m venv venv
venv\Scripts\activate     # on Windows      # PowerShell-           .\venv\Scripts\Activate.ps1

# OR
source venv/bin/activate  # on Mac/Linux


3️⃣ Install dependencies

pip install -r requirements.txt


4️⃣ Add your credentials in .env

SKILLCAPTAIN_USER_ID=your_user_id_here
SKILLCAPTAIN_JSESSIONID1=your_first_session_id
SKILLCAPTAIN_JSESSIONID2=your_second_session_id

🧩 Run the App

streamlit run app.py
