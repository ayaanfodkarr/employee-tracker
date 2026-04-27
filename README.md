# 👥 Employee Attendance & Productivity Tracker

An automated pipeline that analyzes employee attendance and productivity data, detects patterns, flags at-risk employees, and sends a detailed weekly report to the manager automatically.

## 🔍 What it does
- Analyzes employee attendance and productivity data
- Detects patterns — frequent absences, late arrivals, low productivity
- Calculates risk levels — High, Medium, Low for every employee
- Predicts at-risk employees using a Random Forest ML model (83% accuracy)
- Visualizes attendance and productivity trends with charts
- Automatically emails a detailed weekly report to the manager

## 🛠️ Tech Stack
- Python
- Jupyter Notebook
- Pandas — data processing
- Matplotlib & Seaborn — visualizations
- Scikit-learn (Random Forest) — ML predictions
- SMTP — automated email reports
- python-dotenv — secure credentials

## 💡 Real World Use Case
Instead of manually reviewing attendance spreadsheets, this pipeline automatically identifies which employees need attention and emails a full report to the manager every week — saving hours of manual work.

## 🚀 How to Run
1. Clone the repo
2. Install dependencies: `pip install pandas numpy matplotlib seaborn scikit-learn python-dotenv`
3. Create a `.env` file with your credentials
4. Open `employeeTracker.ipynb` in Jupyter Notebook
5. Run all cells: `Kernel → Restart & Run All`
