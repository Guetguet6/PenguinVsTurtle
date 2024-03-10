**Projet de Classification d'Images : Pingouins vs Tortues**

Ce projet a été réalisé dans le cadre du cours de **Modélisation Mathématiques**.
L'objectif principal est de développer un modèle de classification d'images capable de distinguer les pingouins des tortues à partir d'un ensemble d'images.

## Auteurs

- [Dubois Gaétan](https://github.com/Guetguet6)
- [Hermant--Jakubowski Arthur](https://github.com/serpentox)

## Description du projet

Nous avons construit un modèle de classification basé sur l'architecture **Vision Transformer (ViT)** pour résoudre cette tâche. Le modèle a été entraîné sur un dataset personnalisé composé d'images de pingouins et de tortues, puis évalué sur un ensemble de validation distinct.

## Dataset

Le dataset utilisé pour ce projet comprend des images de haute qualité de pingouins et de tortues, collectées à partir de diverses sources en ligne. Il est structuré de la manière suivante :

- `data/train/train/` : Images d'entraînement de pingouins ainsi que de tortues
- `data/valid/valid/` : Images de validation de pingouins ainsi que de tortues

Les annotations correspondantes sont fournies dans les fichiers JSON `data/train_annotations.json` et `data/valid_annotations.json`.

Au total, le dataset contient **500 images d'entraînement** et **70 images de validation**, réparties équitablement entre les deux classes.

Le dataset est disponible sur [ce lien Kaggle](https://www.kaggle.com/datasets/abbymorgan/penguins-vs-turtles).

## Entraînement du modèle

Pour entraîner le modèle, vous pouvez simplement cliquer sur le badge [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Guetguet6/PenguinVsTurtle/blob/main/notebook.ipynb) pour ouvrir le notebook Google Colab associé à ce projet. Le notebook contient toutes les instructions nécessaires pour charger les données, entraîner le modèle et l'évaluer.

Le modèle entraîné sera sauvegardé dans le fichier `model_trained.pth`.