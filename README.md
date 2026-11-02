<img width="100%" alt="HACKHAZARDS '26 Banner" src="https://github.com/user-attachments/assets/c698b2cd-da84-4cb0-9276-125c6a7244aa" />

# 🚀 PYQ Pattern Analyzer
> **Smart Study Planner & Revision Intelligence for Engineering Students**

[![Live App](https://img.shields.io/badge/🚀%20Launch-Live%20App-brightgreen?style=for-the-badge)](https://heavenly-exam-intel-path.base44.app)
[![Built with Base44](https://img.shields.io/badge/Platform-Base44-blue?style=for-the-badge)](https://base44.com)
[![Hackathon](https://img.shields.io/badge/HACKHAZARDS-'26-orange?style=for-the-badge)]()
[![Languages](https://img.shields.io/badge/Languages-English%20%7C%20Hindi%20%7C%20Bengali-purple?style=for-the-badge)]()

---

## 🌐 Quick Access
👉 **Direct App Link:** [https://heavenly-exam-intel-path.base44.app](https://heavenly-exam-intel-path.base44.app)  
*(No local setup required. Open the link, create an account, and start analyzing your previous year questions immediately.)*

---

## 📌 Problem & Domain
**Theme:** Learning & Knowledge Systems  

Indian engineering students preparing for semester exams frequently spend time studying low-weightage topics while missing high-frequency ones. Analyzing 5+ years of previous year question papers (PYQs) manually across multiple subjects is tedious and error-prone. 

This challenge is magnified for students in tier-2 and tier-3 colleges who are more comfortable grasping difficult technical concepts in regional languages.

---

## 🎯 Objective & Value Provided
* **Target Users:** Undergraduate engineering students preparing for university semester exams.
* **Core Pain Point:** Not knowing which topics repeat consistently across exam cycles.
* **The Solution:** Students upload PDFs or paste question text; the platform clusters recurring topics and stratifies them into **High, Medium, and Low** priority tiers. Students can also clarify conceptual doubts directly in **Hindi or Bengali**.

---

## ✨ Key Features
- 📄 **Flexible Input:** Upload question paper PDFs or paste raw text.
- 📊 **Smart Priority Ranking:** Automatically scores and classifies recurring topics (High, Medium, Low) based on frequency.
- 🗣️ **Multilingual AI Assistant:** Clarify doubts and study concepts in **English, Hindi, or Bengali**.
- 📁 **Subject Workspaces:** Save and revisit past question analyses organized by semester and subject.
- 🔒 **Per-User Authentication:** Secure individual student accounts to keep study workspaces private.
- ⭐ **Feedback Loop:** Built-in rating mechanism for continuous user experience improvements.

---

## 🧠 System Architecture

```mermaid
flowchart TD
    A[Student Ingestion: PDF / Paste Text] --> B[Text Preprocessing & Normalization]
    B --> C[Base44 LLM Extraction Engine]
    C --> D[Topic Cluster & Frequency Ranker]
    D --> E[Priority Tiers: High / Medium / Low]
    E --> F[Interactive Study Dashboard]
    F --> G[Multilingual Query Assistant: EN / HI / BN]
