# Real-Time Rumor to Reality Verifier for Stock News using Blockchain Anchoring

## 📌 Overview
This project is a **Generative AI-powered** real-time news verification system designed for the stock market.  
It detects whether incoming stock-related news is **rumor** or **authentic** and stores verification results on the **blockchain** for transparency and immutability.

Built with:
- **FastAPI** for backend REST API
- **Azure OpenAI** for Generative AI-based rumor detection
- **Blockchain anchoring** (Ethereum/Testnet) for immutable proof
- **Docker** for containerized deployment

---

## 🚀 Features
- Real-time stock news ingestion
- AI-powered rumor detection using Azure OpenAI
- Blockchain anchoring to prevent tampering
- REST APIs for integration into external platforms
- Ready for deployment to Microsoft Azure

---

## 🛠️ Tech Stack
- **Backend:** Python 3.10+, FastAPI
- **Generative AI:** Azure OpenAI GPT Model
- **Blockchain:** Ethereum / Polygon Testnet (Web3.py)
- **Deployment:** Docker, Azure Container Apps
- **Data Sources:** News API / Twitter API (can be integrated)

---

## 📂 Project Structure
rumor_verifier_project/
│── app/
│ ├── main.py # FastAPI entry point
│ ├── ai_verifier.py # Azure OpenAI logic
│ ├── blockchain_anchor.py # Blockchain anchoring logic
│ ├── news_ingest.py # News ingestion logic
│── requirements.txt # Dependencies
│── Dockerfile # Docker build file
│── .env.example # Environment variables template
│── README.md # Project documentation


   
