# 🚀 PYQ Pattern Analyzer

> **AI-Powered Exam Intelligence & Revision Prioritization for Engineering Students**

[![Live Demo](https://img.shields.io/badge/Demo-Live%20App-brightgreen.svg)](https://heavenly-exam-intel-path.base44.app)
[![Platform: Base44](https://img.shields.io/badge/Platform-Base44%20Fullstack-blue.svg)](https://base44.com)
[![Target: MAKAUT / Indian Universities](https://img.shields.io/badge/Domain-Engineering%20Exams-orange.svg)]()
[![Multilingual](https://img.shields.io/badge/Languages-English%20%7C%20Hindi%20%7C%20Bengali-purple.svg)]()

---

## 📌 The Problem
Engineering students preparing for university semester exams (specifically across tier-2 and tier-3 colleges) often struggle with syllabus overload. Previous Year Questions (PYQs) hold the recurring patterns, but manually cross-referencing 5+ years of papers across 6–8 subjects is time-consuming and prone to misjudgment. 

Furthermore, existing study resources are overwhelmingly English-only, creating an additional comprehension barrier for students who grasp technical concepts better in regional languages.

---

## 💡 The Solution
**PYQ Pattern Analyzer** automates question paper analysis by ingesting raw PYQ papers, isolating underlying syllabus topics, evaluating frequency weightage, and generating an actionable revision roadmap:
* **Weighted Topic Priority:** Categorizes recurring topics into **High, Medium, and Low** priority tiers based on question repetition.
* **Multilingual Concept Assistant:** Answers doubts and clarifies tricky exam topics in **English, Hindi, and Bengali**.
* **Subject Workspace:** Allows students to save, organize, and track their question analysis across semesters.
* **Isolated User State:** Secure per-user accounts ensuring individual study plans remain private.

---

## 🛠️ System Architecture

```mermaid
flowchart TD
    A[Student Ingestion: PDF / Paste Text] --> B[Text Preprocessing & Normalization]
    B --> C[Base44 LLM Extraction Engine]
    C --> D[Topic Cluster & Frequency Ranker]
    D --> E[Priority Tiers: High / Medium / Low]
    E --> F[Interactive Study Dashboard]
    F --> G[Multilingual Query Assistant: EN / HI / BN]
