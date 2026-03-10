<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Yashraj%20Muthyapwar&fontSize=52&fontColor=ffffff&fontAlignY=38&desc=Building%20intelligent%20systems%20from%20raw%20data%20to%20production%20AI&descAlignY=60&descSize=17&descColor=a0c4d8" width="100%" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=18&duration=3500&pause=1500&color=2C9FE0&center=true&vCenter=true&multiline=false&width=700&lines=I+build+RAG+systems+that+work+beyond+the+demo;I+engineer+cloud+data+pipelines+on+AWS%2C+Azure+%26+GCP;I+turn+unstructured+data+into+reliable+LLM+applications;I+ship+agentic+tools+from+prototype+to+production)](https://github.com/Yashraj-Muthyapwar)

[![Email](https://img.shields.io/badge/Email-muthyapwaryashraj%40gmail.com-0f2027?style=flat-square&logo=gmail&logoColor=white)](mailto:muthyapwaryashraj@gmail.com)
</div>

I build **end-to-end intelligent systems** designing RAG pipelines, LLM agents, and agentic tools on the AI side, while architecting the **cloud data infrastructure** those systems depend on. My work spans **AWS, Azure, and GCP**, with a focus on retrieval quality, LLM observability, IaC-managed pipelines, and production reliability.

# Flagship Projects

## 🧠 FRAG-MED &nbsp;—&nbsp; Medical RAG with Hierarchical Retrieval

**`RAG`** &nbsp;**`Parent-Child Architecture`** &nbsp;**`Arize Phoenix`** &nbsp;**`Clinical QA`** &nbsp;**`LLM Observability`**

A **domain-specific RAG system for clinical question answering**, built on a hierarchical retrieval architecture with **parent-child document mapping**. Most RAG prototypes use flat vector search — this project directly addresses why those systems hallucinate in production: **context fragmentation**.

The system retrieves **fine-grained child chunks** for precision while injecting the **full parent document as context** into the LLM prompt. **Arize Phoenix** provides end-to-end LLM tracing and retrieval quality monitoring throughout the pipeline.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/FRAG-MED)

## 📚 NotionAtlas AI &nbsp;—&nbsp; Semantic Search & RAG over Notion

**`Qdrant`** &nbsp;**`Sentence Transformers`** &nbsp;**`Notion API`** &nbsp;**`RAG Pipeline`** &nbsp;**`Streamlit`**

An **end-to-end RAG pipeline** that indexes entire Notion workspaces and enables **natural language Q&A across thousands of pages**. The fully automated pipeline handles extraction → chunking → embedding → retrieval → LLM answer generation, with a Streamlit interface built for non-technical users.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/NotionAtlas-AI-Semantic-Search-And-RAG-Assistant-for-Notion)

## 🔍 LyteQuery &nbsp;—&nbsp; Conversational SQL Agent

**`LangChain`** &nbsp;**`Text-to-SQL`** &nbsp;**`LLM Agents`** &nbsp;**`Multi-table Schema`** &nbsp;**`Streamlit`**

An **agentic system** that converts plain-English business questions into **accurate SQL**, executes queries against relational databases, and returns clean human-readable summaries. Handles **multi-table schemas**, generates query explanations, and surfaces results in language any stakeholder can act on — removing the SQL barrier entirely.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/LyteQuery-AI-SQL-Agent)

# 🏗️ Data Infrastructure

## 🟠 AWS Retail Data Pipeline &nbsp;—&nbsp; IaC with Terraform

**`Terraform`** &nbsp;**`AWS Glue`** &nbsp;**`Amazon S3`** &nbsp;**`Amazon Athena`** &nbsp;**`AWS RDS`**

**Full implementation of the data engineering lifecycle on AWS**, built entirely with infrastructure-as-code. Extracts retail data from an **RDS OLTP** database, transforms it via **AWS Glue** into columnar Parquet on S3, and serves analytical queries through **Athena**. Every resource — IAM roles, Glue jobs, S3 buckets, RDS instances — provisioned and version-controlled with **Terraform**.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/aws-retail-data-pipeline)

## 🔷 AWS Governed Lakehouse &nbsp;—&nbsp; Apache Iceberg + Lake Formation

**`Apache Iceberg`** &nbsp;**`AWS Lake Formation`** &nbsp;**`Amazon Athena`** &nbsp;**`RBAC`** &nbsp;**`Amazon S3`**

A **governed data lakehouse on AWS** using **Apache Iceberg** as the open table format and **Lake Formation** for fine-grained role-based access control. Supports **ACID transactions**, schema evolution, and **time-travel queries** — production-grade patterns for regulated or multi-team data environments where governance is non-negotiable.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/aws-governed-lakehouse)

## 🔵 Azure E-Commerce Analytics Pipeline &nbsp;—&nbsp; Medallion Architecture

**`Azure Data Factory`** &nbsp;**`Databricks`** &nbsp;**`PySpark`** &nbsp;**`Synapse Analytics`** &nbsp;**`Power BI`**

End-to-end analytical pipeline spanning **ADF** for orchestration, **Databricks with PySpark** for transformation, and **Synapse Analytics** for serving. Implements **Bronze-Silver-Gold medallion architecture** — raw ingestion through OLTP-to-OLAP transformation to analytics-ready Gold layer consumed by **Power BI** dashboards.

[![View Repo](https://img.shields.io/badge/View%20Repo-0f2027?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yashraj-Muthyapwar/End-to-End-E-commerce-Analytics-Pipeline-on-Azure)

## 🎙️ Also Shipped

**PrepWise — AI Interview Simulator** &nbsp;·&nbsp; [View Repo](https://github.com/Yashraj-Muthyapwar/PrepWise-LinkedIn-Interview-AI)

A **Chrome extension** that auto-extracts job descriptions from LinkedIn and generates role-specific interview questions across technical, behavioral, and HR categories. **Whisper** handles speech-to-text; **GPT-4o** evaluates answers — the complete interview loop runs in-browser.

`GPT-4o` &nbsp;`OpenAI Whisper` &nbsp;`Chrome Extension` &nbsp;`LinkedIn Integration`

## 🛠 Tech Stack

**Languages & Core**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**AI / ML Frameworks**

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=flat-square&logo=openai&logoColor=white)

**RAG, Vector Databases & Observability**

![Qdrant](https://img.shields.io/badge/Qdrant-DC244C?style=flat-square)
![ChromaDB](https://img.shields.io/badge/ChromaDB-5C4EE5?style=flat-square)
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=flat-square)
![Arize Phoenix](https://img.shields.io/badge/Arize%20Phoenix-FF6B35?style=flat-square)
![Sentence Transformers](https://img.shields.io/badge/Sentence%20Transformers-009688?style=flat-square)

**Cloud & Data Engineering**

![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=flat-square&logo=apachespark&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-0070BB?style=flat-square)
![Databricks](https://img.shields.io/badge/Databricks-FF3621?style=flat-square&logo=databricks&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat-square&logo=dbt&logoColor=white)

**Infrastructure & DevOps**

![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)

**Databases**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

**APIs & Web**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer" width="100%" />
</div>
