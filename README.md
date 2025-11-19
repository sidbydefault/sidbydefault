# Hi there, I'm Sai Siddharth Duvvada 👋

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat&logo=linkedin)](https://linkedin.com/in/sai-siddharth-duvvada)

## 🚀 About Me

Hey! I'm a Machine Learning Engineer who actually likes debugging production systems at 2 AM (just kidding, I don't—but I've done it enough times). I build AI stuff that people can actually use, not just impressive Jupyter notebooks that die in staging.

Got my B.Tech and M.S. by Research from IIIT Hyderabad, where I learned that research papers and production code speak very different languages. These days I'm working with LLMs, RAG systems, and computer vision—basically teaching computers to read, remember, and see things. Sometimes it even works on the first try.

---

## 💼 Stuff I've Built

### 🏥 Clinical Trial MCP Server
*Making sense of clinical trials without losing patient data to the cloud*

Built this for healthcare institutions who (rightfully) don't want to send their patient data to random APIs. It's an MCP server that runs entirely on-premise, matching patients to clinical trials using vector search and some SQL magic.

**What it does:**
- Searches through 45K clinical trials using Milvus vector DB and matches them with 400K synthetic patient records in PostgreSQL. Turns out vector embeddings are pretty good at understanding medical jargon.
- Built a RAG pipeline that combines semantic search with actual SQL queries—because sometimes you just need to filter by age > 65, you know?
- Automatically generates eligibility criteria and recruitment lists. Saves a lot of manual Excel spreadsheet hell.
- Everything runs locally. HIPAA compliance isn't optional when you're dealing with health data.

The fun part was making Milvus and PostgreSQL play nice together—vector search for finding relevant trials, then complex SQL joins for the nitty-gritty filtering.

**Built with**: Python, Milvus, PostgreSQL, SQLModel, MCP Protocol, RAG

---

### 🛒 E-Commerce Data Analytics Platform
*When "just use Excel" stops being a viable option*

Built a proper data pipeline on Databricks because someone decided 180K customer records was too many for Google Sheets. Implements the whole medallion architecture thing (Bronze-Silver-Gold) that data engineers love talking about at conferences.

**What it actually does:**
- Processes streaming data with Delta Live Tables and PySpark. Added SCD Type 2 tracking so you can see what customers looked like six months ago when they actually liked your products.
- Created 13 different data quality checks. Turns out, bad data in = garbage insights out. Who knew?
- Built RFM segmentation to figure out which customers are worth keeping and which ones are just browsing. Split them into 8 cohorts—from "throws money at us" to "probably forgot their password."
- Product performance analytics across 5 tiers. Helps answer exciting questions like "why isn't this selling?" and "should we even stock this?"
- Wrote a synthetic data generator because testing with production data is how you end up on HackerNews for the wrong reasons.

The whole thing deploys with Databricks Asset Bundles, so you can break dev and prod independently. Modern MLOps, baby.

**Built with**: Databricks, PySpark, Delta Live Tables, SQL, Python, way too much YAML

---
## 🎓 Education

**IIIT Hyderabad** *(Aug 2017 - Dec 2022)*
B.Tech & M.S. by Research in Electronics and Communication Engineering
CGPA: 8.0/10

---

## 🔬 Research & Publications

**Published Work:**

📄 [**Structural and Functional Pathology in Cocaine Use Disorder**](https://doi.org/10.1016/j.pnpbp.2023.110862)
*Progress in Neuro-Psychopharmacology and Biological Psychiatry* (2024)
J. Rasgado-Toledo, **S. S. Duvvada**, et al.
*A multimodal fusion approach to understanding structural-functional pathology in substance use disorders*

---

## 🛠️ Technical Skills

### **Languages & Frameworks**
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=flat&logo=apache-spark&logoColor=white)

### **AI/ML Specializations**
- 🤖 **Large Language Models**: RAG, MCP Protocol, Fine-tuning, Prompt Engineering
- 🔍 **NLP & Information Retrieval**: Elasticsearch, Haystack, LangChain, LangGraph
- 👁️ **Computer Vision**: OpenCV, MediaPipe, Object Detection
- 📊 **Deep Learning**: GANs, Transformers, Hawkes Processes
- 📈 **Signal Processing**: PPG Analysis, Time-Series Forecasting

### **Data Engineering & MLOps**
- **Big Data Platforms**: Databricks, Delta Live Tables, Medallion Architecture
- **Vector Databases**: Milvus, ChromaDB, FAISS
- **Data Engineering**: PySpark, NumPy, Pandas, SQLModel
- **Databases**: PostgreSQL, SQL Server
- **MLOps Tools**: MLflow, Databricks Asset Bundles, Docker, fastAPI
- **Deployment**: Docker, REST APIs, CI/CD Pipelines

---

## 🌟 Currently Obsessed With

- Building RAG systems that don't hallucinate medical advice (harder than it sounds)
- Making large-scale data pipelines that actually finish running before the heat death of the universe
- Contributing to open-source when I'm not fighting with Docker containers
- Figuring out how to make vector databases and SQL databases be friends
- Trying to convince people that "just prompt ChatGPT" isn't always the solution

---

## 📫 Let's Connect!

Always up for chatting about ML projects, debugging production nightmares, or why your model works on your laptop but nowhere else.

- 💼 [LinkedIn](https://linkedin.com/in/sai-siddharth-duvvada)
- 📧 Hit me up for collabs, opportunities, or hot takes on the latest AI hype

---

<div align="center">

### ⚡ "Building AI that works in production, not just in notebooks"

![Profile Views](https://komarev.com/ghpvc/?username=sidbydefault&color=blue&style=flat)

</div>
