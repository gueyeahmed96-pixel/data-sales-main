# Analyse des Données de Ventes 2019

## 📄 Description du Projet

Ce projet a pour objectif d'analyser les données de ventes d'une année complète (2019) afin d'en extraire des informations exploitables. L'analyse est réalisée à travers un notebook Jupyter (`exploration_ventes.ipynb`) et vise à répondre à plusieurs questions commerciales clés pour orienter les futures stratégies marketing et de vente.

## 📊 Données

Le jeu de données est initialement réparti dans plusieurs fichiers CSV, chacun représentant un mois de l'année 2019. Ces fichiers sont fusionnés en un seul DataFrame pour l'analyse.

Les colonnes principales incluent :
- `Order ID` : Identifiant unique de la commande
- `Product` : Nom du produit acheté
- `Quantity Ordered` : Quantité de produit commandée
- `Price Each` : Prix unitaire du produit
- `Order Date` : Date et heure de la commande
- `Purchase Address` : Adresse de livraison

## 🚀 Installation et Lancement

Pour exécuter ce projet, vous devez avoir Python et les bibliothèques suivantes installées.

1.  **Clonez le dépôt (si applicable) ou téléchargez les fichiers.**

2.  **Installez les dépendances :**
    ```bash
    pip install pandas numpy plotly seaborn jupyterlab
    ```

3.  **Lancez Jupyter Lab ou Jupyter Notebook :**
    ```bash
    jupyter lab
    ```

4.  **Ouvrez et exécutez le notebook `exploration_ventes.ipynb`.**

## 🔍 Questions Analysées

L'analyse menée dans le notebook cherche à répondre aux questions suivantes :

1.  **Quel a été le meilleur mois pour les ventes et quel chiffre d'affaires a été réalisé ?**
    - Identification des pics de ventes saisonniers.

2.  **Dans quelle ville avons-nous enregistré le plus de commandes ?**
    - Analyse géographique des ventes pour identifier les marchés clés.

3.  **À quel moment de la journée devrions-nous diffuser de la publicité pour maximiser les ventes ?**
    - Identification des heures de pointe pour les achats afin d'optimiser les campagnes publicitaires.

4.  **Quel produit se vend le plus ? Y a-t-il une corrélation avec son prix ?**
    - Analyse de la performance des produits et de la relation entre le prix et la demande.

5.  **Quelles combinaisons de produits sont les plus souvent vendues ensemble ?**
    - Identification d'opportunités de ventes croisées (cross-selling) et d'offres groupées (bundles).

## 🛠️ Outils Utilisés

- **Langage** : Python 3
- **Bibliothèques d'analyse** : Pandas, NumPy
- **Bibliothèques de visualisation** : Plotly, Seaborn
- **Environnement** : Jupyter Notebook
