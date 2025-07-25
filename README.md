# AI-Chatbot2-by-Samiksha

# 🤖 AI-Powered Chatbot Using ChatGPT & n8n

This project is a **simple AI assistant** built using no-code automation tools. It connects **n8n**, **ChatGPT (OpenAI)**, and **Google Sheets** to automatically answer common questions based on structured data.

---

## 🧰 Tech Stack
- 🧠 **ChatGPT (OpenAI)** – For generating natural, conversational responses
- 🔗 **Google Sheets** – Data source for storing structured information
- ⚙️ **n8n** – No-code platform for building and managing the workflow

---

## 💡 What It Does
- Answers questions like:
  - *“What is the phone number from the sheet?”*
  - *“What is the status of this activity?”*
- Pulls data from Google Sheets and returns a **human-like AI response** without writing backend code.

---

## ⚙️ How It Works
1. A **Webhook** or **HTTP Request** node in n8n receives the user’s query.  
2. The **Google Sheets** node searches for the relevant data row based on keywords.  
3. The result is passed to **ChatGPT**, which uses a prompt like:  
   *“Use this data row to answer the user’s question clearly and helpfully.”*  
4. ChatGPT processes the data and generates a natural response.

---
