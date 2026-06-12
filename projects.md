# My Projects

## Index

- [Customer Churn Predictor](#customer-churn-predictor)
- [EV Charging Station Usage Analysis](#ev-charging-station-usage-analysis)
- [InfoPal](#infopal)
- [UniOps](#uniops)
- [Emotion-Satisfaction Analysis](#emotion-satisfaction-analysis)
- [HealthyPaws](#healthypaws)
- [MerNote](#mernote)
- [BusyBus](#busybus)
- [CookBook](#cookbook)

### Customer Churn Predictor

#### Description

End-to-end ML system that predicts customer churn with 80% accuracy using Logistic Regression. Built sklearn pipeline with preprocessing, LLM integration via OpenRouter for AI-generated retention recommendations. Identified $1.3M+ at-risk revenue with risk scoring (HIGH/MEDIUM/LOW) and interactive Streamlit dashboard.

#### Technologies

- **ML & Processing:** Scikit-learn, Pandas, Python
- **Explainability & API:** FastAPI
- **Dashboard:** Streamlit, Plotly
- **LLM:** OpenRouter

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?logo=scikit-learn&logoColor=white&style=for-the-badge) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white&style=for-the-badge) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white&style=for-the-badge)

---

### EV Charging Station Usage Analysis

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/EV-Charging-Data-Warehouse-BI-System)

#### Description

Performed end-to-end analysis on 200K+ EV charging records to identify usage patterns, energy trends, and station performance insights. Built ETL workflows and interactive dashboards for business intelligence reporting.

**Period:** 2026 Feb – Apr

#### Technologies

- **ETL & Data Warehousing:** SQL Server, SSIS for building ETL workflows and dimensional modeling.
- **Analytics & BI:** SSAS for OLAP cubes, Power BI for interactive dashboards and reporting.
- **Data Processing:** Python for additional data preprocessing and analysis tasks.

![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge) ![SSIS](https://img.shields.io/badge/SSIS-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge) ![SSAS](https://img.shields.io/badge/SSAS-CC2927?logo=microsoft-sql-server&logoColor=white&style=for-the-badge) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?logo=power-bi&logoColor=black&style=for-the-badge) ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge)

#### Screenshots

| ![EV Charging Analysis](projects/ev-charging-1.png) |
| :-------------------------------------------------: |

---

### InfoPal

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/my-infoPal)

#### Description

Built a prototype Retrieval-Augmented Generation (RAG) pipeline for document-based question answering using a local LLM setup. Implemented document ingestion, semantic search using FAISS, and context-aware response generation using Mistral-7B.

**Period:** 2026 Jan

#### Key Features

- **Document Ingestion:** Process and chunk documents for efficient retrieval.
- **Semantic Search:** FAISS-based vector search for relevant document retrieval.
- **Context-Aware Generation:** Mistral-7B LLM for generating accurate responses based on retrieved context.
- **Interactive UI:** Streamlit-based interface for easy document upload and querying.

#### Technologies

- **RAG Pipeline:** Python for core RAG implementation and orchestration.
- **Vector Search:** FAISS for efficient similarity search on document embeddings.
- **Embeddings:** Sentence Transformers for generating semantic document representations.
- **LLM:** Mistral-7B for context-aware response generation.
- **Frontend:** Streamlit for rapid prototyping and interactive user interface.

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white&style=for-the-badge) ![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?logo=streamlit&logoColor=white&style=for-the-badge) ![FAISS](https://img.shields.io/badge/FAISS-000000?logo=meta&logoColor=white&style=for-the-badge) ![Mistral](https://img.shields.io/badge/Mistral-7B-FF6B6B?logo=mistral&logoColor=white&style=for-the-badge)

#### Screenshots

| ![InfoPal 1](projects/infopal-1.png) | ![InfoPal 2](projects/infopal-2.png) | ![InfoPal 3](projects/infopal-3.png) |
| :----------------------------------: | :----------------------------------: | :----------------------------------: |

---

### UniOps

#### Description

University facility management system with resource booking, incident ticketing, and real-time notifications. My contribution: Module A (Facilities & Assets Catalogue) – full stack development including 13 RESTful API endpoints with Spring Boot, role-based access control, and React admin dashboard with advanced filtering, real-time analytics, and PDF export. Optimized performance with debounced search and MongoDB indexing.

**Period:** 2026 Feb – Apr

#### Technologies

- **Backend:** Spring Boot 3.x, MongoDB Atlas, Maven
- **Frontend:** React 18, DaisyUI, Tailwind CSS
- **Authentication:** OAuth 2.0
- **API:** REST

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?logo=spring-boot&logoColor=white&style=for-the-badge) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge)

---

### Emotion-Satisfaction Analysis

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/emotion-satisfaction-analysis)

#### Description

Multi-activity comparative study validating whether emotional connection predicts satisfaction across entertainment domains (movies, social media, music). Implemented descriptive, inferential, predictive, and meta-analysis using R. My contribution: music dataset analysis with strong evidence (r=0.215, p<0.001, OR=1.731) supporting the hypothesis.

**Period:** 2026 Feb – Mar

#### Key Findings

- **Correlation Analysis:** Demonstrated significant positive correlation (r=0.215) between emotional connection and satisfaction in music domain.
- **Statistical Significance:** Strong evidence with p-value < 0.001.
- **Odds Ratio:** Users with emotional connection were 1.731 times more likely to report satisfaction.
- **Meta-Analysis:** Combined effect sizes across all entertainment domains for comprehensive validation.

#### Technologies

- **Statistical Analysis:** R for comprehensive statistical computing.
- **Data Manipulation:** Tidyverse for data wrangling and transformation.
- **Meta-Analysis:** Meta package for combining effect sizes across studies.
- **Visualization:** ggplot2 for publication-quality statistical graphics.
- **Effect Sizes:** Effectsize package for standardized effect size calculation.
- **Predictive Modeling:** Caret with Logistic Regression for classification tasks.

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white&style=for-the-badge) ![Tidyverse](https://img.shields.io/badge/Tidyverse-1A162D?logo=r&logoColor=white&style=for-the-badge) ![ggplot2](https://img.shields.io/badge/ggplot2-276DC3?logo=r&logoColor=white&style=for-the-badge)

#### Screenshots

| ![Emotion Satisfaction Analysis](projects/emotion-sat2.png) |
| :---------------------------------------------------------: |

---

### HealthyPaws

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/healthy-paws-petcare)

#### Description

Developed billing and finance module for a MERN-based veterinary system, focusing on secure and automated payment workflows. Implemented Stripe payments, invoicing, refunds, coupon system, and financial dashboards.

**Period:** 2025 Aug – Oct

#### Key Features

- **Payment Processing:** Stripe integration for secure online payments.
- **Invoicing System:** Automated invoice generation and management.
- **Refund Management:** Complete refund workflow with transaction tracking.
- **Coupon System:** Discount code management and validation.
- **Financial Dashboards:** Real-time financial analytics and reporting for finance managers.
- **Offline Payments:** Support for cash and check payment recording.

#### Technologies

- **Frontend:** React.js with TailwindCSS for responsive and modern UI.
- **Backend:** Node.js and Express.js for RESTful API development.
- **Database:** MongoDB for flexible data storage.
- **Authentication:** JWT for secure role-based access control.
- **Payments:** Stripe API for payment processing and webhooks.
- **Document Generation:** PDFKit for invoice and report PDF generation.

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=for-the-badge) ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white&style=for-the-badge) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge) ![JWT](https://img.shields.io/badge/JWT-000000?logo=json-web-tokens&logoColor=white&style=for-the-badge) ![Stripe](https://img.shields.io/badge/Stripe-008CDD?logo=stripe&logoColor=white&style=for-the-badge) ![PDFKit](https://img.shields.io/badge/PDFKit-FF6B6B?logo=pdf&logoColor=white&style=for-the-badge)

#### Screenshots

| ![Client Invoice Summary](projects/client_invoice_summary.png) | ![Client Offline Pay](projects/client_offline_pay.png) | ![Online Pay](projects/online_pay.png) |
| :------------------------------------------------------------: | :----------------------------------------------------: | :------------------------------------: |
| ![Pay Successful](projects/pay_successful.png) | ![FM Dashboard](projects/fm_dashboard.png) | |

---

### MerNote

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/MerNote/tree/feature-branch) [![Live Demo](https://img.shields.io/badge/Live%20Demo-https://mernote.sandaliranahewa.dev/-blue?style=for-the-badge&logo=vercel&logoColor=white)](https://mernote.sandaliranahewa.dev/)

#### Description

Personal notes app with full CRUD, JWT authentication, and bcrypt password hashing. Features dark/light theme toggle, note color themes, debounced search, and a token-based password reset flow via Resend email API. Rate-limited with Upstash Redis (sliding window). Containerized with Docker multi-stage build, reverse-proxied through Nginx with SSL, and self-hosted on a DigitalOcean droplet.

**Period:** 2025 Jun

#### Key Features

- **CRUD Operations:** Complete create, read, update, delete functionality for notes.
- **User Authentication:** Secure login, registration, and password reset.
- **Caching & Rate Limiting:** Redis (Upstash) for performance and sliding window rate limiting.
- **Containerization & Deployment:** Docker, Nginx, SSL, DigitalOcean.

#### Technologies

- **Frontend:** React 19, Tailwind CSS, DaisyUI
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas
- **Authentication:** JWT, bcrypt
- **Caching & Rate Limiting:** Upstash Redis
- **Email:** Resend API
- **Deployment:** Docker, Nginx, DigitalOcean

![Node.js](https://img.shields.io/badge/Node.js-339933?logo=nodedotjs&logoColor=white&style=for-the-badge) ![Express.js](https://img.shields.io/badge/Express.js-000000?logo=express&logoColor=white&style=for-the-badge) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white&style=for-the-badge) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=for-the-badge) ![TailwindCSS](https://img.shields.io/badge/TailwindCSS-06B6D4?logo=tailwind-css&logoColor=white&style=for-the-badge) ![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis&logoColor=white&style=for-the-badge) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white&style=for-the-badge) ![Nginx](https://img.shields.io/badge/Nginx-009639?logo=nginx&logoColor=white&style=for-the-badge) ![DigitalOcean](https://img.shields.io/badge/DigitalOcean-0080FF?logo=digitalocean&logoColor=white&style=for-the-badge)

#### Screenshots

| ![MerNote 1](projects/mernote-1.png) | ![MerNote 2](projects/mernote-2.png) |
| :----------------------------------: | :----------------------------------: |

---

### BusyBus

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/BusyBus-BusOperator)

#### Description

Contributed to BusOperator use case implementation of an MVC-based bus reservation system with thread-safe backend design using Singleton database architecture. Implemented full CRUD functionality with responsive frontend and database-driven booking system.

**Period:** 2025 Apr – May

#### Key Features

- **Bus Operator Dashboard:** Complete bus and schedule management interface.
- **CRUD Operations:** Create, read, update, delete for bus routes and schedules.
- **Singleton Database:** Thread-safe database connection management.
- **MVC Architecture:** Clean separation of concerns for maintainable code.
- **Responsive Design:** Mobile-friendly frontend for on-the-go management.

#### Technologies

- **Backend:** Java with MVC architecture pattern.
- **Frontend:** JSP for dynamic content rendering with HTML, CSS, JavaScript.
- **Database:** MySQL for relational data storage.
- **Design Pattern:** Singleton for database connection management.

![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white&style=for-the-badge) ![JSP](https://img.shields.io/badge/JSP-007396?logo=java&logoColor=white&style=for-the-badge) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=white&style=for-the-badge) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white&style=for-the-badge) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white&style=for-the-badge) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black&style=for-the-badge)

#### Screenshots

| ![BusyBus](projects/busybus-1.png) |
| :--------------------------------: |

---

### CookBook

[![Repository](https://img.shields.io/badge/Repository-black?logo=github&logoColor=white&style=for-the-badge)](https://github.com/sandaliz/CookBook)

#### Description

Designed a mobile application prototype for busy individuals to manage recipes, get personalized suggestions, and access AI-powered cooking assistance. Features include smart recipe discovery, personalized meal planning, step-by-step cooking instructions with timers, and real-time AI chef assistance for cooking queries. Created as an ideathon project focusing on UI/UX design and feature demonstration.

**Period:** 2025 Sep

#### Key Features

- **Smart Recipe Discovery:** Intelligent recipe recommendations based on preferences and available ingredients.
- **Personalized Meal Planning:** Custom meal plans tailored to dietary restrictions and goals.
- **Step-by-Step Cooking:** Detailed instructions with integrated timers for each step.
- **AI Chef Assistant:** Real-time AI-powered cooking assistance for queries and substitutions.
- **Recipe Management:** Save, organize, and share favorite recipes.

#### Technologies

- **Development:** Android Studio for mobile app development.
- **Language:** Kotlin for modern Android development.
- **Design:** UI/UX prototyping and design implementation.

![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?logo=android-studio&logoColor=white&style=for-the-badge) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?logo=kotlin&logoColor=white&style=for-the-badge)

#### Screenshots

| ![CookBook 1](projects/cookbook-1.png) | ![CookBook 2](projects/cookbook-2.png) | ![CookBook 3](projects/cookbook-3.png) |
| :------------------------------------: | :------------------------------------: | :------------------------------------: |
| ![CookBook 4](projects/cookbook-4.png) | ![CookBook 5](projects/cookbook-5.png) | ![CookBook 6](projects/cookbook-6.png) |
| ![CookBook 7](projects/cookbook-7.png) | ![CookBook 8](projects/cookbook-8.png) | ![CookBook 9](projects/cookbook-9.png) |
| ![CookBook 10](projects/cookbook-10.png) | ![CookBook 11](projects/cookbook-11.png) | |

---

© 2026 Sandali Ranahewa
