# n8n project
🤖 AI Resume Analyzer (n8n + LLM)

🚀 Overview
An AI-powered workflow that analyzes resumes and provides structured feedback using Large Language Models (LLMs). Built using n8n for automation and API integration.
 🧠 Features
- Resume evaluation with AI
- Score generation (out of 10)
- Missing skills identification
- Actionable improvement suggestions
- Automated workflow execution

⚙️ Tech Stack
- n8n (Workflow Automation)
- OpenAI API (LLM)
- REST APIs
- JSON

🔄 Workflow
Webhook → Resume Input → AI Analysis → Output Response

📷 Screenshots
<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/ae3a30c4-7b80-4a8b-96ea-cd0630b8cfbb" />


🧪 How to Run
1. Import `workflow.json` into n8n
2. Add your OpenAI API key in HTTP node
3. Trigger webhook with resume input

## 📌 Sample Input
```json
{
  "resume_text": "Python, SQL, Power BI, basic AI knowledge"
}
