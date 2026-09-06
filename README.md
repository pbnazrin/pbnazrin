# Hi 👋 I'm Nazrin

### Software Engineer → AI/ML Engineer | Generative AI | Agentic AI | MDM

I'm a **Software Engineer with 4 years of experience in frontend engineering**, working in the **Enterprise Mobility / Mobile Device Management (MDM)** domain.

I'm currently transitioning into **AI/ML Engineering**, with a focus on applying Machine Learning and Generative AI to real-world enterprise and device-management problems.

My interests include **Machine Learning, Deep Learning, Generative AI, RAG, Agentic AI, MCP, AI evaluation, MLOps and production AI systems**.

> **My goal:** Combine software engineering + MDM domain expertise + AI/ML to build intelligent, production-ready systems.

---

## 🧠 AI/ML Focus

I'm currently building hands-on experience across:

* Machine Learning
* Deep Learning
* Generative AI & LLMs
* Retrieval-Augmented Generation (RAG)
* Agentic AI
* Multimodal AI
* MCP & Tool Engineering
* LLM / Agent Evaluation
* MLOps & LLMOps
* AI application deployment

---

## 🏢 Domain Expertise

### Enterprise Mobility & Device Management

My professional experience is in the **MDM / Enterprise Mobility Management domain**, working with systems that manage and monitor enterprise devices.

Areas I'm particularly interested in applying AI/ML to include:

* Device health prediction
* Predictive device failure
* Device anomaly detection
* Device telemetry analysis
* Intelligent troubleshooting
* Log analysis
* Device configuration intelligence
* Application and device monitoring
* AI-powered support assistants
* Automated root-cause analysis

> Portfolio projects use **synthetic or publicly available data** and do not contain proprietary company code, data or confidential information.

---

# 🚀 Featured AI/ML Projects

## 🧠 Predictive Device Health & Failure Detection

An end-to-end Machine Learning system designed to identify enterprise devices that may be at risk of failure or becoming unhealthy.

### Problem

Can device telemetry be used to predict whether a device is likely to experience a failure or become unhealthy in the near future?

### Example features

```text
Device OS
OS Version
Device Model
Battery Health
Battery Temperature
CPU Usage
Memory Usage
Storage Usage
Network Signal
App Crash Count
Error Count
Reboot Count
Last Check-in
Data Usage
Days Since Update
```

### ML Pipeline

```text
Device Telemetry
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Feature Engineering
       ↓
Preprocessing
       ↓
ML Models
       ↓
Model Evaluation
       ↓
Explainability
       ↓
Model Tracking
       ↓
API
       ↓
Docker
       ↓
Cloud Deployment
```

### Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* SHAP
* MLflow
* FastAPI
* Docker

🔗 **Repository:** `Coming Soon`

---

## 🚨 Device Anomaly Detection

An ML system for identifying unusual behaviour in enterprise device telemetry where labelled failure data may not always be available.

### Example

```text
Normal Device
     ↓
CPU       ─────────
Memory    ───────
Battery   ──────────
Network   ─────────
Errors    ──


Potential Anomaly
     ↓
CPU       ───────────────
Memory    ─────────────
Battery   ───
Network   ─
Errors    ───────────────
```

### Techniques explored

* Exploratory data analysis
* Feature engineering
* Isolation Forest
* One-Class SVM
* Autoencoders
* Anomaly scoring
* Threshold selection
* Model evaluation

🔗 **Repository:** `Coming Soon`

---

# 🔥 MDM Knowledge RAG

### Enterprise Mobility Support Copilot

A RAG-based AI assistant designed to answer questions about device management, enrollment, policies, operating systems, applications and troubleshooting.

The system uses **publicly available documentation and synthetic examples**.

### Architecture

```text
              User
                ↓
          Query Processing
                ↓
        ┌───────────────┐
        │  Hybrid Search │
        └───────┬───────┘
                ↓
       Vector + Keyword Search
                ↓
             Reranker
                ↓
               LLM
                ↓
        Answer + Citations
```

### Focus areas

* Document ingestion
* Chunking strategies
* Embeddings
* Vector databases
* Hybrid retrieval
* Reranking
* Query rewriting
* Metadata filtering
* Citation generation
* RAG evaluation
* Hallucination reduction

🔗 **Repository:** `Coming Soon`

---

# 🤖 Agentic MDM Troubleshooting Assistant

An AI agent designed to investigate device issues by interacting with device-management tools and knowledge sources.

### Example

```text
Admin:
"Why is device ABC123 offline?"
              ↓
       Troubleshooting Agent
              ↓
     ┌────────┼─────────┐
     ↓        ↓         ↓
 Device     Logs      Network
 Status     Tool        Tool
     ↓        ↓         ↓
     └────────┼─────────┘
              ↓
        Root Cause Analysis
              ↓
       Recommended Action
```

### Example tools

```text
get_device_status()
get_device_logs()
get_network_status()
get_device_policy()
get_device_app_status()
get_recent_commands()
get_device_location()
```

### Technologies

* Python
* LangGraph
* LLMs
* RAG
* Tool Calling
* MCP
* FastAPI
* PostgreSQL
* Vector Database
* AI Observability

### Engineering focus

* Agent state management
* Tool selection
* Planning & routing
* Error handling
* Guardrails
* Human-in-the-loop
* Agent evaluation
* Observability

🔗 **Repository:** `Coming Soon`

---

# 👁️ Multimodal Device Support Assistant

An experimental multimodal AI system that combines screenshots, device telemetry and enterprise documentation to assist with troubleshooting.

### Architecture

```text
              Screenshot
                  +
           Device Telemetry
                  +
            MDM Knowledge
                  ↓
          Multimodal AI
                  ↓
          Diagnosis / RAG
                  ↓
       Recommended Resolution
```

### Capabilities

* Screenshot understanding
* Error extraction
* Document retrieval
* Device-context analysis
* Multimodal reasoning
* Troubleshooting recommendations

🔗 **Repository:** `Coming Soon`

---

# 🔌 MCP & Tool Engineering

Exploring **Model Context Protocol (MCP)** and tool-based AI systems for connecting agents with external enterprise systems.

### Example architecture

```text
                    AI Agent
                       ↓
                   MCP Client
                       ↓
        ┌──────────────┼──────────────┐
        ↓              ↓              ↓
     Device          Database       Documents
      Tools            Tools          Tools
        ↓              ↓              ↓
     MDM Data        SQL Data      Knowledge
```

Focus areas:

* MCP servers
* Tool schemas
* Function calling
* Structured outputs
* Tool permissions
* Error handling
* Agent-tool interaction
* Secure tool execution

🔗 **Repository:** `Coming Soon`

---

# 📊 AI Evaluation

A major focus of my AI engineering work is **measuring whether AI systems actually work**.

I'm exploring evaluation across:

```text
RAG
 ├── Retrieval Quality
 ├── Context Relevance
 ├── Faithfulness
 └── Answer Relevance

Agents
 ├── Tool Selection
 ├── Task Completion
 ├── Agent Trajectory
 └── Error Recovery

Production
 ├── Latency
 ├── Token Usage
 ├── Cost
 └── Reliability
```

---

# 🚀 MLOps / LLMOps

Building AI systems with production engineering practices.

```text
GitHub
   ↓
CI/CD
   ↓
Docker
   ↓
Cloud
   ↓
AI Application
   ↓
Monitoring
   ├── Logs
   ├── Metrics
   ├── Traces
   ├── Latency
   └── Cost
```

Areas of interest:

* MLflow
* Model versioning
* Experiment tracking
* Model evaluation
* Prompt versioning
* AI observability
* FastAPI
* Docker
* CI/CD
* Cloud deployment

---

# 💻 Software Engineering Background

Before specializing in AI/ML, I worked as a **Frontend Engineer** building production enterprise applications.

### Frontend

* Angular
* TypeScript
* JavaScript
* HTML
* CSS
* RxJS
* State Management

### Engineering

* REST APIs
* Component architecture
* Application architecture
* Git
* CI/CD
* Debugging
* Performance optimization
* Enterprise application development

My software engineering background helps me approach AI systems not only as ML experiments, but as **maintainable and deployable production applications**.

---

# 🛠️ Current AI/ML Stack

### Programming

![Python](https://img.shields.io/badge/Python-3776AB?style=flat\&logo=python\&logoColor=white)

### Data & ML

![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat\&logo=pandas\&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=flat\&logo=scikit-learn\&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EC4E20?style=flat)

### Deep Learning & GenAI

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat\&logo=pytorch\&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat\&logo=huggingface\&logoColor=black)

* Transformers
* LLMs
* Embeddings
* RAG
* Multimodal AI
* Fine-tuning

### Agentic AI

* LangChain
* LangGraph
* MCP
* Tool Calling
* AI Agents
* Human-in-the-loop
* Guardrails

### MLOps / Backend

![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=flat\&logo=mlflow\&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat\&logo=fastapi\&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat\&logo=github-actions\&logoColor=white)

---

# 📚 Current Learning Path

```text
Python
   ↓
Statistics & Mathematics
   ↓
Machine Learning
   ↓
Deep Learning
   ↓
PyTorch
   ↓
Transformers
   ↓
Generative AI
   ↓
RAG
   ↓
Agentic AI
   ↓
MCP & Tool Engineering
   ↓
Evaluation
   ↓
MLOps / LLMOps
   ↓
Production AI Systems
```

---

# 🎯 Career Direction

I'm transitioning from **Frontend Engineering into AI/ML Engineering**, with a particular interest in:

* AI Engineer
* Machine Learning Engineer
* Generative AI Engineer
* Agentic AI Engineer
* AI/ML Platform Engineering
* MLOps / LLMOps

I'm especially interested in solving **enterprise problems using AI/ML**, where strong software engineering and domain knowledge can be combined with intelligent systems.

---

# 📫 Connect With Me

* 💼 LinkedIn: `[Your LinkedIn](https://www.linkedin.com/in/nazrin-p-b-0708733b/)`
* 📧 Email: `pbnazrin@gmail.com`
* 🐙 GitHub: `https://github.com/pbnazrin/`

---

> **From managing devices to building intelligent systems.**
>
> **Software Engineering × MDM × AI/ML**
