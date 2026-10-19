<div align="center">

# Guilherme Henrique Mendes

**Junior Data Analyst · Analytics Engineer · BI**

*Quantitative rigor (UFF Mathematics + 6x military admissions) · Production data engineering · Stakeholder communication*

<p>
  <a href="./README.md"><strong>🇧🇷 Português</strong></a> &nbsp;|&nbsp; <strong>🇺🇸 English</strong>
</p>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ghmendes02-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ghmendes02/)
[![GitHub](https://img.shields.io/badge/GitHub-StylishGH-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/StylishGH)
[![Email](https://img.shields.io/badge/Email-guiguimendes2002%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:guiguimendes2002@gmail.com)
[![Location](https://img.shields.io/badge/Mesquita--RJ-Brazil-009c3b?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## 📌 About Me

I am a **B.Sc. in Mathematics (Teaching Track) undergraduate at Universidade Federal Fluminense (UFF/CEDERJ)**, building production-grade data systems and analytical pipelines that go far beyond sandbox notebooks. My academic foundation is grounded in **linear algebra, calculus, statistical inference, and mathematical optimization**, paired with daily hands-on practice in **ETL, relational data modeling (PostgreSQL / analytical SQL), machine learning, and cloud deployment**.

I achieved admission into highly competitive Brazilian military academies known for rigorous quantitative standards:
- ⚓ **EFOMM (Merchant Marine Officers School)** — Admitted **twice** (Calculus, Physics, Linear Algebra, and English).
- ✈️ **EEAr (Aeronautics Specialists School)** — Admitted **3 times**.
- 🎖️ **ESA (Army Sergeants School)** — Admitted **1 time**.

This background shaped my discipline, high-stakes resilience, and structured analytical mindset to dissect and solve complex quantitative problems under pressure.

Furthermore, my experience as a **private mathematics and physics tutor** forged a core business skill: **stakeholder communication** — translating dense mathematical formulas and abstract metrics into actionable, intuitive insights for business decision-makers.

---

## 🛠️ Technical Stack

<div align="center">

![Python](https://img.shields.io/badge/Python-3.12-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-Advanced_CTEs_&_Windows-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-1.5-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-0.115-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-1.40-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-pgvector-3ECF8E?style=for-the-badge&logo=supabase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-Flow-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## 🚀 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📐 LemmaS — Adaptive EdTech & Math Intelligence Platform</h3>
      <p align="center"><em>Production platform integrating vector search, SM-2 spaced repetition, and multi-provider Socratic AI tutoring</em></p>
      <ul>
        <li><strong>Real-world Scale:</strong> <strong>21,272 questions</strong> cataloged from official military boards and <strong>2,000 axiomatic lemmas</strong> mapped in Supabase PostgreSQL.</li>
        <li><strong>Automated ETL Pipeline:</strong> PDF ingestion via <code>PyMuPDF</code>, native XObject figure extraction, and strict taxonomic classification by exam board and difficulty.</li>
        <li><strong>Socratic AI Engine:</strong> Multi-provider architecture (Gemini 2.5 Flash + NVIDIA NIM) with resilient fallbacks, latency caching, and LaTeX sanitization.</li>
        <li><strong>Vector Search & SM-2:</strong> Semantic embeddings via <code>pgvector</code> (HNSW indexing) for sub-100ms retrieval and SM-2 algorithm for long-term knowledge retention.</li>
      </ul>
      <p align="center">
        <a href="https://lemmas-ochre.vercel.app/dashboard"><strong>🌐 Live Web App</strong></a> ·
        <a href="https://github.com/StylishGH/LemmaS"><strong>📦 Source Code</strong></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">📈 Predictive Analysis & Clustering of B3 Companies</h3>
      <p align="center"><em>End-to-end financial data pipeline, K-Means clustering, and balance-sheet resilience classification</em></p>
      <ul>
        <li><strong>Data Ingestion & Cleaning:</strong> Extracted and standardized public financial statements from the Brazilian SEC (<strong>CVM</strong>) for hundreds of publicly traded companies.</li>
        <li><strong>Feature Engineering:</strong> Computed key valuation multiples (P/E, P/BV, EV/EBITDA) and liquidity indicators (Current Ratio, Net Debt/EBITDA); treated outliers using IQR.</li>
        <li><strong>Unsupervised & Supervised ML:</strong> Segmented assets via <strong>K-Means</strong> (validated with Elbow and Silhouette methods) and trained <strong>Random Forest</strong> classifiers.</li>
        <li><strong>Interactive Dashboard:</strong> Delivered a responsive <strong>Streamlit</strong> web dashboard featuring dynamic filtering, interactive Plotly charts, and sortable financial tables.</li>
      </ul>
      <p align="center">
        <a href="https://ghmendes.streamlit.app"><strong>🌐 Live Dashboard</strong></a> ·
        <a href="https://github.com/StylishGH/Empresas-B3-analise-de-dados"><strong>📦 Source Code</strong></a>
      </p>
    </td>
  </tr>
</table>

---

## 🧠 Data Philosophy & Analytical Principles

| Principle | Practical Implementation |
| :--- | :--- |
| **Statistical Rigor** | Stratified k-fold cross-validation, confidence intervals, and hypothesis testing to prevent spurious correlations. |
| **Data Quality & Integrity (ETL)** | 80% of analytical success depends on data preparation: strict type validation, justified imputation, and zero data leakage. |
| **Explainability & Business Value** | Every machine learning model must solve a concrete business problem; leverage Feature Importance and translate metrics into ROI terms. |
| **Reproducibility** | Containerized environments (Docker), pinned dependencies, and clean modular code versioned via Git. |

---

## 🎯 Education & Distinctions

- 🎓 **B.Sc. in Mathematics (Teaching Track)** — Universidade Federal Fluminense (UFF / CEDERJ) *(Expected graduation: 2027)*
- ⚓ **EFOMM** — Admitted 2x *(Calculus, Physics, Linear Algebra, and English)*
- ✈️ **EEAr** — Admitted 3x
- 🎖️ **ESA** — Admitted 1x
- 🌐 **Languages:** Portuguese (Native) · English (Fluent technical reading, intermediate written/spoken communication)

---

## 📬 Contact & Open Opportunities

Actively seeking entry-level full-time opportunities as a **Junior Data Analyst**, **Analytics Engineer**, or **BI Analyst**.

- 💼 **LinkedIn:** [linkedin.com/in/ghmendes02](https://www.linkedin.com/in/ghmendes02/)
- 📧 **Professional Email:** [guiguimendes2002@gmail.com](mailto:guiguimendes2002@gmail.com)
- 🐙 **GitHub:** [github.com/StylishGH](https://github.com/StylishGH)
- 📍 **Location:** Mesquita, RJ — Open to **Remote** and **Hybrid/On-site in Rio de Janeiro**.

<div align="center">
  <sub>"I reduce decision costs under uncertainty by uniting quantitative rigor, stakeholder communication, and production data engineering."</sub>
</div>
