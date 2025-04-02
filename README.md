# NLP: Classification des Hymnes Nationaux par Continent

Ce projet utilise des techniques de traitement du langage naturel (NLP) pour classer les hymnes nationaux selon leur continent d'origine.

## Description du projet

Le notebook `NLP_B2_AIV.ipynb` contient une analyse complète d'un dataset contenant les hymnes nationaux de différents pays, avec pour objectif de prédire le continent d'origine d'un hymne à partir de son texte.

### Dataset
Le dataset utilisé, "National Anthems of the World", contient 5 variables :
- Country: Le nom du pays
- Alpha-2: Le code à deux lettres du pays
- Alpha-3: Le code à trois lettres du pays
- Continent: Le continent du pays (cible)
- Anthem: L'hymne national du pays (feature)

### Méthodologie
1. **Prétraitement des textes** :
   - Nettoyage de base
   - Suppression de la ponctuation
   - Lemmatisation
   - Suppression des stopwords
   - Tokenisation
   - Vectorisation avec TF-IDF

2. **Classification** :
   - Utilisation d'un modèle SVM
   - Séparation des données en train/test (80%/20%)

## Résultats
Le modèle atteint une précision de [X]% sur les données de test.

## Comment exécuter
1. Cloner le dépôt
2. Installer les dépendances : `pip install -r requirements.txt`
3. Exécuter le notebook Jupyter

## Dépendances
- Python 3.x
- pandas
- numpy
- scikit-learn
- nltk
- matplotlib
- seaborn

## Auteur
[Votre nom]

## Licence
[MIT]
