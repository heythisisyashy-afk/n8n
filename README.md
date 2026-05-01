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
(Add workflow screenshot here)

🧪 How to Run
1. Import `workflow.json` into n8n
2. Add your OpenAI API key in HTTP node
3. Trigger webhook with resume input

## 📌 Sample Input
```json
{
  "resume_text": "Python, SQL, Power BI, basic AI knowledge"
}
