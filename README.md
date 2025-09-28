# Todoist AI Assistant ✅

[![Python](https://img.shields.io/badge/python-3.9+-blue)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![LangChain](https://img.shields.io/badge/LangChain-AI-orange)](https://www.langchain.com/)
[![Todoist](https://img.shields.io/badge/Todoist-API-red)](https://developer.todoist.com/)

**Author:** Bisista Shrestha  
**Date:** 2025-09-27  

---

## 🚀 Overview
The **Todoist AI Assistant** is a conversational agent that integrates **Google Gemini 2.5 LLM** (via LangChain) with the **Todoist API**.  
It allows you to **manage tasks naturally through chat**, enabling you to add tasks, view tasks, and interact with your Todoist account using simple language.

This agent is powered by:
- **LangChain Tools & AgentExecutor** – for tool orchestration.  
- **Google Gemini** – for natural language understanding and responses.  
- **Todoist API** – for task management (create, view tasks, etc.).  

---

## ✨ Features
- Add new tasks to your Todoist account via conversation.  
- View your current tasks in Todoist.  
- Maintains conversation history for contextual interactions.  
- Natural chat interface powered by **Gemini LLM**.  

---

## ⚙️ Installation

1. **Clone the repository**:    
git clone <repository_url>
cd <repository_folder>

2. Install dependencies:    
pip install -r requirements.txt

3. Set up environment variables:    
Create a .env file in the root folder and add:  
TODOIST_API_KEY=your_todoist_api_key_here
GEMINI_API_KEY=your_google_gemini_api_key_here  

---

## 💻 Usage     
Run the assistant from terminal:    
python main.py

Example conversation:   
You: Add a task to finish my math homework
AI: Task "finish my math homework" has been added to your Todoist.

You: Show my tasks
AI: Here are your current tasks:
- finish my math homework
- buy groceries
- complete project report   
Press CTRL+C to stop the agent.

---

## 📜 License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.

---

## 🔮 Notes

- Currently supports adding tasks and showing tasks.
- Can be extended with more Todoist features (update, complete, delete tasks).
- Uses Gemini LLM for natural language task parsing.

---

## 🚧 Future Improvements

Here’s what’s planned for upcoming versions:
- Complete tasks – mark tasks as done from chat.
- Delete tasks – remove tasks by name or ID.
- Deadlines & Reminders – allow users to set due dates and reminders via natural language.
- Priorities – let users assign priority levels to tasks.
- Labels & Projects – categorize tasks under specific Todoist projects and labels.
- Error Handling – improve reliability with better API error messages.
- Web/Gradio UI – add a simple front-end for non-terminal users.


