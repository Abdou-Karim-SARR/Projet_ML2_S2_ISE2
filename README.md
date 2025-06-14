


## Description du Projet

FraudGuard est un système intelligent conçu pour détecter les fraudes dans les transactions en ligne. Développé pour **Vesta Corporation**, ce projet combine des techniques avancées de *machine learning* et d’analyse comportementale pour identifier les opérations suspectes avec une grande précision.

##  Technologies Utilisées

- **Langage** : Python 3
- **Machine Learning** : LightGBM, Scikit-learn
- **Backend** : Flask
- **Frontend** : HTML5, CSS3, Chart.js
- **Traitement des données** : Pandas, NumPy
- **Visualisation** : Matplotlib, Seaborn

##  Structure des Fichiers

```
fraud-detection/
├── app.py                  # Application Flask principale
├── predict.py              # Module de prédiction
├── requirements.txt        # Dépendances Python
├── static/
│   ├── css/                # Feuilles de style CSS
│   └── images/             # Images et logos
├── templates/              # Fichiers HTML
│   ├── base.html
│   ├── index.html
│   ├── predict.html
│   ├── dashboard.html
│   └── stats.html
├── data/
│   ├── processed/          # Données nettoyées
│   └── models/             # Modèles entraînés
└── notebooks/              # Notebooks d’analyse exploratoire
```

##  Installation et Exécution

### 1. Cloner le dépôt

```bash
git clone [lien-du-depot]
cd fraud-detection
```

### 2. Créer un environnement virtuel

```bash
python -m venv env
env\Scripts\activate  # Sous Windows
source env/bin/activate  # Sous Linux/macOS
```

### 3. Installer les dépendances

```bash
pip install -r requirements.txt
```

### 4. Lancer l’application

```bash
python app.py
```

### 5. Accéder à l’interface

[http://localhost:8000](http://localhost:8000)

## Fonctionnalités

###  Prédiction en temps réel

- Upload de fichiers CSV
- Affichage instantané des risques de fraude

###  Tableau de bord interactif

- Statistiques globales
- Histogrammes et scores
- Nombre de fraudes détectées

### Analyse avancée

- Exploration des données transactionnelles
- Visualisation des tendances de fraude

## Modèle de Machine Learning

- **Modèle utilisé** : LightGBM
- **AUC** : 0.92 sur les données de test
- **Traitement** : gestion des valeurs manquantes
- **Feature Engineering** : enrichissement des variables
- **Validation** : découpage temporel réaliste

## Équipe

- Bocar Mamoudou DIACK  
- Fallou NGOM  
- Mamadou Lamine NDAO  
- Abdou Karim SARR  

>  Supervisé par : Madame Mously DIAW

##  Ressources

- [Donnees sur Kaggle](https://www.kaggle.com/c/ieee-fraud-detection)
- [Documentation LightGBM](https://lightgbm.readthedocs.io/)
- Article : *"How AI is Transforming Fraud Detection in Financial Services"*

-  [lien de l'application](https://projet-ml2-s2-ise2.onrender.com)
