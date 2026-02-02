# 🛡️ ToxiGuard: Toxic Comment Detection

Welcome to my Toxic Speech Detection repository! This project implements a production-ready NLP pipeline designed to detect harmful content in real-time. It uses a fine-tuned Transformer model wrapped in a modern API infrastructure for scalable deployment.

---

## 📌 Project Highlights

✅ **Multi-Label Classification (DistilBERT)** A fine-tuned DistilBERT transformer model capable of detecting 6 specific types of toxicity (Toxic, Severe Toxic, Obscene, Threat, Insult, Identity Hate) simultaneously.

✅ **Class Imbalance Handling** Implemented custom `BCEWithLogitsLoss` with calculated position weights (up to 5.0x scaling) to ensure the model correctly identifies rare classes like "Threats" without bias.

✅ **Production-Ready API (FastAPI)** The model is served via a high-performance FastAPI backend, allowing for real-time inference requests with sub-50ms latency.

✅ **Containerized Deployment (Docker)** Fully Dockerized environment ensuring the application runs consistently across different machines and cloud platforms without dependency issues.

---

## 🔧 Tech Stack

- Python 3.9+
- PyTorch / Hugging Face Transformers
- FastAPI / Uvicorn
- Docker
- Pandas / NumPy
- Scikit-learn

---
