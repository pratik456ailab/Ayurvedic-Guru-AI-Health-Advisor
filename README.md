# Ayurvedic Guru – AI Ayurvedic Health Advisor 🧘‍♂️🌿

A real-time AI chatbot that provides Ayurvedic health suggestions using n8n, Google Gemini, and a clean frontend built on Lovable App.

## 🚀 Architecture Overview

Frontend (Lovable App)
        |
        ↓
Webhook (n8n)
        |
        ↓
AI Agent (n8n)
        |
        ↓
Google Gemini Chat Model
        |
        ↓
Response Back to UI

--
<img width="1366" height="768" alt="Screenshot 2025-12-16 163908" src="https://github.com/user-attachments/assets/95427379-1abb-45ec-94c5-0d52f8934578" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 163925" src="https://github.com/user-attachments/assets/8280f662-5555-47cb-bcdb-89cbae342533" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 164314" src="https://github.com/user-attachments/assets/d86f1c51-c82b-460e-8ea6-c94e54508fd4" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 165122" src="https://github.com/user-attachments/assets/37e7d10a-c403-4e18-bc2c-f7ec5b74f91e" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 165145" src="https://github.com/user-attachments/assets/18b84102-460f-4caa-a05f-074daab4394c" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 165209" src="https://github.com/user-attachments/assets/511e9706-3121-4d65-b358-2c6849bcbe43" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 170052" src="https://github.com/user-attachments/assets/7317e39d-dd34-4f9f-aa2b-2d1620861432" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 170306" src="https://github.com/user-attachments/assets/10dafb81-88dc-45fa-91ff-86cba3b0deea" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 170336" src="https://github.com/user-attachments/assets/49db8704-0a2e-4fd5-afdd-c70744cb57c0" />
--
<img width="1366" height="768" alt="Screenshot 2025-12-16 170516" src="https://github.com/user-attachments/assets/2878cd45-2dea-4a6b-863a-6413e2a25633" />
--

## 🔧 Features

- Real-time conversational Ayurvedic guidance

- Webhook → AI Agent → Gemini Chat pipeline

- Domain-specific system prompts for safe Ayurvedic advice

- Automatic handling of user messages

- Live deployed frontend

- Zero backend code — fully automated through n8n
--
## 🧠 How It Works

- User sends a message from the Ayurvedic Guru UI.

- The message hits an n8n Webhook.

- The AI Agent prepares the structured prompt.

- The prompt is processed by Google Gemini Chat Model.

- The Ayurvedic-style response is returned to the UI.

--
## 🛠️ Tech Stack

- n8n Workflow Automation

- Google Gemini Chat Model

- Webhooks

- AI Agent Node

- Lovable App UI

- Prompt Engineering

--
## 📌 Use Cases

- Ayurvedic lifestyle guidance

- Natural remedy recommendations

- Health education bots

- Personalized wellness assistants











