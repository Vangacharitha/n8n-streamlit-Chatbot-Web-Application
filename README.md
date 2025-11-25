# 🤖 n8n + Streamlit ChatBot Web Application

A modern, AI-powered ChatBot Web Application built using **Streamlit (frontend)** and **n8n + Gemini AI (backend)**.  
The chatbot supports **context-aware conversations** using memory, providing intelligent and interactive responses similar to real AI assistants.

---

## 📸 Screenshots

### **ChatBot UI**
*(Chatbot App UI using Streamlit)*
<img width="1919" height="1022" alt="Interface of chatbot" src="https://github.com/user-attachments/assets/48a28cb9-5990-4607-ae13-3f588b4819b5" />


### **n8n Workflow**
*(Chatbot workflow snapshot)*

<img width="1919" height="922" alt="chatbot" src="https://github.com/user-attachments/assets/1fc83c6e-4e8a-44e5-9e1c-381dcfcd66fd" />

---

## 🚀 Features

- ⚡ Real-time chatbot UI built with **Streamlit**
- 🔗 Backend handled by **n8n Webhook + Gemini AI Agent**
- 🧠 Memory support for **context-aware conversations**
- 🎨 Clean chat interface with **user & bot icons**
- ⚙️ Fully customizable **system instructions**
- 🖥️ Runs locally using **VS Code**

---

## 🧩 How It Works

1. User sends a message from Streamlit.  
2. Streamlit sends the message to an **n8n Webhook**.  
3. The **n8n AI Agent (Gemini Model + Memory)** processes the conversation.  
4. n8n returns the output.  
5. Streamlit displays the formatted chatbot response.  

---
## 📁 Project Structure

├── chatbot_n8n_workflow.json # n8n workflow (Webhook + AI Agent)
├── Chatbot UI.png # Screenshot - Streamlit app
└── Chatbot workflow.png # Screenshot - n8n workflow




🛠️ Tech Stack


| Tool                    | Purpose                  |
| ----------------------- | ------------------------ |
| **Streamlit**           | Frontend UI              |
| **n8n**                 | Workflow automation      |
| **Gemini AI**           | Chat model for responses |
| **Simple Memory (n8n)** | Maintain context         |
| **VS Code**             | Development environment  |

