<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:6d28d9&height=200&section=header&text=Emna%20Ben%20Othman&fontColor=ffffff&fontSize=44&fontAlignY=38&desc=AI%20Engineering%20Student%20%C2%B7%20Applied%20ML%20%C2%B7%20Software%20Engineering&descSize=17&descAlignY=60" width="100%" alt="Emna Ben Othman" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/emna-benothman"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:emna.benothman@esprit.tn"><img src="https://img.shields.io/badge/Email-1f2937?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Based_in-Ariana%2C_Tunisia-374151?style=flat-square&logo=googlemaps&logoColor=white" alt="Location" />
  <img src="https://img.shields.io/badge/Status-Open_to_opportunities-16a34a?style=flat-square" alt="Open to opportunities" />
</p>

<p align="center">
  <a href="https://github.com/emna-benothman">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&duration=3000&pause=1200&color=6D28D9&center=true&vCenter=true&width=640&lines=AI+Engineering+student+at+ESPRIT;LLM+workflows+and+applied+machine+learning;C%2B%2B+%C2%B7+Python+%C2%B7+Django+%C2%B7+Qt;Competitive+programmer+%E2%80%94+TCPC+2026" alt="Typing headline" />
  </a>
</p>

---

## About

Third-year AI engineering student at **ESPRIT School of Engineering** (Tunisia, class of 2027). I combine object-oriented software engineering, data systems, and applied AI to build reliable, production-minded software.

- Building **LifeLink**, a blood-donation logistics platform (Django)
- Chaining LLMs with live data sources for grounded, schema-driven reasoning
- Competing in algorithmic programming contests (TCPC 2026, INSAT Winter Cup)
- Looking for **AI and data engineering** internships and opportunities

---

## Featured Projects

| Project | Summary | Stack |
| :-- | :-- | :-- |
| **DataDock**<br/>Smart fishing port management | Desktop platform with role-based access (3 user tiers) and traceability for 15+ vessels. Dynamic pricing engine chaining Gemini with live weather and fishing-activity data, plus a contextual chatbot and CRUD dashboards. | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![Qt](https://img.shields.io/badge/Qt_6-41CD52?style=flat-square&logo=qt&logoColor=white) ![Oracle](https://img.shields.io/badge/Oracle_11g-F80000?style=flat-square&logo=oracle&logoColor=white) ![Gemini](https://img.shields.io/badge/Gemini_API-8E75C2?style=flat-square&logo=google&logoColor=white) |
| **LifeLink**<br/>Blood donation coordination | Web platform connecting blood banks, donors, collection centres, and clinics. Focus on blood-unit traceability, automated urgency matching, and appointment workflows. *In active development.* | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |
| **Olist Analytics**<br/>E-commerce BI and ML | Data warehouse staging architecture for 100,000+ orders, with ETL cleaning and dimensional modeling. Supervised and unsupervised models for customer behavior analysis. | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white) ![Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white) |
| **Paxora Kids**<br/>EdTech storefront | Owned the backend finance module: relational MySQL schema and PHP CRUD APIs for a 20+ SKU store. Stripe payment simulation and Leaflet.js pickup map. Built in a 4-person Agile team. | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white) ![JS](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) |

> DataDock and Paxora Kids are academic team projects hosted in private faculty repositories.

<details>
<summary><b>DataDock architecture</b></summary>

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
```

- **Architecture:** MVC in C++ with Qt; signals and slots for asynchronous API polling.
- **Database:** Oracle 11g schemas with triggers, sequence-generated keys, and transactional safety.
- **Security:** authentication and privilege checks across Port Master, Fleet Operator, and Market Analyst roles.

</details>

<details>
<summary><b>LifeLink details</b></summary>

- **Logistics:** cold-chain tracking for blood units, with status indicators and expiration countdowns.
- **Matching:** pairs rare blood requests with nearby available donors.
- **Process:** bi-weekly Agile Scrum sprints, protected branches, and code review.

</details>

<details>
<summary><b>Olist Analytics details</b></summary>

- **ETL:** cleaned heterogeneous CSVs into staging tables, handling foreign keys and null values.
- **Modeling:** customer lifetime value regression and RFM segmentation with scikit-learn.

</details>

<details>
<summary><b>Paxora Kids details</b></summary>

- **Finance:** transactional consistency for order totals, taxes, and simulated Stripe webhooks.
- **Maps:** interactive partner pickup locations with custom Leaflet.js markers.

</details>

---

## Technical Skills

| Area | Technologies |
| :-- | :-- |
| **Languages** | Python · C++ · C · JavaScript · PHP · SQL · Bash · HTML/CSS · LaTeX |
| **AI and ML** | Google Gemini API · LLM orchestration · scikit-learn · Machine Learning · Deep Learning · Pandas · NumPy · Matplotlib · Jupyter · Google Colab |
| **Data** | Oracle 11g · MySQL · SQLite · Data warehousing · ETL pipelines · Business intelligence · Data modeling |
| **Frameworks** | Django · Qt 6 / Qt Creator · SDL 1.2 · Bootstrap 5 · Leaflet.js |
| **APIs** | REST · Stripe · OpenMeteo · Global Fishing Watch · Postman |
| **Tooling** | Git · GitHub · VS Code · Linux · Agile Scrum |

---

## Achievements

| | |
| :-- | :-- |
| **TCPC 2026** | 30th of 96+ teams, and 1st among private engineering schools in Tunisia |
| **INSAT Winter Cup 2025–2026** | Top 12 of 60+ teams |
| **Academics** | 16.12/20 average, and 19.25/20 on an advanced C++ object-oriented project |

---

## Experience

**Educational Content Contributor and Front-End Support** · TAGEUP · *Apr – Sep 2026*
Structured online TAGE MAGE learning curricula and contributed core front-end features to the web platform.

**IT Engineering Intern** · CTAMA Assurances · *Summer 2024*
Technical support in an enterprise environment: IT maintenance, database queries, and system operations.

## Education

**Engineering Cycle, Artificial Intelligence** · ESPRIT School of Engineering · *Expected 2027*

## Languages

Arabic (native) · French (fluent) · English (full professional) · Spanish (A1)

---

## Working Principles

- **Disciplined design:** strict typing, defensive input handling, and clean OO patterns before added complexity.
- **Grounded AI:** LLMs tied to structured schemas and verified data, with robust fallback logic.
- **Team hygiene:** feature branches, atomic commits, clear relational modeling, Agile delivery.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:6d28d9&height=90&section=footer" width="100%" alt="" />
</p>
