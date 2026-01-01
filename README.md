# MSBA-Capstone-1

**Course**: Graduate Business Analytics Capstone (1.5 credits, 16 weeks)  
**Project**: [Kaggle Home Credit Default Risk Competition](https://www.kaggle.com/competitions/home-credit-default-risk)  
**Tools**: Positron IDE with Databot and Positron Assistant

---

## Overview

This capstone bridges classroom learning to real-world data analytics. You'll complete an end-to-end data science project—from problem framing through model deployment and presentation—using a 2.68 GB dataset of consumer lending data. By the end, your GitHub repository becomes a portfolio piece demonstrating your ability to deliver business value through data science.

**Details:**
- Real, messy data (10 interconnected files, missing values, class imbalance)
- Emphasis on business decisions, not just model accuracy
- Modern AI tools used the way practitioners use them in industry
- Your repository tells your story to future employers

---

## The Business Problem

Home Credit provides consumer loans to people with little or no traditional credit history—customers who are invisible to FICO scores. Your task is not simply to predict default (which is the Kaggle competition objective), but to **optimize profit given the business model of increasing access**. This reframes the problem from prediction accuracy to business decision-making under uncertainty.

---

## Core Technologies

- **Python** or **R** for data analysis and modeling.  Your choice. You should use the programming language that you are best able to read and evaluate.
- **GitHub** for version control and portfolio hosting. You will also publish your decision support app to GitHub pages.
- **Positron IDE** with **Databot** and **Positron Assistant** for AI-assisted coding and exploration.
- **Quarto** for reproducible reporting that mixes code, output, and narrative using R and Python interchangeably.

---

## Deliverables

| Deliverable | Description |
|-------------|-------------|
| Problem Statement | Formal framing of the business and technical problem |
| EDA Report | Data quality findings, key patterns, cleaning plan |
| Preprocessing Pipeline | Reproducible functions for data cleaning and feature engineering |
| Trained Model | Classification model with Kaggle submission score |
| Threshold Analysis | Business-optimized decision threshold with cost justification |
| Model Card | Documentation for responsible deployment (fairness, explainability) |
| Dashboard | Interactive decision support application deployed to Github Pages |
| Portfolio README | Professional repository showcasing your end-to-end work |
| Group Presentation | 10-minute pitch to stakeholders summarizing your approach and findings |

---

## AI in this Course

There are a lot of assignments in this course! AI will help you complete them. The course deliverables cannot be completed in this 15 week timeframe without this assistance.

## AI Philosophy

AI coding assistants are tools, not authors. You make the decisions—AI helps you execute faster.

| Your Job | AI's Job |
|----------|----------|
| Understand the business problem | Write boilerplate code quickly |
| Decide what analysis to run | Execute repetitive tasks |
| Interpret results critically | Suggest approaches you might not know |
| Catch errors and validate output | Generate first drafts for iteration |
| Own the final deliverable | Help you get unstuck |

**Don't submit AI output you don't understand.** If you can't explain why your code works, you're not ready to submit it.

---

## AI Tools

**Databot** — Your EDA partner. Purpose-built for rapid exploration. Works in a WEAR loop (Write → Execute → Analyze → Regroup), proposing next steps after each analysis. Use for Week 5 EDA. Not designed for production code.

**Positron Assistant** — Your coding partner. Writes persistent, versioned code to disk. Four modes: Ask, Edit, Agent, Plan. Use for Weeks 6+ when building reproducible pipelines.

**ChatGPT** — Your research and writing partner. You have free access through your EDU account. Use for domain research, document drafting, and brainstorming (Weeks 2, 4, 8).

---

## Core Workflow Principle

**Commit functions and scripts to GitHub—not data files or model artifacts.**

This ensures reproducibility, proper version control, and reusability across train/test splits. For example, commit the code that preprocesses raw data into features, but do not commit the processed feature files themselves. Instead, regenerate them locally as needed.

| ✓ Commit | ✗ Do NOT Commit |
|----------|-----------------|
| `src/preprocess.py` | `data/raw/*.csv` |
| `src/features.py` | `data/processed/*.parquet` |
| `src/model.py` | `models/*.pkl` |
| `positron.md` | `submissions/*.csv` |

Your modeling strategy should follow the same logic: build functions that transform data identically for training and inference, save only the code that produces outputs, and regenerate artifacts locally as needed.