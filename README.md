# Hi there, I'm Ishan Bansal 👋

## 🎓 Electronics & Communication Engineer | 🤖 Agentic AI & LLMOps Engineer | ⚡ Tech Explorer | 🚀 Always Learning

[![GitHub followers](https://img.shields.io/badge/GitHub-Follow-blue?style=for-the-badge&logo=github)](https://github.com/ishanb18)
[![AI/ML Engineer](https://img.shields.io/badge/AI%2FML-Engineer-green?style=for-the-badge&logo=tensorflow)](https://github.com/ishanb18)
[![ECE Engineer](https://img.shields.io/badge/Electronics-Engineer-orange?style=for-the-badge&logo=arduino)](https://github.com/ishanb18)

---

## 🧑‍💻 About Me

- 🎓 Pursuing **B.Tech in Electronics & Communication Engineering** at LNMIIT (2023–27)
- 🤖 **Agentic AI & LLMOps Engineer** specializing in multi-agent systems and RAG pipelines
- 🔬 Exploring **LLMs, Deep Learning, Embedded Systems, and Full-Stack AI Development**
- 💡 Passionate about building **production-grade AI systems, voice interfaces, and agentic frameworks**
- 🌱 Currently diving deeper into **evaluation frameworks, VLMs, and MLOps**
- ✍️ Documenting my journey and projects here on GitHub

---

## 🔬 Research & Publications

### 📄 HAR for Healthcare Monitoring via Pose-Based Bidirectional LSTM · *INDISCON 2026, MNIT* · Apr 2026
*Ishan Bansal, Vidit Vinarma, Kartik Sharma — Advisor: Dr. Sandeep Saini, LNMIIT*

- **AI/ML Tech:** BiLSTM, MediaPipe Pose Landmarks, Edge Deployment
- Architected a BiLSTM classifier (~110K parameters) achieving **94.89% accuracy** and 0.945 macro F1 across 7 clinical classes, optimized for low-power CPU edge deployment
- Geometric post-processing engine sustaining **96.64% fall detection recall** with 2.1% FPR and <2ms CPU latency at 15 FPS

---

## 🚀 Featured Projects

### 🤖 [Blog Generation Agentic AI](https://github.com/ishanb18) — *Autonomous Multi-Agent System* · May 2026
**AI-powered autonomous pipeline** that produces full blog posts using a 5-agent LangGraph architecture with concurrent section writing.

**🎯 What it does:**
- Orchestrates 5 specialized agents for research, outlining, writing, editing, and publishing
- Delivers **5× faster** content production vs. sequential generation using LangGraph's `Send()` fan-out pattern
- Zero schema validation errors in production via strict Pydantic v2 structured outputs

**🛠️ Tech Stack:**
- **Orchestration:** LangGraph, LangChain
- **AI Models:** Mistral AI, Google Gemini, Tavily Search
- **Backend:** Python, Pydantic v2, Streamlit
- **Architecture:** Multi-agent fan-out with exponential-backoff error handling

**✨ Key Features:**
- 🧠 **5-agent autonomous pipeline** with parallel concurrent writing
- 🔍 **3-mode research system** powered by Tavily web search
- 🛡️ **Zero crash guarantee** with exponential-backoff on API failures
- 📋 **Strict structured outputs** via Pydantic v2 across all agent nodes

---

### 🌾 [Agroculture](https://github.com/ishanb18/Agroculture) — *Context-Aware Voice AI Farming Assistant* · Sep 2025
**AI-powered agricultural assistant** with market prices, weather insights, and Hindi-first multilingual voice I/O.

**🎯 What it does:**
- Connects farmers to live market prices, weather forecasting, and go/no-go planting decisions via voice
- Supports **Hindi and English** speech with real-time ASR and TTS
- Persists agronomy knowledge into a local vector database for low-latency RAG

**🛠️ Tech Stack:**
- **Backend:** FastAPI, Python, APScheduler
- **AI/ML:** Mistral AI, OpenAI Whisper (ASR), Microsoft Edge-TTS, spaCy NER
- **Vector DB:** ChromaDB with `all-MiniLM-L6-v2` embeddings
- **APIs:** Agmarknet market endpoints, Open-Meteo weather API

**✨ Key AI/ML Features:**
- 🗣️ **Hindi-first bilingual voice interface** with Whisper ASR + Edge-TTS
- 🌦️ **Live weather forecasting** with go/no-go planting engine
- 📦 **Overlapping chunking + RAG pipeline** for agronomy knowledge base
- ⏰ **Automated hourly alert jobs** via APScheduler background scheduling

---

### 💬 [Agentic Search Chatbot](https://github.com/ishanb18) — *Stateful LLM Agent* · Oct 2025
**Stateful conversational agent** using LangGraph with conditional tool routing and live web retrieval.

**🎯 What it does:**
- Maintains multi-turn dialogue state across long conversations
- Automatically triggers web search only when queries exceed internal LLM knowledge
- Recovers gracefully from node failures without breaking conversation flow

**🛠️ Tech Stack:**
- **Orchestration:** LangGraph StateGraph, LangChain
- **Search:** Tavily Search API
- **Frontend:** Streamlit

**✨ Key Features:**
- 🔄 **Stateful multi-turn dialogue** with automatic state recovery
- 🌐 **Conditional web retrieval** → out-of-knowledge failures near **0%**
- 🛠️ **Tool routing** with conditional edge logic

---

### 📄 [RAG-PDF-QnA](https://github.com/ishanb18) — *Document Question-Answering System* · Aug 2025
**Production RAG pipeline** for semantically accurate document Q&A with sub-second retrieval.

**🎯 What it does:**
- Indexes any PDF into a FAISS vector store and answers questions with source grounding
- Profiled and optimized with LangSmith tracing for production latency

**🛠️ Tech Stack:**
- **RAG:** LangChain, FAISS, OpenAI API
- **Observability:** LangSmith

**✨ Key Features:**
- ⚡ **Sub-second nearest-neighbor retrieval** via FAISS vector indexing
- 📉 **150ms latency reduction (20% improvement)** by refactoring to parallel embedding inference
- 🔍 **LangSmith tracing** for bottleneck identification and optimization

---

### 🏢 [foursqr_final](https://github.com/ishanb18/foursqr_final) — *AI-Powered Business Matchmaking Platform*
A comprehensive **full-stack platform** that revolutionizes business connections using AI and location intelligence.

**🎯 What it does:**
- Connects property owners, franchise companies, and entrepreneurs using **AI algorithms**
- Provides **AI-powered market analysis** and intelligent pricing recommendations
- Features modern responsive web interface with **real-time AI insights**

**🛠️ Tech Stack:**
- **Backend:** Python, FastAPI, SQLite
- **AI/ML:** Mistral AI for intelligent recommendations and NLP
- **APIs:** Foursquare Places API for location intelligence
- **Frontend:** HTML5, CSS3, JavaScript, Bootstrap 5

**✨ Key AI/ML Features:**
- 🗺️ **Location Intelligence** powered by Foursquare API
- 🤖 **AI-powered business matchmaking** using advanced algorithms
- 📊 **ML-based market analysis** and pricing insights
- 🔐 **Smart API management** with AI-powered validation

---

### 🛡️ [Phishing URL Detector](https://github.com/ishanb18/Phising_url_detector) — *Cybersecurity AI*
**Machine learning-based system** for detecting malicious URLs using advanced feature extraction and classification.
- **AI/ML Tech:** Supervised Learning, Feature Engineering, Classification Algorithms
- **ML Models:** Logistic Regression, Random Forest, XGBoost
- **Features:** Intelligent URL analysis, ML-powered threat detection, automated feature extraction

### 🧠 [ANN Optimizer Comparison](https://github.com/ishanb18/ANN-different_optimizers-) — *Deep Learning Research*
Comprehensive **deep learning research** analyzing different optimization algorithms on CIFAR-10 dataset.
- **AI/ML Tech:** Deep Neural Networks, Optimization Algorithms, Performance Analysis
- **ML Models:** Custom ANNs with SGD, Adam, RMSprop, Momentum optimizers
- **Features:** Performance visualization, convergence analysis, model comparison

### 📡 [Arduino Frequency Detector](https://github.com/ishanb18/frequency_detector-using-arduino) — *Embedded Systems*
Real-time digital signal processing with embedded C++.
- **Tech:** C++, Arduino, Embedded Systems, Signal Processing
- **Features:** Real-time signal processing, interrupt handling, serial communication

---

## 🔧 Tech Stack

### 🤖 Agentic AI & LLMOps
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangSmith](https://img.shields.io/badge/LangSmith-FF6B35?style=for-the-badge&logo=langchain&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logo=anthropic&logoColor=white)

### 🧠 ML & Deep Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### 💻 Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

### 🚀 Frameworks & Backend
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

### 🛠️ Tools & Platforms
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white)
![Google Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)

---

## 📊 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ishanb18&theme=tokyonight)
![Top Languages](https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ishanb18&theme=tokyonight)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=ishanb18&theme=tokyonight&hide_border=true)

</div>

---

## 🏆 Honors & Awards

- 🥇 **Bajaj Finserv HackRx 6.0** — Ranked **87th out of 7,000+** (Top 1.3%) for fintech solution design · Aug 2025

---

## 🎯 Current Goals & Learning

- 🧩 Going deeper into **LLM evaluation frameworks** and **agentic system design**
- ⚡ Exploring **DSPy, Langfuse, and MLFlow** for production ML observability
- 🔬 Building on my **BiLSTM research** — interested in VLMs and multimodal systems
- 🚀 Contributing to **open-source AI projects** in AgTech and health tech
- 🌱 Mastering **MLOps** and **AI deployment at scale**

---

## 📫 Let's Connect!

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ishan-bansal-60b631286)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:ishanbansal543210@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/ishanb18)

---

<div align="center">

**🤖 Building production-grade AI systems, one agent at a time! 🚀**

*"Where Electronics Engineering meets Agentic AI — creating intelligent systems that actually ship."*

![Agentic AI](https://img.shields.io/badge/🤖_Agentic_AI-LLMOps_Engineer-brightgreen?style=for-the-badge)
![ECE Engineer](https://img.shields.io/badge/⚡_ECE_Engineer-LNMIIT_2027-blue?style=for-the-badge)

</div>
