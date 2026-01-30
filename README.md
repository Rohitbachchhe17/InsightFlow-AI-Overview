
# 🚀 InsightFlow AI – Automated CSV Analytics with n8n & LLM

InsightFlow AI is an AI-powered data analytics automation pipeline built using n8n that converts raw CSV files into meaningful visual insights — without any manual chart configuration.

It automatically understands the dataset structure, selects suitable aggregations, chooses the correct chart types using LLM-based reasoning, and generates charts dynamically through an HTTP visualization API.

This project is designed as a reusable, data-agnostic analytics engine suitable for real-world reporting and automated data pipelines.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/572f679d-2a5a-48c3-982b-57e456f32334" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/fcf7a85d-41b0-4367-b993-5617e6d714ac" />

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6631184b-6dc8-4390-9ae9-06d4dbb7daf2" />

---

## 🔗 Full Demo

🎥 Video Demo  
https://drive.google.com/file/d/1GoP06EqCGicpPMR_pRDPyQmpvV0WyvzA/view?usp=sharing

---

## 🧠 What InsightFlow AI Does

InsightFlow AI automatically performs:

- CSV structure understanding
- Column type detection (categorical, numerical, time-based, etc.)
- Distribution and aggregation analysis
- AI-driven chart selection
- Dynamic chart configuration generation
- Chart rendering via HTTP API

No dashboards to design.  
No charts to configure.  
Just upload a CSV and receive visual insights.

---

## 🏗️ Architecture Overview
CSV Input
↓
Data Parsing (n8n)
↓
Aggregation & Statistics Engine
↓
LLM Reasoning Layer
↓
Chart Logic Generator
↓
HTTP Chart Rendering API
↓
Visual Insight Output


---

## ✨ Key Features

- AI-driven chart type selection (bar, line, pie, comparative, etc.)
- Automatic aggregation detection
- Fully automated CSV → insight pipeline
- Dataset-agnostic (no schema dependency)
- Reusable and scalable n8n workflow
- API-driven visualization
- Suitable for business, academic and operational analytics

---

## 🔑 Why This Project Matters

Most CSV visualization tools:

- Require manual chart setup
- Depend on predefined schemas
- Break when new datasets are introduced
- Are not reusable automation pipelines

InsightFlow AI:

- Works with any structured CSV
- Uses LLM reasoning instead of hard-coded rules
- Adapts to new datasets without workflow changes
- Mirrors real-world data automation architectures

---

## 🛠️ Technology Stack

- n8n – Workflow orchestration
- LLM (via API) – Chart reasoning and analytics logic
- JavaScript / JSON – Data transformation inside n8n
- HTTP Chart API – Dynamic chart rendering
- CSV ingestion and parsing pipeline

---

## 📁 Workflow Content

The repository contains:

- n8n workflow definition
- CSV parsing and transformation logic
- LLM prompt and reasoning flow
- Chart configuration generator nodes

---

## 🧩 How It Works

1. Upload a structured CSV file
2. n8n parses and profiles the dataset
3. Aggregation statistics are computed
4. Dataset metadata is sent to the LLM
5. The LLM decides:
   - suitable dimensions
   - aggregation metrics
   - best chart type
6. Dynamic chart configuration is generated
7. The chart is rendered using an HTTP visualization endpoint

---

## ▶️ Running the Project

### 1. Install n8n


or using Docker:


---

### 2. Import the Workflow

- Open the n8n UI
- Import the workflow JSON file from this repository

---

### 3. Configure Environment Variables

Set the following environment variables in n8n:

LLM_API_KEY=your_api_key_here
CHART_API_ENDPOINT=your_chart_rendering_api


---

### 4. Run the Workflow

- Upload your CSV file
- Execute the workflow
- Automatically generated chart insights will be produced

---

## 📸 Workflow and Output

Screenshots included in the repository:

- Workflow screenshot  
  Screenshot 2025-12-31 152022

- Output screenshots  
  Screenshot 2025-12-31 153503  
  Screenshot 2025-12-31 153531

---

## 🔍 Use Cases

- Automated KPI reporting
- Business analytics automation
- Academic data exploration
- Operations monitoring
- Internal analytics pipelines
- AI-assisted data storytelling

---

## 📌 Project Highlights

- No predefined schemas
- No hard-coded chart logic
- No manual dashboard configuration
- Fully reusable analytics workflow
- AI-assisted insight generation

---

## 📄 License

MIT License

---

## 👤 Author

InsightFlow AI  
Built using n8n and LLM-based analytics reasoning.

