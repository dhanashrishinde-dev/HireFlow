# 🚀 HireFlow – AI-Powered Outreach Automation Platform

HireFlow is an end-to-end Generative AI application that automates personalized job outreach by combining web scraping, Retrieval-Augmented Generation (RAG), vector search, and Large Language Models.

The platform extracts job requirements directly from company career pages, matches them with relevant projects from a candidate portfolio, and generates highly personalized cold emails within seconds.

---

## ✨ Features

### 🔍 Automated Job Extraction

* Scrapes career pages from company websites
* Extracts job roles, required skills, experience, and descriptions
* Supports multiple job postings from a single page

### 🧠 Retrieval-Augmented Generation (RAG)

* Stores portfolio projects inside ChromaDB
* Uses semantic similarity search to identify relevant projects
* Enhances LLM responses with contextual portfolio information

### 📧 AI-Powered Cold Email Generation

* Generates personalized outreach emails automatically
* Tailors emails based on job requirements
* Produces ready-to-send professional email drafts

### ⚡ Smart Portfolio Matching

* Embedding-based project retrieval
* Context-aware recommendation system
* Dynamic portfolio linking

### 🌐 Interactive User Interface

* Streamlit-based web application
* Simple URL input workflow
* Real-time email generation

---

## 🏗️ System Architecture

Career Page URL
↓
Web Scraping (WebBaseLoader)
↓
Text Cleaning & Processing
↓
LLM Job Extraction
↓
Skill Identification
↓
ChromaDB Vector Search
↓
Relevant Portfolio Retrieval
↓
RAG Pipeline
↓
Groq Llama 3.3 70B
↓
Personalized Cold Email

---

## 🛠️ Technology Stack

### Generative AI

* Large Language Models (LLMs)
* Retrieval-Augmented Generation (RAG)
* Prompt Engineering
* Semantic Search

### Frameworks

* LangChain
* Streamlit

### LLM Provider

* Groq API
* Llama 3.3 70B Versatile

### Vector Database

* ChromaDB

### Programming

* Python

### Data Processing

* Pandas
* NumPy

### Web Scraping

* WebBaseLoader
* BeautifulSoup

### Deployment

* GitHub
* Render

---

## 📂 Project Structure

```text
HireFlow/
│
├── main.py
├── chains.py
├── portfolio.py
├── utils.py
├── my_portfolio.csv
├── requirements.txt
├── runtime.txt
├── .env
│
├── vectorstore/
│
└── README.md
```

---

## 🔄 Workflow

1. User enters a company careers page URL.
2. HireFlow scrapes the webpage.
3. Job descriptions are extracted using Groq Llama 3.3.
4. Required skills are identified.
5. ChromaDB performs semantic search on portfolio projects.
6. Relevant projects are retrieved.
7. RAG enriches the prompt with portfolio context.
8. Personalized cold email is generated.
9. User receives a ready-to-send outreach email.

---

## 🎯 Use Cases

* Job Application Automation
* Freelance Proposal Generation
* Consulting Outreach
* Lead Generation
* Recruitment Assistance

---

## 📈 Key Outcomes

* Automated job requirement extraction
* Portfolio-aware email generation
* Reduced manual outreach effort
* Improved personalization through semantic retrieval
* End-to-end AI workflow using modern GenAI architecture

---

## 🚀 Installation

### Clone Repository

```bash
git clone https://github.com/your-username/HireFlow.git
cd HireFlow
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

```bash
# Windows
venv\Scripts\activate

# Linux/Mac
source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Configure Environment Variables

```env
GROQ_API_KEY=your_groq_api_key
```

### Run Application

```bash
streamlit run main.py
```

---



Interested in:

* Generative AI
* Agentic AI
* LLM Engineering
* Machine Learning
* Data Science

---

⭐ If you found this project useful, consider starring the repository.
