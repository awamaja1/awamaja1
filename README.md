# Hi there, I'm [Nama Anda] 👋
**AI Automation Engineer | Software Engineering Undergraduate | ML Researcher**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/username-anda)
[![Email](https://img.shields.io/badge/Email-Contact_Me-red?style=flat&logo=gmail)](mailto:email-anda@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_My_Web-green?style=flat&logo=googlechrome)](https://link-portofolio-anda.com)

I am a highly motivated Software Engineering undergraduate with a **hands-on builder mentality**. I specialize in designing production-grade **workflow automations**, deploying **Agentic AI systems**, and implementing **parameter-efficient fine-tuning (PEFT)** for Large Language Models. 

I thrive on bridging the gap between business operational pain points and robust technical solutions—building reliable systems that handle massive data synchronizations, edge cases, and API limits efficiently.

---

## 🛠️ Technical Arsenal

### **AI & Machine Learning**
- **LLM Infrastructure:** QLoRA Fine-tuning, Unsloth, HuggingFace, Model Evaluation (IndoMMLU, ROUGE-L, BERTScore, DIFF-EPITOME)
- **Agentic AI & Engineering:** Prompt Engineering, Model Context Protocol (MCP), Agent Development Kit (ADK), RAG concepts
- **Classical ML & Deep Learning:** BiLSTM, Random Forest, K-Means Clustering, TruncatedSVD, CRISP-DM Methodology

### **Workflow Automation & Integration**
- **Platforms:** n8n (Self-hosted/Cloud), Microsoft Power Automate
- **Scripting:** Google Apps Script, custom JavaScript code nodes
- **APIs:** REST API consumption & development, Webhooks, WhatsApp Business API (WAHA)

### **Software Engineering Stack**
- **Backend:** Python (FastAPI, Django REST Framework), Node.js
- **Frontend:** Next.js 15, React 19, TypeScript, Tailwind CSS
- **Infrastructure & DevOps:** Docker, Google Cloud Run, Vercel, Linux VPS, Git

---

## 🚀 Featured Projects

### 🧠 LLM Infrastructure & Deep Learning
*   **Customer Sentiment Analysis Engine (BiLSTM)**
    *   Engineered an end-to-end NLP pipeline using **BiLSTM** and **FastText Indonesian embeddings** to extract insights from >10,000 scraped Google Play Store reviews.
    *   Tackled minority class imbalance through SMOTE and achieved highly robust test accuracy for real-world text-label contradictions.
*   **Bank Transaction Clustering & Classification**
    *   Analyzed complex banking data using Unsupervised Learning (**K-Means**) to identify distinct customer profiles and Supervised Learning (**Decision Tree/Random Forest**) for cluster prediction with 98% accuracy.

### ⚙️ Workflow Automation & Systems Integration
*   **Automated Document Monitoring System (AIL)**
    *   Engineered a hybrid automation system integrating **Google Sheets** and **Microsoft OneDrive** to monitor real-time document pipelines without system timeouts.
    *   Invented a **"Ninja Email Webhook"** batching strategy in Power Automate and implemented **"Turbo Sync"** (Hash Map caching) in JavaScript to synchronize hundreds of rows in under 5 seconds.
*   **End-to-End WhatsApp Chatbot Workflow**
    *   Deployed an automated data request workflow utilizing **n8n** and WAHA webhooks.
    *   Authored custom **JavaScript code nodes** inside n8n to accurately parse complex JSON message payloads and format dynamic structured bot responses.

### 🤖 Agentic AI & Serverless APIs
*   **QuickBrief AI – Serverless Text Summarization Agent**
    *   Built a production-ready HTTP REST API via **FastAPI**, **Docker**, and **Google Cloud Run** to summarize large volumes of text in under 2 seconds using Google's Gemini LLM.
    *   Features robust error handling, edge-case fallback, and scalable zero-config deployment.
*   **E-Commerce Revenue Insight Agent**
    *   Architected an Agentic workflow integrating the **Model Context Protocol (MCP)** to securely extract structured data from BigQuery SQL databases. 
    *   Allows the LLM to autonomously retrieve deterministic sales data and generate grounded operational insights.

### 💻 Full-Stack & Backend Engineering
*   **CredexAI – Full-Stack AI Credit Scoring Platform**
    *   Developed a frontend-first application for alternative SME credit scoring using **Next.js 15, React 19, and TypeScript**.
    *   Integrated **Azure AI Language** with strict payload validation (**Zod**) and engineered a deterministic fallback mechanism to gracefully handle AI service timeouts.
*   **Dual-Stakeholder Recommendation System (TIPDONG)**
    *   Designed a zero-shot cross-domain ML recommendation system (SVD & Random Forest) for a campus food ordering platform, deployed as REST APIs on HuggingFace Spaces.

---

## 📜 Publications & Research

**QLoRA Fine-Tuned Gemma-2 Model for Affective Intervention**  
*International Journal of Advances in Data and Information Systems (IJADIS) – Accepted with Major Revisions*
- Authored a research paper on parameter-efficient fine-tuning (PEFT) of the 9-billion parameter **Gemma-2 LLM** utilizing **QLoRA** (4-bit NF4 precision) and the **Unsloth** framework.
- Constructed a synthetic data distillation pipeline formatted into strict *Instruction-Input-Output* triplets.
- Successfully mitigated catastrophic forgetting mathematically—boosting task-adjacent linguistic stability (ROUGE-L +23.34%, BERTScore +4.79%) while maintaining a robust **60.6% zero-shot accuracy** on the IndoMMLU benchmark.
