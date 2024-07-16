# Prédiction de Type de Cuisine

Ce projet utilise le traitement du langage naturel (NLP) pour prédire le type de cuisine en analysant les ingrédients d'une recette. Il met en œuvre des techniques de NLP avancées avec les bibliothèques spaCy et NLTK pour traiter et analyser les listes d'ingrédients.

## Installation

Assurez-vous que Python 3 est installé sur votre système pour utiliser ce projet.

### Dépendances

Installez les dépendances requises en exécutant les commandes suivantes :

pip install kaggle
pip install spacy
pip install nltk


Après avoir installé NLTK, téléchargez les ressources nécessaires :

import nltk
nltk.download('tokenize')
nltk.download('wordnet')
nltk.download('punkt')
nltk.download('averaged_perceptron_tagger')


## Utilisation

Exécutez le notebook pour effectuer la prédiction du type de cuisine. Le système prendra en entrée la liste des ingrédients et prédira la cuisine correspondante. Suivez les instructions dans le notebook pour les étapes spécifiques.

## Données

Les données pour ce projet proviennent de Kaggle. Configurez votre clé API Kaggle pour télécharger l'ensemble de données contenant les recettes et leurs ingrédients.

## Technologies Utilisées

- Python 3.x
- spaCy
- NLTK
- Kaggle API

## Contribution

Nous encourageons la contribution à ce projet ! Si vous avez des idées d'amélioration ou des corrections, soumettez une pull request.

## Licence

Distribué sous la Licence MIT. Voir le fichier `LICENSE` pour plus d'informations.
