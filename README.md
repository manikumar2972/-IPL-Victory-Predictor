# 🏏 IPL Win Predictor

This project predicts the probability of a team winning an IPL match using machine learning. It processes historical match and ball-by-ball data from the IPL to train a predictive model. The project includes a **Jupyter Notebook** for data analysis & model building and a **Streamlit app** for real-time predictions.

---

## 📂 Project Structure
```
IPL-Win-Predictor/
│
├── IPL Predictor.ipynb   # Jupyter Notebook with data processing & model training
├── app.py                # Streamlit web app for predictions
├── pipe.pkl              # Saved ML pipeline/model
├── requirements.txt      # Python dependencies
├── matches.csv           # Match-level IPL data
├── deliveries.csv        # Ball-by-ball IPL data
└── README.md             # Project documentation
```

---

## 📊 Dataset
- **matches.csv** – Match-level details such as date, venue, teams, toss, and winner.
- **deliveries.csv** – Ball-by-ball details including runs, wickets, overs, and batsmen.  

---

## 🚀 Running the Project

### Run Jupyter Notebook:
```bash
jupyter notebook
```
Open `IPL Predictor.ipynb` and run all cells.

### Run Streamlit App (Local):
```bash
streamlit run app.py
```
Open in browser: `http://localhost:8501`

---

## 📦 Requirements
```
streamlit
pandas
numpy
scikit-learn
```

---

## 🤝 Contributing
Pull requests are welcome. For major changes, open an issue.

---

