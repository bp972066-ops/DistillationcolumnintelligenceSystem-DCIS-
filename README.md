# DistillationcolumnintelligenceSystem-DCIS-
# 🧪 Distillation Column Intelligence System (DCIS) v2.0

## Advanced Fault Diagnosis & Corrective Action Engine

### Enhanced with LangGraph Processing & Gemini AI

--- 

## 💡 Overview

The Distillation Column Intelligence System (DCIS) is an advanced Python-based application designed to assist process engineers and operators in diagnosing operational faults in industrial distillation columns. It combines rule-based expert knowledge with cutting-edge AI (Google Gemini) to provide comprehensive, actionable insights, significantly improving troubleshooting efficiency and preventing costly downtime.

---

## ✨ Features

*   **Rule-Based Expert System:** Diagnoses common column faults (Flooding, Weeping, Foaming, Entrainment, Fouling, Reboiler Issues, Pressure Control) based on hydraulic and operational parameters.
*   **AI-Enhanced Commentary (Gemini Integration):** Provides concise, expert AI commentary for each detected fault, highlighting the most likely root causes and prioritizing immediate corrective actions.
*   **LangGraph Workflow Orchestration:** Utilizes LangGraph to build a robust and modular workflow for sequential diagnosis, from initial data input and rule-based analysis to AI enrichment and final report generation.
*   **Interactive Input Modes:** Supports manual data entry, quick input with default values, and a full auto-demo scenario for ease of use.
*   **Detailed Diagnostic Reports:** Generates comprehensive reports including operating conditions, matched symptoms, likely root causes, immediate corrective actions, and long-term preventive measures.
*   **Cross-Platform Compatibility:** Designed for both local terminal execution (with rich ANSI coloring) and Google Colab environments.

---

## ⚙️ How It Works

1.  **Data Input:** Users provide current column operating conditions (e.g., feed rate, temperatures, pressures, delta-P across trays) and observed symptoms.
2.  **Rule-Based Analysis:** The system applies a set of predefined heuristic rules and domain expertise to identify potential fault conditions and assign a score and confidence level to each.
3.  **AI Enhancement (Optional):** If enabled, the Gemini AI model analyzes the raw conditions and rule-based findings to generate an expert narrative for each identified fault, focusing on the most critical aspects.
4.  **Report Generation:** A detailed diagnostic report is compiled, presenting the diagnosed problems, their severity, confidence scores, matched symptoms, root causes, and recommended actions. The AI commentary is integrated where available.
5.  **Output & Storage:** The report is displayed to the user and can optionally be saved as a JSON file for record-keeping and further analysis.

---

## 🛠️ Monitored Faults

DCIS is equipped to detect and provide guidance on the following critical distillation column issues:

*   **Flooding:** Excessive liquid holdup due to high vapor velocity.
*   **Weeping:** Liquid leaking through trays due to insufficient vapor velocity.
*   **Foaming:** Stable foam formation disrupting vapor-liquid contact.
*   **Entrainment:** Liquid droplets carried with vapor, reducing separation efficiency.
*   **Fouling:** Gradual buildup of deposits restricting flow and reducing performance.
*   **Reboiler Issues:** Malfunctions in the reboiler affecting vapor generation.
*   **Pressure Control:** Deviations in column pressure impacting separation.
