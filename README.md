# AI-Visual-Mood

Projet de Deep Learning consacré à l'analyse d'images et à la prédiction de caractéristiques liées à l'humeur ou aux émotions visuelles.

## 📌 Présentation

AI-Visual-Mood a pour objectif de construire une chaîne complète de Deep Learning, depuis la préparation des données jusqu'à l'entraînement et l'utilisation d'un modèle pour effectuer des prédictions sur des images.

Le projet est développé de manière progressive afin de conserver une organisation claire, reproductible et adaptée à un dépôt GitHub professionnel.

## 🎯 Objectifs

- Mettre en pratique les notions fondamentales des réseaux de neurones et du Deep Learning.
- Préparer et organiser un jeu de données d'images.
- Mettre en place un pipeline de prétraitement des données.
- Construire et entraîner un modèle de Deep Learning.
- Évaluer les performances du modèle.
- Effectuer des prédictions sur de nouvelles images.
- Ajouter des tests pour vérifier le bon fonctionnement du projet.
- Documenter les différentes étapes du développement.

## 📁 Structure du projet

```text
AI-Visual-Mood/
│
├── app/                    # Application / interface
│
├── data/
│   ├── raw/                # Données originales
│   ├── processed/          # Données prétraitées
│   └── README.md           # Documentation du dataset
│
├── docs/                   # Documentation du projet
│   └── PROJECT_PLAN.md     # Plan du projet
│
├── models/                 # Modèles entraînés
│
├── notebooks/              # Expérimentations et travaux pratiques
│   └── 01_environment.ipynb
│
├── src/                    # Code source principal
│   ├── data.py             # Chargement et préparation des données
│   ├── model.py            # Architecture du modèle
│   ├── train.py            # Entraînement
│   └── predict.py          # Prédiction
│
├── tests/                  # Tests automatisés
│   └── test_data.py
│
├── .gitignore
├── LICENSE
├── README.md
└── requirements.txt