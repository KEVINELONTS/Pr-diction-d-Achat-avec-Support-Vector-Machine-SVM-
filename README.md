# Pr-diction-d-Achat-avec-Support-Vector-Machine-SVM-
Ce projet consiste à appliquer un algorithme de Support Vector Machine (SVM) pour prédire si un utilisateur achètera un produit ou non, à partir de données issues des réseaux sociaux.  Le modèle est entraîné sur le dataset Social Network Ads, en utilisant deux variables explicatives :  l’âge  le salaire estimé

echnologies utilisées

Python

NumPy

Pandas

Matplotlib

Scikit-learn

 Structure du projet
├── Social_Network_Ads.csv
├── SVM_Social_Network_Ads.ipynb
└── README.md
 Étapes du projet

Importation des bibliothèques nécessaires

Chargement et préparation du dataset

Séparation des données en Training set et Test set

Construction du modèle SVM avec noyau linéaire

Entraînement du modèle

Prédiction des résultats

Évaluation du modèle à l’aide de la matrice de confusion

Modèle utilisé

Algorithme : Support Vector Machine (SVM)

Kernel : Linéaire

Bibliothèque : sklearn.svm.SVC

Résultats

Le modèle permet de comparer :

les valeurs réelles

les valeurs prédites

Une matrice de confusion est utilisée pour évaluer les performances du classificateur.

Comment exécuter le projet

Cloner le dépôt :

git clone https://github.com/ton-username/nom-du-repo.git


Installer les dépendances :

pip install numpy pandas matplotlib scikit-learn


Ouvrir le notebook :

jupyter notebook

 Améliorations possibles

Normalisation des données

Visualisation graphique des frontières de décision

Test d’autres kernels (RBF, polynomial)

Calcul de l’accuracy, precision et recall

 Auteur

Projet réalisé par lntsi kevine
