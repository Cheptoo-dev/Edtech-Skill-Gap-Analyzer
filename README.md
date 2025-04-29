# Edtech-Skill-Gap-Analyzer
AI-powered tool that helps users discover the skills they need to reach their dream careers — and find resources to bridge the gap.

## 🚀 Demo
[Live Demo Coming Soon]

## 📌 Features
- Input your current skills and career goals
- Get a list of missing skills and relevant learning resources
- Real-time analysis using semantic embeddings
- Clean UI built with React/Dash
- FastAPI backend + PostgreSQL database

## 🛠️ Tech Stack

| Layer        | Tools Used                           |
|--------------|---------------------------------------|
| Backend      | Python, FastAPI, PostgreSQL, SQLAlchemy |
| AI/ML        | Sentence Transformers, Scikit-learn    |
| Frontend     | React.js (with TypeScript) or Dash     |
| Deployment   | Docker, Render, Vercel                 |

## 📚 How It Works
1. User selects or inputs their existing skills
2. Chooses a career goal (e.g., "Data Scientist")
3. The app:
   - Embeds both sets of skills
   - Computes similarity
   - Identifies gaps
   - Recommends relevant resources

## 🧪 Local Setup

```bash
# Backend
cd backend
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn main:app --reload

# Frontend
cd frontend
npm install
npm run dev
