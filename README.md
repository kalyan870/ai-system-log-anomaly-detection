# ai-system-log-anomaly-detection
AI System Log Anomaly Detection Dashboard
# AI System Log Anomaly Detection Dashboard

An AI-driven monitoring dashboard that analyzes application and server logs to detect abnormal patterns, classify severity levels, and support proactive system monitoring.

This project focuses on practical log analysis used in real-world DevOps and production environments, rather than synthetic or toy examples.

---

## 🚀 Features

- Detects anomalies from raw system and application logs  
- Severity-based classification:
  - Low (Warnings)
  - Medium (Timeouts / Access issues)
  - High (Errors / Failures)
  - Critical (System-level failures)
- Ignores normal informational logs
- Interactive web interface
- Live deployed demo

---

## 🧠 How It Works

1. User pastes system or application logs
2. The system scans each log line for risk-related patterns
3. Anomalies are identified based on keyword presence
4. Each anomaly is assigned a severity level
5. Results are displayed in a structured dashboard with summary metrics

This approach mirrors real-world log monitoring tools used for early failure detection.

---

## 🛠️ Tech Stack

- Python
- Gradio
- Rule-based anomaly detection
- Hugging Face Spaces (deployment)

---

## 📊 Sample Log Analysis

Example input:
