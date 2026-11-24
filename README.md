<p align="center">
  <img src="assets/banner.svg" width="100%" alt="Emna Ben Othman - AI Engineering Student" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/emna-benothman"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://github.com/emna-benothman"><img src="https://img.shields.io/badge/GitHub-6d28d9?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="mailto:emna.benothman@esprit.tn"><img src="https://img.shields.io/badge/Email-ec4899?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Open_to-Opportunities-10b981?style=for-the-badge" alt="Open to opportunities" />
</p>

<p align="center">
  <a href="https://github.com/emna-benothman">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1200&color=22D3EE&center=true&vCenter=true&width=640&lines=AI+Engineering+student+at+ESPRIT;LLM+workflows+and+applied+machine+learning;C%2B%2B+%C2%B7+Python+%C2%B7+Django+%C2%B7+Qt;Competitive+programmer+%E2%80%94+TCPC+2026" alt="Typing headline" />
  </a>
</p>

---

## 👋 About

AI engineering student at **ESPRIT School of Engineering** (Tunisia, **class of 2029**). I combine object-oriented software engineering, data systems, and applied AI to build reliable, production-minded software.

- 🩸 Building **LifeLink**, a blood-donation logistics platform (Django)
- 🧠 Chaining LLMs with live data sources for grounded, schema-driven reasoning
- 🏆 Competing in algorithmic contests (TCPC 2026, INSAT Winter Cup)
- 🚀 Looking for **AI and data engineering** internships and opportunities

---

## 🚀 Featured Projects

| Project | Summary | Stack |
| :-- | :-- | :-- |
| 🐟 **DataDock**<br/>Smart fishing port management | Desktop platform with role-based access (3 user tiers) and traceability for 15+ vessels. Dynamic pricing engine chaining Gemini with live weather and fishing-activity data, plus a contextual chatbot and CRUD dashboards. | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=flat-square&logo=qt&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle_11g-F80000?style=flat-square&logo=oracle&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=google&logoColor=white) |
| 🩸 **LifeLink**<br/>Blood donation coordination | Web platform connecting blood banks, donors, collection centres, and clinics. Focus on blood-unit traceability, automated urgency matching, and appointment workflows. *In active development.* | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| 🛒 **Olist Analytics**<br/>E-commerce BI and ML | Data warehouse staging architecture for 100,000+ orders, with ETL cleaning and dimensional modeling. Supervised and unsupervised models for customer behavior analysis. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white) |
| 🧸 **Paxora Kids**<br/>EdTech storefront | Owned the backend finance module: relational MySQL schema and PHP CRUD APIs for a 20+ SKU store. Stripe payment simulation and Leaflet.js pickup map. Built in a 4-person Agile team. | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

> 🔒 DataDock and Paxora Kids are academic team projects hosted in private faculty repositories.

<details>
<summary><b>🐟 DataDock architecture</b></summary>

```mermaid
flowchart LR
    subgraph ext [External data]
        A[Global Fishing Watch API]
        B[OpenMeteo marine weather]
    end
    subgraph core [Platform core]
        C[Vessel sensor stream] --> D[Gemini reasoning engine]
        A --> D
        B --> D
        D --> E[Dynamic pricing engine]
        E --> F[Qt 6 / C++ operator GUI]
        G[(Oracle 11g)] <--> F
    end
    style A fill:#0e7490,stroke:#22d3ee,color:#fff
    style B fill:#0e7490,stroke:#22d3ee,color:#fff
    style C fill:#334155,stroke:#94a3b8,color:#fff
    style D fill:#6d28d9,stroke:#a78bfa,color:#fff
    style E fill:#be185d,stroke:#f472b6,color:#fff
    style F fill:#15803d,stroke:#4ade80,color:#fff
    style G fill:#b91c1c,stroke:#f87171,color:#fff
```

- **Architecture:** MVC in C++ with Qt; signals and slots for asynchronous API polling.
- **Database:** Oracle 11g schemas with triggers, sequence-generated keys, and transactional safety.
- **Security:** authentication and privilege checks across Port Master, Fleet Operator, and Market Analyst roles.

</details>

<details>
<summary><b>🩸 LifeLink details</b></summary>

- **Logistics:** cold-chain tracking for blood units, with status indicators and expiration countdowns.
- **Matching:** pairs rare blood requests with nearby available donors.
- **Process:** bi-weekly Agile Scrum sprints, protected branches, and code review.

</details>

<details>
<summary><b>🛒 Olist Analytics details</b></summary>

- **ETL:** cleaned heterogeneous CSVs into staging tables, handling foreign keys and null values.
- **Modeling:** customer lifetime value regression and RFM segmentation with scikit-learn.

</details>

<details>
<summary><b>🧸 Paxora Kids details</b></summary>

- **Finance:** transactional consistency for order totals, taxes, and simulated Stripe webhooks.
- **Maps:** interactive partner pickup locations with custom Leaflet.js markers.

</details>

---

## 🛠️ Technical Skills

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![LaTeX](https://img.shields.io/badge/LaTeX-008080?style=flat-square&logo=latex&logoColor=white)

**AI and Machine Learning**

![Gemini](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=google&logoColor=white)
![LLM](https://img.shields.io/badge/LLM_Orchestration-10A37F?style=flat-square&logo=openai&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Machine Learning](https://img.shields.io/badge/Machine_Learning-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Deep Learning](https://img.shields.io/badge/Deep_Learning-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Colab](https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

**Data and Databases**

![Oracle](https://img.shields.io/badge/Oracle_11g-F80000?style=flat-square&logo=oracle&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Data Warehousing](https://img.shields.io/badge/Data_Warehousing-0ea5e9?style=flat-square&logo=databricks&logoColor=white)
![ETL](https://img.shields.io/badge/ETL_Pipelines-00897B?style=flat-square&logo=apache-airflow&logoColor=white)
![BI](https://img.shields.io/badge/Business_Intelligence-F2C811?style=flat-square&logo=powerbi&logoColor=black)
![Data Modeling](https://img.shields.io/badge/Data_Modeling-5C6BC0?style=flat-square&logo=diagramsdotnet&logoColor=white)

**Frameworks and APIs**

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=flat-square&logo=qt&logoColor=white)
![SDL](https://img.shields.io/badge/SDL_1.2-1774A0?style=flat-square&logo=c&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat-square&logo=bootstrap&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet.js-199900?style=flat-square&logo=leaflet&logoColor=white)
![REST](https://img.shields.io/badge/REST_APIs-009688?style=flat-square&logo=fastapi&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![OpenMeteo](https://img.shields.io/badge/OpenMeteo-FFA500?style=flat-square&logo=accuweather&logoColor=white)

**Tooling**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-6d28d9?style=flat-square&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visual-studio-code&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Agile](https://img.shields.io/badge/Agile_Scrum-205493?style=flat-square&logo=jira&logoColor=white)

---

## 🏆 Achievements

<table width="100%">
  <tr>
    <td width="33%" align="center">
      <img src="https://img.shields.io/badge/TCPC_2026-f59e0b?style=for-the-badge" alt="TCPC 2026" /><br /><br />
      <b>30th of 96+ teams</b><br />
      1st among private engineering schools in Tunisia
    </td>
    <td width="33%" align="center">
      <img src="https://img.shields.io/badge/INSAT_Winter_Cup-06b6d4?style=for-the-badge" alt="INSAT Winter Cup" /><br /><br />
      <b>Top 12 of 60+ teams</b><br />
      2025–2026 season
    </td>
    <td width="33%" align="center">
      <img src="https://img.shields.io/badge/Academics-10b981?style=for-the-badge" alt="Academics" /><br /><br />
      <b>16.12 / 20 average</b><br />
      19.25 / 20 on an advanced C++ OO project
    </td>
  </tr>
</table>

---

## 💼 Experience

**Educational Content Contributor and Front-End Support** · TAGEUP · ![Apr–Sep 2026](https://img.shields.io/badge/Apr_–_Sep_2026-6d28d9?style=flat-square)
Structured online TAGE MAGE learning curricula and contributed core front-end features to the web platform.

**IT Engineering Intern** · CTAMA Assurances · ![Summer 2024](https://img.shields.io/badge/Summer_2024-0ea5e9?style=flat-square)
Technical support in an enterprise environment: IT maintenance, database queries, and system operations.

## 🎓 Education

**Engineering Cycle, Artificial Intelligence** · ESPRIT School of Engineering · ![Class of 2029](https://img.shields.io/badge/Class_of_2029-ec4899?style=flat-square)

## 🌐 Languages

![Arabic](https://img.shields.io/badge/Arabic-Native-16a34a?style=flat-square)
![French](https://img.shields.io/badge/French-Fluent-2563eb?style=flat-square)
![English](https://img.shields.io/badge/English-Full_Professional-7c3aed?style=flat-square)
![Spanish](https://img.shields.io/badge/Spanish-A1-f59e0b?style=flat-square)

---

## 🧭 Working Principles

- 🏗️ **Disciplined design:** strict typing, defensive input handling, and clean OO patterns before added complexity.
- 🧠 **Grounded AI:** LLMs tied to structured schemas and verified data, with robust fallback logic.
- 🤝 **Team hygiene:** feature branches, atomic commits, clear relational modeling, Agile delivery.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b1020,50:1e1b4b,100:4c1d95&height=90&section=footer" width="100%" alt="" />
</p>
