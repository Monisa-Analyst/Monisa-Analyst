# Hi, I'm Monisa 👋

I am a Data Analyst and Cybersecurity Automation enthusiast. I enjoy cleaning messy datasets, designing relational database models, and building interactive security triage tools. My technical focus is on **Python, SQL, Power BI, and Streamlit**. 

Lately, I've been focusing on bridging the gap between data engineering and security operations by building automated pipelines that parse raw event logs, enrich them with real-time threat intelligence, and summarize findings using generative AI.

---

## 🛠️ Skills & Technologies

*   **Languages:** Python (Pandas, NumPy, requests), SQL (PostgreSQL, SQLite, MySQL)
*   **Data Visualization & BI:** Power BI (Data Modeling, Star Schemas, DAX), Streamlit, Plotly, Seaborn
*   **Security & Operations:** Log analysis, threat intelligence correlation, MITRE ATT&CK mapping, Git, Bash

---

## 🚀 Featured Projects

### 1. Sales Insights & AI Query Assistant
A complete data engineering and business intelligence project. It processes a raw e-commerce dataset, normalizes it into a star schema database, and builds an interactive dashboard complete with an AI-powered conversational SQL assistant.

*   👉 **[Click to Open Live Web Application](https://share.streamlit.io/monisa-analyst/sales-insights-dashboard/main/src/app.py)**
*   📁 **[GitHub Repository](https://github.com/Monisa-Analyst/sales-insights-dashboard)**
*   **Key Highlights:**
    *   **ETL Pipeline:** Wrote Python and Pandas scripts to clean and parse ~50,000 messy sales records.
    *   **Star Schema Database:** Designed and built a 5-table relational SQLite database with structured primary/foreign keys and query indexes.
    *   **Interactive Analytics:** Built a multi-page Streamlit interface with Plotly charts visualizing trends, top customers, category share, and regional sales.
    *   **AI SQL Generator:** Connected the Gemini API to let users query the database using plain English. Wrote a custom regex-based SQL fallback engine to handle API quota limits gracefully.
    *   **Advanced SQL:** Developed standalone analytical queries featuring CTEs, multi-table joins, and window functions (e.g., `LAG` for MoM growth, `DENSE_RANK` for customer value).

---

### 2. Sentinel: SOC Alert Ingestion & Triage Platform
An automation tool built to help Tier-1 Security Operations Center (SOC) analysts ingest, enrich, and prioritize security alerts.

*   👉 **[Click to Open Live Web Application](https://share.streamlit.io/monisa-analyst/ai-soc-analyst/main/app.py)**
*   📁 **[GitHub Repository](https://github.com/Monisa-Analyst/ai-soc-analyst)**
*   **Key Highlights:**
    *   **Enrichment Pipeline:** Integrates VirusTotal API v3 for live IP reputation lookups, returning ASN details, geographical location, and detection counts.
    *   **Local Threat Intel:** Built a custom correlation engine that flags malicious subnet blocks, maps IPs to geopolitical risk levels, and attributes activity to threat actors (e.g., Fancy Bear, TA505).
    *   **Risk Scoring:** Designed a composite risk engine scoring security alerts from 0 to 100 based on initial severity, VT verdicts, and event type weight.
    *   **Framework Mapping:** Automatically maps alerts to MITRE ATT&CK techniques (over 40 rules) and identifies the corresponding Cyber Kill Chain phase.
    *   **AI Analyst Notes:** Uses GPT-3.5-turbo (with an offline rule-based fallback) to generate structured threat assessments, indicators, and playbooks.
    *   **Export & Audits:** Generates compliance-ready plain-text and JSON incident reports, with structured logs formatted in JSON Lines (JSONL).

---

## 📬 Contact & Connections

*   **Email:** [monisa.asi@gmail.com](mailto:monisa.asi@gmail.com)
*   **LinkedIn:** [linkedin.com/in/monisa-l-333546366](https://www.linkedin.com/in/monisa-l-333546366)
*   **GitHub:** [github.com/Monisa-Analyst](https://github.com/Monisa-Analyst)
