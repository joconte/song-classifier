# Song Classifier using Deep Learning

Projet de classification de musique par style musical.
Ce projet a été réalisé dans le cadre d'un cours sur le Deep Learning à l'EPSI Montpellier, cours prodigué par M. ALTAZIN Thomas.

# Outils utilisés

- Librosa
- FastAI
- Jupyter Notebook
- Python3

# Groupe de travail

- JACQUES Nils
- SEVRAIN Florian
- LASPOUGEAS Thomas
- CONTE Jonathan

# Constitution de nos datasets

Recherche de playlist de musique sur Youtube et téléchargement des musiques via ce site : https://loader.to/fr/

Split des musiques dans les répertoires `train` et `test` (du répertoire `song`) ainsi que par style musical.

Transformation des fichiers audio en spectrogramme de 00:30 à 01:00 dans le répertoire `image-from-song`

# Comment effectuer des prédictions avec notre modèle sans l'entrainer à nouveau ?

Prérequis : 
- Librosa
- FastAI
- Jupyter Notebook
- Python3

Etapes :
- Cloner le repository : `git clone https://github.com/joconte/song-classifier.git`
- Positionnez vous dans le projet : `cd song-classifier`
- Exécuter un Jupyter Notebook : `jupyter notebook song_classifier.ipynb`
- Exécuter les cellules suivantes du Jupyter Notebook : 
  - Chargement des dépendances pour la transformation d'audio en image
  - Création de notre méthode de transformation d'audio en image
  - Import des dépendances de FASTAI pour effectuer notre classification
  - Chargement de notre modèle
  - Prédiction

