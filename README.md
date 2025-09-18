 GDATA – Pipeline IA Automatisée

Ce projet implémente une **pipeline complète d’automatisation en Data Science et Machine Learning**, allant de l’exploration des données au déploiement du modèle.  
L’objectif est de **réduire le coût et le temps de traitement des données** tout en automatisant au maximum les tâches du data scientist.

---

# Fonctionnalités principales

 1. Exploration et Visualisation
- Génération de rapports interactifs (`ydata-profiling`).
- Analyse statistique, détection des valeurs manquantes et anomalies.

 2. Nettoyage des Données
- Suppression des doublons.
- Remplissage des valeurs manquantes par la moyenne.

 3. Ingénierie des Features
- Encodage des variables catégorielles.
- Normalisation des données avec `StandardScaler`.

 4. Annotation Automatique
- Réseau de neurones simple en **PyTorch**.
- Étiquetage automatique des données non labellisées.
- Sauvegarde du modèle d’annotation (`annotation_model.pth`).

 5. Gestion des Données Déséquilibrées
- Application de **SMOTE** pour équilibrer les classes minoritaires.

 6. Génération de Données Synthétiques
- Intégration d’un modèle GAN (`gan_generator.keras`) pour produire de nouvelles données.

 7. Sélection et Optimisation Automatique
- AutoML avec **TPOTClassifier** (recherche génétique).
- Sélection automatique du meilleur pipeline.

 8. Explicabilité
- Analyse de l’importance des variables avec **SHAP**.
- Génération de graphiques explicatifs (`shap_summary_plot.png`).

 9. Déploiement & Monitoring
- Intégration avec **MLflow** pour :
  - Versionner les modèles.
  - Suivre les expériences.
  - Faciliter le déploiement en production.

---

# Structure du projet

# gdata
datascientist-AI
