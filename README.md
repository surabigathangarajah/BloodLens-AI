```markdown
# 🩸 BloodLens AI

An AI-powered blood report analysis assistant that converts complex laboratory results into simple health insights and personalized dietary recommendations.

BloodLens AI uses **Generative AI, LangChain, Google Gemini, and Streamlit** to extract blood test values, identify abnormal results, and generate easy-to-understand health summaries.

---

## 🚀 Features

- 🧪 Extracts blood test values from blood reports
- 📊 Classifies results as:
  - HIGH
  - LOW
  - NORMAL
- 🤖 Uses Large Language Models (LLMs) for medical report analysis
- 📝 Generates simple health summaries
- 🥗 Provides practical Sri Lankan diet recommendations
- 💻 Interactive Streamlit web application

---



```
## 🏗️ System Architecture
User
|
| Enter Blood Report
↓
Streamlit Application
|
↓
LangChain Framework
|
↓
Google Gemini / Gemma LLM
|
↓
Blood Report Analysis
|
├── Extract Test Values
|
├── Classify Results
|
└── Generate Health Summary + Diet Plan
|
↓
User Interface

```

---

## 🛠️ Tech Stack

- **Programming Language:** Python
- **Frontend:** Streamlit
- **AI Framework:** LangChain
- **Large Language Model:** Google Gemini / Gemma
- **Environment Management:** python-dotenv

---

## 📂 Project Structure

```

BloodLens-AI/
│
├── app.py
├── requirements.txt
├── README.md
├── .env.example
└── sample_report.txt

````

---

## ⚙️ Installation & Setup

### Clone the repository

```bash
git clone https://github.com/your-username/BloodLens-AI.git
````

Navigate to the project folder:

```bash
cd BloodLens-AI
```

---

### Install dependencies

```bash
pip install -r requirements.txt
```

---

### Setup Environment Variables

Create a `.env` file:

```env
GOOGLE_API_KEY=your_api_key_here
```

Add your Google Gemini API key.

---

### Run the Application

```bash
streamlit run app.py
```

The application will open in your browser.

---

## 🔍 How It Works

### Stage 1: Blood Report Extraction

The AI extracts:

* Test name
* Test value
* Reference range
* Status (HIGH / LOW / NORMAL)

from the given blood report.

### Stage 2: Health Analysis

The extracted results are analyzed by the LLM to generate:

* Simple health summary
* Blood report interpretation
* Personalized diet recommendations

---

## 📸 Application Preview

<img width="1920" height="842" alt="Application" src="https://github.com/user-attachments/assets/3d0f755a-8c3a-4ab6-9f53-b48b7ccd0183" />


---



## 🔮 Future Improvements

* PDF blood report upload support
* OCR-based report extraction
* Retrieval Augmented Generation (RAG) for medical knowledge
* Patient history tracking
* Cloud deployment

```
```
