🏥 Prédiction de l'état de santé des patients (malade ou sain)
📖 Présentation du Projet
Ce projet a pour objectif de prédire si un patient est malade ou sain à partir de données médicales. Il repose sur l’analyse de données tabulaires et d’images médicales, et vise à aider les professionnels de santé à détecter rapidement des pathologies grâce à des modèles d’intelligence artificielle.

Le projet est structuré en plusieurs étapes :

📊 Exploration et Prétraitement des Données

🏗 Analyse des Biais et Visualisation

🤖 Entraînement et Évaluation du Modèle

🎯 Prédiction sur de Nouveaux Patients

🛠️ Installation et Pré-requis
🔹 1. Cloner le repository
bash
Copier
Modifier
git clone https://github.com/ton-utilisateur/prediction-sante.git  
cd prediction-sante  
🔹 2. Installer les dépendances
Crée un environnement virtuel (optionnel) et installe les packages nécessaires :

bash
Copier
Modifier
python -m venv venv  
source venv/bin/activate  # Sur Linux/Mac  
venv\Scripts\activate     # Sur Windows  
pip install -r requirements.txt  
🔹 3. Lancer Jupyter Notebook
bash
Copier
Modifier
jupyter notebook  
Puis ouvre le fichier notebooks/Prédiction_patient_malade_ou_sain.ipynb.

📊 Jeu de Données
Le dataset utilisé contient 15 000 patients et 12 colonnes, comprenant :

Image Index : Nom du fichier image associé au patient

Finding Labels : Diagnostic médical (ex. : « No Finding », « Cardiomegaly »…)

Patient Age : Âge du patient

Patient Gender : Sexe du patient

View Position : Position de la prise de vue (ex. : "PA", "AP")

🚀 Méthodologie
1️⃣ Chargement et nettoyage des données

Suppression des colonnes inutiles

Gestion des valeurs manquantes

Normalisation des noms de colonnes

2️⃣ Exploration des biais et visualisation

Analyse de la répartition des maladies

Étude de la corrélation entre variables

Visualisation des images médicales

3️⃣ Modélisation et Prédiction

Entraînement d’un modèle de classification

Validation et évaluation des performances

Test sur de nouveaux patients

🏆 Résultats attendus
✅ Amélioration de la détection des maladies
✅ Meilleure compréhension des données médicales
✅ Outil d’aide à la décision pour les médecins
