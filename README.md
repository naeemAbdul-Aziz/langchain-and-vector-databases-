# 🌐 LangChain Projects Collection

Welcome to the **LangChain Projects Collection**!  
This repository houses the hands-on projects I created during my journey through the LangChain and Deep Lake course.

These projects demonstrate various applications of Large Language Models (LLMs) and the LangChain framework, designed to solve real-world problems using cutting-edge AI techniques.

Each project showcases different aspects of LangChain and how it integrates with tools like Activeloop's Deep Lake and LLMs (such as GPT-4). The use cases range from summarizing news articles to creating autonomous reasoning agents.

---

## 📁 Projects Overview

### 1. 📰 News Articles Summarizer
Automatically summarizes news articles using LangChain and an LLM.

**Key Concepts:**
- LangChain LLM integration  
- Prompt engineering (summarization)  
- Data ingestion from news sources  

---

### 2. 💬 Customer Support Chatbot
A fully functional chatbot that uses LangChain and Deep Lake to retrieve relevant responses from a database of support documents.

**Key Concepts:**
- Using Deep Lake as a vector store  
- Data ingestion and document retrieval  
- Building a chatbot using LangChain  

---

### 3. 🧠 News Knowledge Graph Extractor
Uses LLMs to extract and organize key information from articles into a structured knowledge graph.

**Key Concepts:**
- Knowledge graph extraction  
- Structuring unstructured data  
- Prompt engineering for data extraction  

---

### 4. 🎥 YouTube Video Summarizer
Summarizes YouTube videos using metadata and content pulled via the YouTube API.

**Key Concepts:**
- YouTube API integration  
- Summarizing long-form content  
- Using external data sources with LangChain  

---

### 5. 🧑‍💻 Jarvis Knowledge Base
An AI assistant that browses a knowledge base and provides answers based on stored information.

**Key Concepts:**
- LangChain chain creation  
- Knowledge base interaction  
- Building an intelligent assistant  

---

### 6. 🛠️ GitHub Repo Chatbot
A chatbot that interacts with GitHub repositories to provide insights and answer questions.

**Key Concepts:**
- Interacting with GitHub API  
- Knowledge extraction from codebases  
- Context-based querying with LangChain  

---

### 7. 💰 Financial Question-Answering Chatbot
A specialized chatbot for answering financial questions using domain-specific data.

**Key Concepts:**
- Integrating financial data  
- Domain-specific question answering  
- Using LangChain’s memory and tools  

---

### 8. 🤖 Autonomous Agent for Report Creation
An autonomous agent that generates full analysis reports using LangChain’s agent framework.

**Key Concepts:**
- LangChain agents  
- Autonomous reasoning with LLMs  
- Building automated workflows  


## ⚙️ How to Use

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/langchain-projects.git
cd langchain-projects
```

### 2. Install Required Dependencies

Ensure you have Python 3.x installed, then install the dependencies:

```bash
pip install -r requirements.txt
```

### 3. Set Up API Keys

For projects requiring APIs (e.g., OpenAI, YouTube), set your API keys in a `.env` file or use environment variables.

* **OpenAI API Key**: [https://platform.openai.com/](https://platform.openai.com/)
* **YouTube API Key**: [https://console.cloud.google.com/](https://console.cloud.google.com/)

### 4. Run the Projects

Navigate to any project folder and run:

```bash
python project_name.py
```

### 5. Explore and Modify

These projects are meant to be a foundation. Feel free to experiment, extend functionality, or adapt them to new use cases!

---

## 🔧 Key Technologies Used

* **LangChain** – Framework for building apps with LLMs
* **Deep Lake** – Vector database for storing and querying embeddings
* **OpenAI GPT-4** – Language model for text generation and reasoning
* **YouTube API** – For pulling video data
* **GitHub API** – For interacting with repository content
