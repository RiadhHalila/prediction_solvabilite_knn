
# 🔍 Prédiction de la Solvabilité des Clients avec KNN

Ce projet est un mini-projet de data science utilisant l'algorithme K-Nearest Neighbors (KNN) pour prédire la **solvabilité des clients** à partir de données financières fictives.

## 📁 Structure du projet

- `notebook.ipynb` : Notebook principal contenant l'ensemble du code, des analyses, visualisations et résultats.
- `data/` : Dossier pouvant contenir un futur jeu de données réel ou exporté.
- `figures/` : Graphiques générés dans le notebook, utiles pour le rapport ou une présentation.
- `README.md` : Description du projet.

## ⚙️ Outils utilisés

- Python 3.x
- Bibliothèques : `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## 🧠 Objectif

Prédire si un client est **solvable** ou **non solvable** en utilisant :
- Son âge
- Son revenu annuel
- Le montant de crédit demandé
- Son ratio dette/revenu

## 📊 Visualisations

Plusieurs visualisations sont intégrées dans le notebook :
- Distribution des variables
- Matrice de corrélation
- Visualisation des performances du modèle (matrice de confusion)

## 🚀 Comment exécuter le projet

1. Cloner ce dépôt GitHub
2. Installer les dépendances avec pip :
   ```bash
   pip install -r requirements.txt
   ```
3. Lancer le notebook avec Jupyter Lab ou Jupyter Notebook :
   ```bash
   jupyter lab
   ```

## ✅ Résultats

Le modèle KNN est évalué à l’aide de métriques standards telles que la précision, le rappel et le F1-score.

## 💡 Pistes d’amélioration

- Tester d'autres modèles (SVM, RandomForest, XGBoost)
- Hyperparamétrage du nombre de voisins `k`
- Validation croisée
- Utilisation de données réelles anonymisées

## 🧑‍💻 Auteur

Projet réalisé par Riadh HALILA

---
© 2025 – Projet pédagogique à but démonstratif.
