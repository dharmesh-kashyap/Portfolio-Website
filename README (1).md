# Personal Portfolio | Data Engineering & Analytics

This repository contains the source code and design breakdown of my personal portfolio website. The site is built as one continuous data pipeline: raw inputs on the left, decision-ready assets on the right, and the visitor walks it by scrolling.

## 🚀 Professional Profile
**Data Engineer, Mumbai** with 2+ years of production experience delivering pipelines for NABARD and ICICI Prudential. I turn messy, multi-source data (government surveys, scheme PDFs, boundary files, Excel uploads) into structured, trustworthy assets that BI tools can consume directly.

## 🛠 Technical Stack
* **Languages:** Python, SQL
* **Big Data & Processing:** PySpark, Hadoop, Polars, DuckDB, Parquet, ETL Pipelines, Data Validation
* **Databases & Modeling:** PostgreSQL, MySQL, Dimensional Modeling (staging, dimension, fact), SQL Query Optimization
* **Backend & Cloud:** Flask, AWS
* **Analytics & BI:** Tableau, AIV Hub, KPI Reporting, Dashboard Development
* **Frontend (this site):** HTML5, CSS3 (Custom Properties), Vanilla JavaScript

## 📊 Key Impact Metrics
* **670K+** Village boundary records delivered as GeoJSON (NABARD)
* **5.2M+** Records in a staging-to-dimension/fact PostgreSQL warehouse (ICICI Prudential)
* **2,500+** Government scheme PDFs extracted with validation checks
* **60+** Mutual fund instruments consolidated by one automated recurring pipeline
* **298** Harmonized survey variables kept consistent across 3 HCES rounds

## 📂 Featured Projects
### 1. Survey ETL for NABARD
Distributed processing of raw NSO/MoSPI microdata.
* **Function:** Standardizes 5 All-India surveys (HCES, ASUSE, AIDIS, SAS, Agriculture Census) across 3 rounds into one long-format schema that BI tools consume directly. The HCES pipeline ships as a modular Python ETL package with a full test suite.
* **Tech:** PySpark, Hadoop, Polars, DuckDB, Parquet.

### 2. Data Processor: Automated File-to-Database Platform
A Flask and PostgreSQL app for finance data upload automation (ICICI Prudential).
* **Function:** Ingests Admin Dump and Location Vacation Excel files into staging tables, validates them, and promotes them into a dimension/fact warehouse. Includes scheduler visibility, refresh progress, conflict reporting, and a notification tray.
* **Tech:** Python, Flask, PostgreSQL, SQL.

### 3. AI-Powered News Intelligence Platform
News scraping, AI enrichment, and chat platform built for NABARD.
* **Function:** A multi-source scraper extracts, cleans, and structures articles into a database feeding a live dashboard, with AI enrichment for classification, summarization, and search plus an interactive commodities ticker.

## 🎬 The Site Experience
* **Hero:** the name resolves from noise on load, and the boundary map behind it reacts to the cursor.
* **Pixel walker:** a 16×16 sprite built from plain divs walks the hairline in steps, and later tracks scroll progress through the pipeline.
* **The pipeline:** a pinned scroll sequence (Extract, Transform, Load, Serve) that adapts to every screen shape and falls back to a stacked layout with scroll-reveal on very short screens.
* **Wide in. Long out. / The stack in context. / Built on solid ground.:** scroll-driven sections for the reshape story, the capability map, and education.
* **Accessibility & performance:** semantic markup, keyboard focus states, `prefers-reduced-motion` support, no external libraries.

## ⚙️ Core Philosophy: "Automation-First"
> "If a workflow can be automated, it will be. That's not a preference. It's a standard."

The site uses the **Intersection Observer API** for performance-efficient reveals and custom JavaScript for the scramble, the counters, and the scroll-linked pipeline, ensuring a premium experience without library bloat.

---
© 2026 Dharmesh Kashyap

---

Thank you
