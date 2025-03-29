# 🚢 Analyse des données du Titanic

Ce projet explore les données du célèbre naufrage du Titanic en utilisant **Python** et **Jupyter Notebook**. L'objectif est d'effectuer une analyse exploratoire des données (EDA) et d'entraîner un modèle de machine learning pour prédire la survie des passagers.  

---

## 📌 Contenu du projet  
📂 **notebooks/** : Contient les notebooks Jupyter avec l'analyse et le modèle  
📂 **data/** : Contient les fichiers de données (`train.csv`, `test.csv`)  
📂 **scripts/** : Scripts Python utilisés pour le prétraitement et l'entraînement du modèle  
📜 **README.md** : Explication du projet  
📜 **requirements.txt** : Liste des dépendances  

---

## 🔧 Installation et Exécution  

### 1️⃣ Cloner le projet  
```sh
git clone https://github.com/utilisateur/titanic-analysis.git
cd titanic-analysis

# Créer un environnement virtuel
python -m venv venv
source venv/bin/activate  # macOS/Linux
venv\Scripts\activate     # Windows

#Lancer Jupyter notebook

#L'analyse des données

L'analyse des données comprend:
Le nettoyage et prétraitement des données
Visualisation des données
Création de nouvelles variables (featuring engineering)
Entraînement d'un modèle de classification (LogisticRegression,RandomForestClassifier,KNeighborClassifier)
