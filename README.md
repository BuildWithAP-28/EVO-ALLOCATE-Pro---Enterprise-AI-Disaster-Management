# EVO-ALLOCATE-Pro---Enterprise-AI-Disaster-Management
EVO-ALLOCATE—an enterprise-grade AI command center for disaster management. Right now, I've deployed a robust MVP that integrates Deep Learning OCR with a geospatial matching pipeline. It’s built to turn ground-level chaos into coordinated, life-saving action."

# 🧠 EVO-ALLOCATE
> **"In a crisis, time is the enemy and chaos is the obstacle. EVO-ALLOCATE engineers the clarity that defeats both—because every second saved is a life saved."**

EVO-ALLOCATE is an Enterprise-Grade, AI-Powered Resource Allocation Command Center. It is designed to revolutionize disaster management by bridging the gap between unstructured field intelligence and highly optimized digital logistics.

## 🚀 The Problem it Solves
During large-scale crises, NGOs and rescue teams face a massive data bottleneck. Analog field reports cause delays, and dispatchers often lack the spatial awareness to match the *right volunteer* with the *exact skills* to the *closest crisis zone*. 

## 💡 How it Works (The 3-Tier Architecture)
1. **The Vision Engine (EasyOCR):** Extracts string literals from uploaded images of handwritten/typed field surveys in milliseconds.
2. **The NLP Pipeline:** Normalizes text and maps critical entity vectors (e.g., "Medical", "Rescue") using advanced semantic dictionaries, calculating a dynamic **Urgency Score (0-100)**.
3. **The Smart Match Engine:** Uses **TF-IDF Vectorization** (for skill-matching) and the **Haversine Formula** (for geospatial proximity) to autonomously pair skilled personnel with urgent tasks.

## 🔥 Key Features
* **Live Geo-Radar:** Interactive telemetry tracking of active crisis zones.
* **Automated Data Seeding:** Instantly synthesizes 150+ realistic enterprise data points for demonstration.
* **Immutable Audit Trail:** Secure, append-only logging of every operational action.
* **Premium Enterprise UI:** Custom CSS-animated Light Theme built for mission-critical clarity.

## 🛠️ Tech Stack
* **Frontend:** Streamlit, Custom CSS
* **Data Visualization:** Plotly Express, Folium (Interactive Mapping)
* **Computer Vision:** EasyOCR (PyTorch)
* **Machine Learning & Math:** Scikit-learn (TF-IDF), NumPy, Pandas, Haversine Geospatial Logic

## 💻 How to Run Locally
1. Clone the repository:
   ```bash
   git clone [https://github.com/yourusername/evo-allocate.git](https://github.com/yourusername/evo-allocate.git)

apne folder me ek "data" naam ka folder banana mat bhulna
   Create and activate a virtual environment.

Install dependencies:

Bash

pip install -r requirements.txt

Run the Enterprise Command Center:

Bash

python -m streamlit run app.py


Developed by Ayush Pandey | Built for Hack To Skill Hackathon 2026
