# 🤖 Business Intelligence AI Assistant

An AI-powered **Business Intelligence Assistant** that helps users understand business metrics, get data analysis guidance, generate report structures, and explore business insights using **Llama 3 locally through Ollama**.

The project combines a **Flask web application**, **prompt engineering**, and a **local Large Language Model (LLM)** to create an AI assistant without requiring a paid API key.

---

## ✨ Features

- 💬 AI-powered Business Intelligence chat assistant
- 📊 Business metrics and KPI explanations
- 🔍 Data analysis guidance
- 📝 Business report generation
- 📈 Visualization recommendations
- 💡 Potential business insights and trends
- 🎯 Task-specific prompt templates
- 🦙 Local Llama 3 integration through Ollama
- 🔐 No external API key required
- 🌐 Simple Flask-based web interface

---

## 🛠️ Technologies Used

| Technology    | Purpose                        |
| ------------- | ------------------------------- |
| 🐍 Python     | Application development         |
| 🌐 Flask      | Backend web framework           |
| 🦙 Ollama     | Local LLM runtime                |
| 🤖 Llama 3    | AI language model                |
| 🔗 Requests   | Communication with Ollama API    |
| 🌍 Flask-CORS | Cross-Origin Resource Sharing    |

---

## 🏗️ Project Structure

Business_intelligence_ai_assistant/
│
├── app_ollama.py
│
├── templates/
│ └── index.html
│
├── static/
│ └── Four-Types-of-Data-Analytics.jpeg
│
└── prompts/
├── analysis_guidance.txt
├── metric_explanation.txt
└── report_generation.txt


---

## 🧠 How the Application Works

The application follows a simple AI-assisted workflow:

        👤 User
          │
          ▼
   🌐 Flask Web Interface
          │
          ▼
   🔍 Task Detection
          │
   ┌──────┼──────────┐
   ▼      ▼          ▼
   Analysis Metrics Reports
Guidance Explanation Generation
│ │ │
└──────┼──────────┘
▼
📝 Prompt Template
│
▼
🦙 Ollama + Llama 3
│
▼
🤖 AI-Generated Response
│
▼
👤 User


---

## 🎯 Task-Specific Prompting

The project uses three dedicated prompt templates to improve the structure and quality of AI responses.

### 🔍 Analysis Guidance

`analysis_guidance.txt`

Used when users ask questions such as:

> "How should I analyze my sales data?"

The prompt guides the AI to provide:

- Key questions to answer
- Recommended metrics
- Analysis methodology
- Visualization recommendations
- Potential insights
- Common pitfalls
- Tools and techniques

---

### 📊 Metric Explanation

`metric_explanation.txt`

Used when users want to understand business metrics, KPIs, calculations, or definitions.

Example:

> "What is customer retention rate?"

The AI can explain the concept, calculation, interpretation, and business relevance.

---

### 📝 Report Generation

`report_generation.txt`

Used when users ask the assistant to create a business report or report structure.

Example:

> "Create a report outline for monthly sales performance."

The prompt helps structure the response around areas such as:

- Executive Summary
- Key Metrics
- Analysis & Insights
- Recommendations
- Visualization Suggestions

---

## 🔄 Request Flow

When a user sends a question, the Flask application:
Receives the user's question
↓
Identifies the type of request
↓
Selects the appropriate prompt template
↓
Combines the instructions with the user question
↓
Sends the prompt to Ollama
↓
Llama 3 generates the response
↓
Flask returns the response to the interface

---

## 🦙 Why Ollama?

This project uses **Ollama** to run the Llama 3 model locally.

This provides:

- ✅ No paid API required
- ✅ No API key required
- ✅ Local model execution
- ✅ Simple integration through an HTTP API
- ✅ Useful environment for experimenting with Generative AI

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone <your-repository-url>
cd Business_intelligence_ai_assistant
```

### 2. Install the Required Python Packages

The application uses Flask, Flask-CORS, Requests, and python-dotenv.

```bash
python -m pip install flask flask-cors requests python-dotenv
```

### 3. Install Ollama

Install Ollama on your computer and make sure the Ollama service is running.

### 4. Download Llama 3

```bash
ollama pull llama3
```

Check that the model is installed:

```bash
ollama list
```

You should see:

llama3:latest


### 5. Run the Flask Application

```bash
python app_ollama.py
```

The application should start at:

http://localhost:5000


Open the URL in your browser.

---

## 💬 Example Questions

Try asking the assistant:

What is the difference between revenue and profit?

How should I analyze monthly sales data?

What metrics should I track for an e-commerce business?

Create a report outline for quarterly sales performance.

What visualizations should I use to analyze customer retention?


---

## 📊 Business Intelligence Focus

The assistant is designed around common Business Intelligence activities, including:

- KPI analysis
- Business metrics
- Trend analysis
- Data interpretation
- Report preparation
- Visualization planning
- Business recommendations

The included **Four Types of Data Analytics** visual also provides context around:

**Descriptive → Diagnostic → Predictive → Prescriptive Analytics**

---

## 🔐 Local AI

Unlike applications that rely on cloud-based AI APIs, this project uses a locally running Llama 3 model through Ollama.

User
│
▼
Flask Application
│
▼
Local Ollama Server
│
▼
Llama 3
│
▼
Response


No external AI API key is required for the current implementation.

---

## 🔮 Future Improvements

Possible improvements for the project include:

- 📂 CSV/Excel dataset upload
- 📊 Automatic Exploratory Data Analysis (EDA)
- 📈 Automatic chart generation
- 🗄️ Database integration
- 🔎 Natural-language SQL generation
- 📑 Automated business reports
- 💾 Conversation memory
- 📌 Interactive KPI dashboards
- 🤖 Support for additional LLMs
- ☁️ Cloud deployment

---

## 🎓 Learning Objectives

This project provides practical exposure to:

- Python application development
- Flask backend development
- REST API communication
- Local LLM integration
- Generative AI
- Prompt engineering
- Task-based prompt selection
- Business Intelligence concepts
- Data analysis workflows

  ---

## 👩‍💻 Author

**Kanak Kirti Sharma**

B.Tech – Computer Science

Interested in **Data Analytics, Business Intelligence, Generative AI, and AI-assisted data applications.**

---

## ⭐ Project Highlights

> **Business Intelligence + Generative AI + Local LLM + Prompt Engineering**

This project demonstrates how a traditional Business Intelligence assistant can be enhanced using a locally running Large Language Model to provide structured, business-focused analytical guidance.

---

