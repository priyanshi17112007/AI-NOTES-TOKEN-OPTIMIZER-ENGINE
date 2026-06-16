🚀 AI-Notes-Token-Optimizer-Engine


![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Gemini](https://img.shields.io/badge/Google-Gemini%202.5%20Flash-orange)
![AI](https://img.shields.io/badge/AI-Generative%20AI-purple)
![Status](https://img.shields.io/badge/Status-Production%20Ready-success)
![Platform](https://img.shields.io/badge/Platform-Colab%20%7C%20VSCode-blue)
![License](https://img.shields.io/badge/License-MIT-green)

🎯 Project Highlights

✅ Real-Time Token Counting
✅ Gemini 2.5 Flash Integration
✅ Smart Text Chunking Engine
✅ SHA-256 Persistent Cache
✅ INR Cost Tracking System
✅ Streaming AI Responses
✅ Budget Guard Protection
✅ Retry & Backoff Handling
✅ Session Analytics Dashboard
✅ A/B Prompt Testing Framework
✅ Google Colab & VS Code Support

## 🛠️ Tech Stack

### Programming Language

🐍 Python 3.10+

### AI & Machine Learning

🤖 Google Gemini 2.5 Flash
🧠 Generative AI
💬 Prompt Engineering

### Core Technologies

📦 Dataclasses
🔄 Generators
🔐 SHA-256 Hashing
💾 JSON Caching
📊 Token Analytics

### Development Tools

💻 VS Code
📓 Google Colab
🌐 GitHub

### Libraries Used

google-genai,
python-dotenv,
os,
sys,
json, 
time,
hashlib,
collections,
typing,
dataclasses, 
functools.

## Running the Project
This project supports both *Google Colab* and *VS Code / Local Python Environment*.

----------------------------------------------------------------------------------------------------------------------------
# Option 1: Run on Google Colab

## Step 1: Open Google Colab

Create a new notebook and install dependencies:

```bash
!pip install google-genai python-dotenv
```

## Step 2: Add Gemini API Key

In Colab:

* Click the 🔑 Secrets tab (left sidebar)
* Create a new secret named:

```text
GEMINI_API_KEY
```

* Paste your Gemini API Key
* Enable Notebook Access

## Step 3: Upload Project File

Upload "AI_NOTES_TOKEN_OPTIMIZER.ipynb" or paste the code into a notebook cell.

## Step 4: Run

Execute all cells and provide your notes when prompte
-----------------------------------------------------------------------------------------------------------------------------
# Option 2: Run in VS Code
The following files are sufficient to run the project in VS Code or any local Python environment:

AI-NOTES-TOKEN-OPTIMIZER-ENGINE/
│
├── main.py
├── requirements.txt
├── .env
├── README.md

📄 File Descriptions:
* main.py-->	Main application entry point
* requirements.txt-->	Python dependencies required to run the project
* .env.example-->	Template for environment variables
* README.md-->	Project documentation and setup guide

## Step 1: Clone Repository

```bash
git clone https://github.com/priyanshi17112007/AI-NOTES-TOKEN-OPTIMIZER-ENGINE.git
cd AI-NOTES-TOKEN-OPTIMIZER-ENGINE
```

## Step 2: Create Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

Mac/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

## Step 3: Install Dependencies

```bash
pip install -r requirements.txt
//google-genai
//python-dotenv
```

## Step 4: Create .env File

Create a file named `.env` in the project root:

```env
GEMINI_API_KEY=your_api_key_here

USD_TO_INR=83.5
INPUT_RATE_USD=0.30
OUTPUT_RATE_USD=2.50
DAILY_LIMIT_INR=50
```
# Step 5: Run Application
:-python main.py


-----------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------
## Architecture:
Input Notes
→ Chunking
→ Token Analysis
→ Cache Check
→ Gemini API
→ Cost Tracking
→ Summary Generation
→ Report Builder


👨‍💻 Author:-
Priyanshi Sharma|
Begginer AI Developer | Python learner | Building Intelligent AI Systems|
 erpriyanshisharma15@gmail.com
