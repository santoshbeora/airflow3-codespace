 Apache Airflow 3 – Cloud Practice Lab (GitHub Codespaces)

🚀 Learn, build, and practice Apache Airflow 3 directly in your browser!  
This repo provides a ready-to-run Docker Compose setup for the latest version of Apache Airflow (v3.x) — hosted fully in GitHub Codespaces, so you can:
- 🧠 Learn and experiment with Airflow 3 DAGs
- 🌍 Access your environment from any device
- 💾 Persist all your DAGs and configuration safely inside this repo



 🧰 Features
- Latest Apache Airflow 3 (auto-updates to the newest stable version)
- Browser-based Airflow UI (Port 8080)
- Persistent `dags/`, `logs/`, and `plugins/` folders
- Free GitHub Codespaces environment — no local install



 ⚙️ Getting Started

 1️⃣ Open in GitHub Codespaces
1. Click the green “Code” button above → select “Codespaces” tab.  
2. Choose “Create codespace on main.”  
   (GitHub will launch a full Linux VM in your browser.)



 2️⃣ Start Airflow

Once the Codespace starts, open the terminal and run:

```bash
docker compose up airflow-init
docker compose up
