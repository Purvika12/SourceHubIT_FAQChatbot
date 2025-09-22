# SourceHubIT_FAQChatbot
# 🤖 FAQ Chatbot Project

## 📍 Objective
The goal of this project is to build a **FAQ Chatbot** that can automatically answer frequently asked questions.  
This project was created as part of the **SourceHubIT Internship**.

The chatbot is implemented in **Google Colab** and provides a user-friendly interface using **Gradio**.

---

## ⚙️ How it Works
1. The chatbot stores a set of **predefined FAQs** (Question → Answer pairs).  
2. When a user asks a question, the chatbot:  
   - Matches it with stored FAQs  
   - Returns the correct answer instantly  
   - If not found, shows a fallback response  
3. The chatbot is accessible through a **Gradio chat interface**.

---

## 🛠️ Tech Stack
- **Python**  
- **Google Colab**  
- **Gradio** (for chat UI)  

---

## 🚀 Setup & Run (Google Colab)

1. Open Google Colab: [Google Colab](https://colab.research.google.com/)  
2. Create a new notebook and paste the code from this repository.  
3. Install Gradio:  
   ```bash
   !pip install gradio -q
