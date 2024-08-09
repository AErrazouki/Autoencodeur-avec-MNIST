# Description de ce code pour l'Autoencodeur avec MNIST

## Objectif

Ce code illustre comment construire et entraîner un autoencodeur en utilisant le jeu de données MNIST. Un autoencodeur est un type de réseau de neurones non supervisé qui apprend à reproduire ses entrées à ses sorties. L'objectif est de réduire la dimensionnalité des données tout en conservant les informations essentielles.

Le code comprend les étapes suivantes :

 ### 1. Chargement et Prétraitement des Données

  - Les données MNIST sont chargées à partir de la base de données, qui contient des images de chiffres manuscrits.

  - Les images en 2D (28x28 pixels) sont aplaties pour être utilisées comme vecteurs 1D (de taille 784) dans le modèle d'autoencodeur..

 ### 2. Définition du Modèle d'Autoencodeur Profond

  - Un autoencodeur avec plusieurs couches cachées est défini.

  - L'encodeur compresse les données d'entrée en une représentation plus petite.

  - Le décodeur reconstruit les données d'origine à partir de cette représentation comprimée.

 ### 3. Entraînement du Modèle

  - L'autoencodeur est entraîné sur les données d'entrée.

  - La perte de reconstruction est suivie pendant l'entraînement pour les données d'entraînement et de validation.

 ### 4. Évaluation et Visualisation

  - Le modèle est utilisé pour reconstruire les images du jeu de données de test.

 - Les images originales et reconstruites sont affichées côte à côte pour comparer les résultats de la reconstruction
