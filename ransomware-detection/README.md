# AI-Driven Ransomware Detection and SOAR Simulation

**Status:** Completed University Project

### Objective
This project combines cybersecurity and machine learning to design a system for the early detection of ransomware attacks. The system uses an unsupervised anomaly detection model to identify malicious patterns in system logs and then simulates an automated incident response workflow based on SOAR (Security Orchestration, Automation, and Response) principles.

### Key Features & Methodology
* **Synthetic Data Generation:** Generated a custom dataset of over 4,800 log entries that mimics realistic ransomware Tactics, Techniques, and Procedures (TTPs) alongside normal user activity.
* **Feature Engineering:** Engineered time-based and frequency-based features (e.g., rolling event counts per minute) from raw log data to create meaningful signals for the model.
* **Unsupervised Learning:** Implemented the **Isolation Forest** algorithm to detect anomalies without relying on pre-labeled attack signatures, allowing it to potentially find novel threats.
* **Automated Response Simulation:** Designed a workflow that, upon detecting a critical anomaly, generates an alarm and a list of recommended incident response actions (e.g., host isolation, account block).

### Key Result
The model proved highly effective at identifying threats, **achieving 99% recall** for the anomaly class. This demonstrates its ability to reliably catch potential attacks while maintaining high overall accuracy, minimizing the risk of a breach going unnoticed.

### Tech Stack
* **Languages & Libraries:** Python, Pandas, Scikit-learn (Isolation Forest)
* **Environment:** Google Colab

### View the Project
The complete code, analysis, and visualizations are available in the Google Colab notebook.

➡️ **[View the full analysis in Google Colab](https://colab.research.google.com/drive/13R-8rvvD7GZlTEkKDiPYPN0o-3mmsrHg?usp=sharing)**
