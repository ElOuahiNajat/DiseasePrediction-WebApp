#  Disease Prediction WebApp

Une application web intelligente de prédiction de maladies à partir des symptômes de l'utilisateur, intégrant un **assistant conversationnel IA** et un modèle de **machine learning** pour fournir des recommandations médicales personnalisées.

---

##  Problématique

Dans de nombreux cas, les individus ressentent des symptômes mais n'ont pas un accès immédiat à un médecin ou des connaissances suffisantes pour interpréter correctement ces signes. Cette absence de guidance initiale peut retarder le diagnostic, aggraver l'état de santé et provoquer de l'anxiété.

---

##  Objectifs

- Fournir un **outil d’auto-évaluation** de la santé à partir des symptômes.
- Prédire les maladies les plus probables via un **modèle d’intelligence artificielle**.
- Offrir un **assistant IA conversationnel** pour aider et informer l’utilisateur.
- Proposer des **recommandations personnalisées** : précautions, médicaments, régimes, etc.
- Sensibiliser à la **prévention** et encourager une **prise en charge rapide**.

---

##  Fonctionnalités principales

-  **Saisie interactive des symptômes**
-  **Prédiction intelligente de la maladie probable**
-  **Assistant IA conversationnel** guidant l’utilisateur
-  **Conseils médicaux personnalisés** :
  - Précautions à prendre
  - Médicaments possibles
  - Régime alimentaire adapté
  - Activités physiques recommandées
- 📊 **Utilisation de jeux de données médicaux fiables**
- 🌐 **Interface web simple et accessible**

---

##  À propos de l'assistant IA

L’application intègre un **assistant conversationnel IA** capable de :

- Guider l’utilisateur dans la saisie des symptômes.
- Répondre à des questions médicales de base.
- Fournir des explications sur les maladies et les traitements.
- Améliorer l’expérience utilisateur grâce à une interface interactive et humaine.

---

## 🛠️ Technologies utilisées

| Technologie | Description |
|-------------|-------------|
| Python / Flask | Backend de l'application |
| HTML / CSS / JS | Frontend web |
| Scikit-learn | Prédiction des maladies (SVM) |
| Pandas / NumPy | Manipulation des données |
| Chatbot IA (NLU simple) | Interaction utilisateur |
| CSV Datasets | Symptômes, maladies, médicaments, etc. |

---

## 📁 Structure du projet

DiseasePrediction-WebApp/
│
├── app.py # Application Flask principale

├── chatbot_server.py # Chatbot IA

├── model_predictor.py # Prédiction de maladies

├── mdel_SVM.py # Entraînement du modèle SVM

├── static/ # Fichiers CSS et JS

├── templates/ # Pages HTML

├── data/ # Fichiers CSV : symptômes, médicaments, etc.

└── .env # Variables d'environnement

---
##  Demo 
https://youtu.be/YVXTZ06m1Zw

##  Installation locale

1. **Cloner le dépôt GitHub** :
```bash
git clone https://github.com/ElOuahiNajat/DiseasePrediction-WebApp.git
cd DiseasePrediction-WebApp

2. **Créer un environnement virtuel (optionnel) ** :
python -m venv env
source env/bin/activate  # (Linux/macOS)
env\Scripts\activate     # (Windows)

3. **Lancer le serveur Flask** :
python app.py

4.**Accéder à l'application** :
Ouvre ton navigateur à l'adresse : http://127.0.0.1:5000

Données utilisées
Les prédictions sont basées sur un ensemble de données médicales fiables contenues dans des fichiers CSV :

Symptom-severity.csv

description.csv

precautions_df.csv

medications.csv

diets.csv

workout_df.csv

Remarques
⚠️ Ce projet est conçu à des fins éducatives et informatives. Il ne remplace en aucun cas un avis médical professionnel. Pour tout problème de santé, consultez un médecin.


