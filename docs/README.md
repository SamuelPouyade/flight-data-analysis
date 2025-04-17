# ✈️ Flight Data Analysis Project

Analyse complète de données de vols combinées à des données météorologiques, pour explorer les causes des retards, identifier des tendances, et proposer des visualisations pertinentes.

---

## 🎯 Objectifs

- Croiser plusieurs datasets (vols, météo, aéroports)
- Explorer les retards et annulations selon différents facteurs (compagnies, météo, périodes)
- Visualiser les résultats sous forme de graphiques et cartes interactives
- Bonus : prédire le risque de retard avec du machine learning

---

## 📁 Structure du projet

📂 `flight-data-analysis/`  
├── 📁 `data/` → Données brutes (vols, météo, etc.)  
├── 📁 `notebooks/` → Notebooks Jupyter (exploration, nettoyage, analyse)  
├── 📁 `output/` → Résultats exportés (graphiques, CSV)  
│   └── 📁 `plots/` → Graphiques générés  
├── 📁 `utils/` → Fonctions Python réutilisables  
├── 📁 `docs/` → Présentation du projet (README, images, schémas)  
├── 📄 `requirements.txt` → Librairies nécessaires  
└── 📄 `.gitignore` → Fichiers à ignorer par Git

---

## 🧠 Stack technique

- Python 3
- Pandas / NumPy
- Matplotlib / Seaborn / Plotly
- Scikit-learn (optionnel pour prédiction)
- Jupyter Notebook

---

## 📦 Données utilisées

- [Flight Delay Dataset – US DOT / Kaggle](https://www.kaggle.com/datasets/usdot/flight-delays)
- [OurAirports – données aéroports](https://ourairports.com/data/)
- [Open-Meteo / NOAA – données météo](https://open-meteo.com/)

---

## 🚀 Démarrage du projet

1. Cloner le repo  
2. Créer et activer un environnement virtuel :
   ```bash
   python3 -m venv .venv
   source .venv/bin/activate
   pip install -r requirements.txt
   jupyter notebook
   ```
   