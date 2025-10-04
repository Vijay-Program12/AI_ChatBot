# 🤖 AI Chat Assistant

An interactive **AI Chat Assistant** built using **Streamlit**, **LangChain**, and **Azure OpenAI GPT-4**.  
This project allows users to have intelligent, real-time conversations with an AI model through a simple web interface.  

---

## 🧠 Overview

The AI Chat Assistant leverages the **Azure OpenAI API** to process natural language queries and return meaningful, context-aware responses.  
The chatbot is built with **Streamlit** for the frontend and **LangChain** for seamless integration with Azure’s GPT models.

---

## 📁 Project Structure

AI_Chat_Assistant/
│
├── .env # Stores Azure OpenAI credentials (not shared for security)
├── app.py # Main Streamlit application
├── requirements.txt # Python dependencies
└── README.md # Project documentation


---

## ⚙️ Features

- 💬 Real-time interactive chat interface  
- 🔐 Secure API key handling using `.env` file  
- 🧩 Integrated with **Azure OpenAI GPT-4**  
- 🎨 Custom UI styling with CSS inside Streamlit  
- 🔁 Maintains chat history during session  
- ⚡ Fast and responsive web app  

---

## 🧾 Requirements

Before running the app, ensure you have the following installed:

- Python 3.9 or higher  
- Azure OpenAI API access  
- Internet connection  

Install dependencies using:
```bash
pip install -r requirements.txt

## How to Run the Chatbot
Create a virtual environment:
python -m venv venv

Activate it:

Windows:
venv\Scripts\activate

Mac/Linux:
source venv/bin/activate

Install Dependencies:
pip install -r requirements.txt

Run the app:
streamlit run app.py

