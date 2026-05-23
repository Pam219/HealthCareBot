# Personal Healthcare Assistant AI 🩺🤖

An intelligent AI-powered healthcare chatbot that combines **Large Language Models (LLMs)**, **Retrieval-Augmented Generation (RAG)**, **Machine Learning**, and **Personalized Memory Systems** to provide healthcare guidance, disease prediction, medicine recommendations, and personalized health assistance.

Built using:
- LangChain
- LlamaIndex
- FastAPI
- Foundation LLMs (Gemini/Groq/OpenAI/Ollama)
- Vector Databases
- Machine Learning

---

# 📌 Project Overview

This project aims to build a **Personal Healthcare Assistant** capable of:

- Conversational healthcare support
- Disease prediction from symptoms
- Personalized health recommendations
- Medicine suggestions
- Health history memory
- Retrieval from medical datasets
- Context-aware healthcare conversations
- Long-term patient memory using vector databases

The chatbot evolves phase by phase from a simple LLM chatbot into a fully personalized AI healthcare assistant.

---

# 🚀 Features

## ✅ Current Features
- LLM-powered chatbot
- LangChain integration
- Prompt-based healthcare assistant
- FastAPI backend
- Basic conversational AI

---

## 🔜 Upcoming Features
- RAG-based medical knowledge retrieval
- Vector database integration
- Personalized patient memory
- Disease prediction models
- Heart disease prediction
- Diabetes prediction
- Medicine recommendation system
- Health history tracking
- Symptom analysis
- Healthcare document indexing
- Doctor recommendation system
- Medication reminders
- Agentic AI workflows

---

# 🧠 Tech Stack

## Backend
- Python
- FastAPI

## AI/LLM Frameworks
- LangChain
- LlamaIndex

## Foundation Models
- Gemini
- Groq
- OpenAI
- Ollama
- Llama 3
- Mistral

## Vector Databases
- FAISS
- ChromaDB
- Pinecone (future)

## Machine Learning
- Scikit-learn
- TensorFlow/Keras
- Pandas
- NumPy

---

# 🏗️ Project Architecture

```text
User Input
    ↓
Frontend / API
    ↓
FastAPI Backend
    ↓
LangChain Workflow
    ↓
Prompt Templates
    ↓
Foundation LLM
    ↓
Healthcare Response
```

---

# 🔮 Future Architecture

```text
User Query
    ↓
LangChain Agent
    ↓
Memory Retrieval
    ↓
Vector Database
    ↓
Medical Knowledge Base
    ↓
ML Disease Prediction
    ↓
LLM Reasoning
    ↓
Personalized Healthcare Response
```

---

# 📂 Project Structure

```text
healthcare-chatbot/
│
├── app.py
├── requirements.txt
├── .env
│
├── chatbot/
│   ├── llm.py
│   ├── prompts.py
│   ├── chains.py
│   └── chatbot.py
│
├── data/
│
├── vectorstore/
│
├── models/
│
├── frontend/
│
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/healthcare-chatbot.git
cd healthcare-chatbot
```

---

## 2️⃣ Create Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux/Mac

```bash
python3 -m venv venv
source venv/bin/activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install langchain
pip install llama-index
pip install fastapi uvicorn
pip install python-dotenv
pip install groq
```

---

# 🔑 Environment Variables

Create a `.env` file:

```env
GROQ_API_KEY=your_api_key
OPENAI_API_KEY=your_api_key
GOOGLE_API_KEY=your_api_key
```

---

# ▶️ Running the Application

## Start FastAPI Server

```bash
uvicorn app:app --reload
```

Server will run at:

```text
http://127.0.0.1:8000
```

---

# 💬 Example API Request

## Endpoint

```http
POST /chat
```

## Request

```json
{
  "message": "I have headache and fever"
}
```

## Response

```json
{
  "response": "Possible causes may include viral infection, flu, or dehydration..."
}
```

---

# 🧩 LangChain + LlamaIndex Usage

## Why LangChain?
Used for:
- Prompt management
- Chains
- Memory systems
- Agent workflows
- Tool calling

---

## Why LlamaIndex?
Used for:
- Document ingestion
- Medical knowledge indexing
- Retrieval systems
- RAG pipelines
- Semantic search

---

# 🧠 Planned AI Workflow

```text
Symptoms
    ↓
Disease Prediction Model
    ↓
Medical Knowledge Retrieval
    ↓
LLM Explanation
    ↓
Personalized Recommendations
```

---

# 📊 Datasets Used

Planned datasets include:
- Disease symptom datasets
- Medicine datasets
- Healthcare recommendation datasets
- Lifestyle datasets
- Fitness tracking datasets

---

# 🧬 Future Personalization Features

The chatbot will later store:
- Previous symptoms
- Medical history
- Allergies
- Lifestyle data
- Medicines
- Chronic diseases
- Family history

This allows:
- Personalized recommendations
- Context-aware healthcare advice
- Long-term health tracking

---

# ⚠️ Disclaimer

This project is intended for:
- Educational purposes
- Research purposes
- AI experimentation

It is **NOT** a replacement for professional medical advice, diagnosis, or treatment.

Always consult qualified healthcare professionals for medical concerns.

---

# 🎯 Learning Goals of This Project

This project helps in learning:
- LLM applications
- RAG systems
- Vector databases
- AI agents
- Prompt engineering
- LangChain
- LlamaIndex
- ML model integration
- Healthcare AI systems
- Memory architectures

---

# 📌 Future Improvements

- Multi-agent AI system
- Voice assistant integration
- OCR for medical reports
- Medical image analysis
- Wearable device integration
- Emergency alert systems
- Real-time health monitoring
- Fine-tuned healthcare LLM
- Mobile application

---

# 🤝 Contributing

Contributions, ideas, and suggestions are welcome.

Feel free to fork the repository and submit pull requests.

---


# 👩‍💻 Author

**Meher Mulani**   
AI/ML & Healthcare AI Enthusiast

---

# ⭐ Project Vision

To create an intelligent AI healthcare assistant capable of:
- Understanding user health conditions
- Learning from previous interactions
- Retrieving medical knowledge intelligently
- Providing personalized healthcare guidance
- Assisting users in maintaining healthier li