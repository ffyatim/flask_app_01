# P7-Scoring - Implementez & Deployez un scoring modèle
Part-2. API for prediction

1. Objectif du projet: (voir Repertoire part-1 @ 'modelisation_app_01)
L’entreprise souhaite:

2. Spécifications du dashboard: Permettre de visualiser le score et l’interprétation de ce score pour chaque client de façon intelligible pour une personne non experte en data science. Permettre de visualiser des informations descriptives relatives à un client (via un système de filtre). Permettre de comparer les informations descriptives relatives à un client à l’ensemble des clients ou à un groupe de clients similaires.

3. Code: flask_app_01.py. Cette partie du code concerne la mise en place d'une API interface programmatique pour calculer et livrer la prediction d'un client en reponse aux application demandeuses. Deux autres parties (modelisation - ipynb) et (dashboard - Streamlit) sont presentées dans des repertoires indépendants.

4. Données en entrée:

- Fichiers csv: resultats de la EDA pre-traitement:
  application_sample.csv : Fichier nettoyé et pre-traité (EAD)
  X_train_sample.csv: Fichier csv d'entrainement du modele
  XGB_clf_model_f.pkl : Le XGBoostClassifier modele

5. Données en sortie:
- La prediction (probabilite entre 0 et 1)
