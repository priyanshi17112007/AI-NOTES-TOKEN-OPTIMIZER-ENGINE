# 🚀 AI Notes Token Optimizer Engine

### Intelligent Token Management & Cost Optimization Platform using Google Gemini AI

![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Gemini](https://img.shields.io/badge/Google-Gemini%202.5%20Flash-orange)
![AI](https://img.shields.io/badge/Generative-AI-green)
![Status](https://img.shields.io/badge/Status-Active-success)

---

## 📌 Overview

AI Notes Token Optimizer Engine is a production-inspired Generative AI application designed to optimize large textual inputs before sending them to an LLM.

The system performs token estimation, intelligent chunking, caching, cost analysis, budget monitoring, prompt experimentation, and response streaming to improve efficiency, reduce API costs, and enhance AI workflow performance.


---

## 🎯 Key Features

### 🤖 Gemini AI Integration

* Google Gemini 2.5 Flash API Integration
* Streaming AI Responses
* Automatic Retry & Error Recovery
* Response Generation Pipeline

### 📊 Token Intelligence

* Real-Time Token Counting
* Token Usage Analytics
* Input/Output Token Monitoring
* Token Cost Estimation

### ✂️ Smart Chunking Engine

* Splits large notes into manageable chunks
* Prevents context window overflow
* Improves processing efficiency
* Supports scalable document handling

### 💾 Persistent Cache System

* SHA-256 Hash-Based Caching
* Eliminates redundant API calls
* Reduced operational cost

### 💰 Cost Optimization

* INR-Based Cost Tracking
* Input/Output Cost Calculation

### 🛡️ Reliability & Protection

* Budget Guard Protection
* Retry with Exponential Backoff
* Safe API Request Handling
* Session Analytics Tracking

### 🧪 Prompt Engineering Toolkit

* A/B Prompt Testing

---

## 🛠️ Tech Stack

### Programming Language

* Python 3.10+

### AI & LLM Technologies

* Google Gemini 2.5 Flash
* Generative AI
* Prompt Engineering

### Core Concepts Implemented

* Token Optimization
* Text Chunking
* Response Streaming
* Cost Analytics
* Cache Management
* Session Monitoring

### Python Libraries

* google-genai
* python-dotenv
* os
* sys
* json
* time
* hashlib
* collections
* typing
* dataclasses
* functools

### Development Environment

* VS Code
* Google Colab
* GitHub

---

## 🏗️ System Architecture

```text
User Notes
    │
    ▼
Token Analysis
    │
    ▼
Smart Chunking
    │
    ▼
SHA-256 Cache Check
    │
    ├── Cache Hit → Return Stored Response
    │
    └── Cache Miss
              │
              ▼
       Gemini API Request
              │
              ▼
      Response Streaming
              │
              ▼
      Cost Calculation
              │
              ▼
      Summary Generation
              │
              ▼
       Analytics Report
```

---

## 📂 Project Structure

```text
AI-NOTES-TOKEN-OPTIMIZER-ENGINE/
│
├── main.py
├── requirements.txt
├── .env.example
├── README.md
```

### File Responsibilities

| File             | Purpose                       |
| ---------------- | ----------------------------- |
| main.py          | Main application execution    |
| requirements.txt | Dependency management         |
| .env.example     | Environment variable template |
| README.md        | Project documentation         |

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/priyanshi17112007/AI-NOTES-TOKEN-OPTIMIZER-ENGINE.git

cd AI-NOTES-TOKEN-OPTIMIZER-ENGINE
```

### Create Virtual Environment

#### Windows

```bash
python -m venv venv

venv\Scripts\activate
```

#### Mac/Linux

```bash
python3 -m venv venv

source venv/bin/activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Configuration

Create a `.env` file in the project root:

```env
GEMINI_API_KEY=your_api_key_here

USD_TO_INR=83.5
INPUT_RATE_USD=0.30
OUTPUT_RATE_USD=2.50
DAILY_LIMIT_INR=50
```

---

## ▶️ Run Application

```bash
python main.py
```

---

## 📓 Run on Google Colab

This project can be executed directly on Google Colab without any local setup.

### Step 1: Open Google Colab

Create a new notebook.

### Step 2: Install Dependencies

```python
!pip install google-genai python-dotenv
```

### Step 3: Configure Gemini API Key

1. Open the **Secrets (🔑)** panel from the left sidebar.
2. Create a new secret named:

```text
GEMINI_API_KEY
```

3. Paste your Gemini API Key.
4. Enable **Notebook Access**.

### Step 4: Upload Project

Upload:

```text
AI_NOTES_TOKEN_OPTIMIZER.ipynb
```

or copy the project code into a notebook cell.

### Step 5: Execute

Run all cells and provide your notes when prompted.

### Colab Benefits

* No local installation required
* Cloud-based execution
* Quick Gemini API testing
* Beginner-friendly environment
* Ideal for experimentation and learning

```

## ☁️ Platform Compatibility

| Platform | Supported |
|-----------|-----------|
| Google Colab | ✅ |
| VS Code | ✅ |
| Windows | ✅ |
| Linux | ✅ |
| macOS | ✅ |
```


---

## 👩‍💻 Author

**Priyanshi Sharma**

Beginner AI Developer | Python Learner | Generative AI Enthusiast

📧 erpriyanshisharma15@gmail.com

*"Building practical AI systems that optimize performance, cost, and user experience."*














