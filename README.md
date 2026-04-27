# 🌿 Leaffliction — Plant Disease Classification (Computer Vision)

<div align="center">
  
![Python](https://img.shields.io/badge/Python-3.10-3776AB?logo=python&logoColor=white)
[![CI](https://img.shields.io/github/actions/workflow/status/raveriss/Total_Perspective_Vortex/ci.yml?branch=main&logo=githubactions&logoColor=white)](https://github.com/raveriss/Total_Perspective_Vortex/actions/workflows/ci.yml)
[![Coverage](https://codecov.io/gh/raveriss/Leaffliction/branch/main/graph/badge.svg)](https://codecov.io/gh/raveriss/Leaffliction)
![Norme 42](https://img.shields.io/badge/norm-42%20flake8-blue?logo=42&logoColor=white)![mypy](https://img.shields.io/badge/mypy-checked-6f42c1?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0iI2ZmZmZmZiIgZD0iTTMgMTlWNWgzLjJMMTIgMTIuNCAxNy44IDVIMjF2MTRoLTNWMTAuMWwtNC44IDYuMUgxMC44TDYgMTAuMVYxOXoiLz48L3N2Zz4%3D)
![Mutation](https://img.shields.io/badge/mutmut-%E2%89%A590%25-f08a24?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjZmZmZmZmIiBzdHJva2Utd2lkdGg9IjIiIHN0cm9rZS1saW5lY2FwPSJyb3VuZCI%2BPHBhdGggZD0iTTcgNGM0IDIuNSA2IDUuNSAxMCA4Ii8%2BPHBhdGggZD0iTTE3IDRjLTQgMi41LTYgNS41LTEwIDgiLz48cGF0aCBkPSJNNyAyMGM0LTIuNSA2LTUuNSAxMC04Ii8%2BPHBhdGggZD0iTTE3IDIwYy00IDIuNS02LTUuNS0xMC04Ii8%2BPC9nPjxnIGZpbGw9Im5vbmUiIHN0cm9rZT0iI2ZmZmZmZiIgc3Ryb2tlLXdpZHRoPSIyIiBzdHJva2UtbGluZWNhcD0icm91bmQiPjxwYXRoIGQ9Ik05IDdoNiIvPjxwYXRoIGQ9Ik04IDEyaDgiLz48cGF0aCBkPSJNOSAxN2g2Ii8%2BPC9nPjwvc3ZnPg%3D%3D)
![pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=precommit&logoColor=white)![black](https://img.shields.io/badge/code%20style-black-000000?logo=black&logoColor=white)
![security](https://img.shields.io/badge/security-bandit-2ea44f?logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPGcgZmlsbD0iI2ZmZmZmZiI%2BPHBhdGggZD0iTTEyIDNsNiAyLjJWOWMwIDEuMi0uNyAyLjMtMS44IDIuOGwtNC4yIDIuMS00LjItMi4xQTMuMSAzLjEgMCAwIDEgNiA5VjUuMnoiLz48cGF0aCBkPSJNNy41IDkuMmMuOS0xLjMgMi41LTIuMiA0LjUtMi4yczMuNi45IDQuNSAyLjJjLS44IDEuMy0yLjQgMi4yLTQuNSAyLjJzLTMuNy0uOS00LjUtMi4yeiIvPjxjaXJjbGUgY3g9IjEwIiBjeT0iOS4yIiByPSIxIi8%2BPGNpcmNsZSBjeD0iMTQiIGN5PSI5LjIiIHI9IjEiLz48cGF0aCBkPSJNMTEgMTMuNWgyVjE4aC0yeiIvPjxwYXRoIGQ9Ik05IDE3aDZ2Mkg5eiIvPjwvZz48L3N2Zz4%3D)
![License](https://img.shields.io/github/license/raveriss/Total_Perspective_Vortex?logo=github&logoColor=white)
  
</div>

##### Ce projet fait partie de mon [`🔗 PORTFOLIO`](https://raveriss.dev/) orienté **Data / IA / Software Engineering**

# 📑 Table des matières

- [📌 Overview](#-overview)
- [📁 Structure du projet](#-structure-du-projet)
- [🧪 1. Dataset Analysis — Distributionpy](#-1-dataset-analysis--distributionpy)
- [🔄 2. Data Augmentation — Augmentationpy](#-2-data-augmentation--augmentationpy)
- [🎨 3. Image Transformation — Transformationpy](#-3-image-transformation--transformationpy)
- [🧠 4. Classification — trainpy](#-4-classification--trainpy)
- [🔍 5. Prediction — predictpy](#-5-prediction--predictpy)
- [🔐 6. Signature SHA1 — signaturetxt](#-6-signature-sha1--signaturetxt)
- [🧩 Norme Python (42)](#-norme-python-42)
- [🛠️ Installation & environnement Poetry](#️-installation--environnement-poetry)
- [▶️ Exemples de commandes](#️-exemples-de-commandes)
- [✅ Qualité logicielle](#-qualité-logicielle)
- [📚 Stack technique](#-stack-technique)
- [🎯 Objectifs pédagogiques](#-objectifs-pédagogiques)
- [© Licence](#-licence)
- [👤 Auteur](#-auteur)

---

## 📌 Overview

**Leaffliction** est un projet de **Computer Vision** visant à détecter automatiquement les maladies présentes sur des feuilles de plantes à partir d’images.

Il suit le sujet *Leaffliction* de l’École 42 et implémente un pipeline complet :

- 📊 Analyse du dataset  
- 🔄 Data augmentation (≥ 6 techniques pour équilibrer les classes)  
- 🎨 Transformations d’images (≥ 6 transformations)  
- 🧠 Classification par Deep Learning (CNN)  
- ✔️ Accuracy ≥ 90 %  
- 🔐 Signature SHA1 pour validation
- 📂 Compatible avec toutes les plantes du dataset (tous les sous-dossiers)
- 🗂️ Les scripts doivent fonctionner avec n’importe quelle organisation du dataset
- 🚫 Le dataset, les images augmentées ou les modèles ne doivent jamais être commit


Développé en **Python 3.10+**, géré via **Poetry**, avec une stack qualité complète : pytest, ruff, mypy, mutmut, black, bandit, pre-commit, GitHub Actions & Codecov.

---

## 📁 Structure du projet

```
Leaffliction/
├── src/leaffliction/
│   ├── __init__.py
│   ├── distribution.py
│   ├── augmentation.py
│   ├── transformation.py
│   ├── training.py
│   ├── prediction.py
│   └── cli.py
│
├── scripts/
│   ├── Distribution.py
│   ├── Augmentation.py
│   ├── Transformation.py
│   ├── train.py
│   └── predict.py
│
├── tests/
│   ├── test_distribution.py
│   ├── test_augmentation.py
│   ├── test_transformation.py
│   ├── test_training.py
│   └── test_prediction.py
│
├── .github/workflows/ci.yml
├── .pre-commit-config.yaml
├── .ruff.toml
├── mypy.ini
├── .coveragerc
├── codecov.yml
├── pyproject.toml
├── poetry.lock
├── LICENSE
└── signature.txt
```

⚠️ Avertissement :  
- Le dataset **NE DOIT PAS** apparaître dans le dépôt (sinon 0 direct).  
- Les images augmentées, transformées et le modèle entraîné NE DOIVENT PAS être commit.  
- Seul `signature.txt` doit être présent.  

---

## 🧪 1. Dataset Analysis — `Distribution.py`

Objectifs :

- Explorer la structure du dataset  
- Calculer la répartition par maladies  
- Générer pie charts & bar charts
- Le programme doit fonctionner avec **toutes les plantes** du dataset
- Le nom des colonnes doit correspondre **exactement** au nom des dossiers des classes
- Les images doivent être correctement détectées même si les chemins contiennent des espaces
 

Exemple d’exécution :

```bash
poetry run python scripts/Distribution.py ./Apple
```

![Répartition du dataset](docs/images/dataset_distribution_apple.png)

*Répartition des images par catégories pour la plante **Apple**.  
Utilisé pour analyser l’équilibre du dataset avant augmentation.*

---

## 🔄 2. Data Augmentation — `Augmentation.py`

Objectifs :

- Équilibrer les classes  
- Appliquer ≥ 6 augmentations :
  - Flip, Rotate, Skew, Shear, Crop, Distortion
- Les images augmentées doivent être enregistrées dans **le même dossier que l’original**
- Une fois l’augmentation terminée, un dataset équilibré doit être produit dans :
```
augmented_directory/
```



Exemple :

```bash
poetry run python scripts/Augmentation.py ./Apple/apple_healthy/image.jpg
```

![Exemples de data augmentation](docs/images/data_augmentation_examples_apple_healthy.png)

*Exemples des 6 augmentations appliquées (Flip, Rotate, Skew, Shear, Crop, Distortion) sur une feuille healthy de la classe **apple_healthy**.*

---

## 🎨 3. Image Transformation — `Transformation.py`

Transformations possibles :

- Gaussian blur  
- Mask  
- ROI  
- Object analysis  
- Pseudolandmarks  
- Color histograms
- Le script doit accepter **une seule image** (affichage)
- Et **un dossier complet** (sauvegarde des résultats dans un dossier destination)
- Une aide doit être disponible via :

Exemples :

```bash
poetry run python scripts/Transformation.py ./Apple/apple_healthy/image.jpg
```
![Pipeline de transformations](docs/images/transform_pipeline_overview.png)

*Pipeline des transformations appliquées : original, Gaussian blur, mask, ROI objects,  
analyse d’objet, pseudolandmarks et histogramme de couleurs.*


Batch mode :

```bash
poetry run python scripts/Transformation.py -src ./Apple/apple_healthy -dst out/
```

---

## 🧠 4. Classification — `train.py`

Objectifs :

- Entraîner un CNN  
- Gérer train/validation  
- Atteindre **≥ 90 % accuracy**  
- Exporter un `.zip` conforme au sujet
- Le modèle doit être entraîné sur un dataset équilibré et transformé
- Le set de validation doit contenir **au moins 100 images**
- Le `.zip` final doit contenir :
  - le modèle entraîné
  - les images nécessaires
  - toutes les métadonnées utiles pour recharger le modèle
- Le modèle doit pouvoir être rechargé **uniquement à partir du `.zip`**


Commande :

```bash
poetry run python scripts/train.py ./Apple
```

---

## 🔍 5. Prediction — `predict.py`

```bash
poetry run python scripts/predict.py ./Apple/apple_healthy/image.jpg
```
![Exemple de prédiction DL](docs/images/dl_classification_prediction_peach_bacterial_spot.png)

*Exemple complet du script `predict.py` :  
image originale (gauche), image transformée (droite)  
→ Classe prédite : **peach_bacterial_spot**.*

Affiche :
- image originale  
- transformation  
- prédiction

- L’image prédite doit appartenir à une plante utilisée pour l’entraînement
- Le script doit afficher la classe prédite de manière lisible

---

## 🔐 6. Signature SHA1 — `signature.txt`

```bash
sha1sum leaffliction_dataset_model.zip
```

Copier la valeur dans :

```
signature.txt
```

⚠️ Mismatch = **note 0**.

- Le `.zip` doit inclure exactement :
  - le dataset préparé (augmenté et transformé)
  - le modèle entraîné
  - les fichiers nécessaires à la prédiction
- Le hash SHA1 fourni doit correspondre **exactement** au `.zip` utilisé pendant la soutenance
- Toute différence → **0 point**


---

## 🧩 Norme Python (42)

Le sujet impose :

```bash
pip install flake8
alias norminette_python="flake8"
```

### Vérifier la norme 42 Python
```bash
norminette_python src/ scripts/
```


**flake8** est requis pour le module 42, même si le projet utilise aussi
`ruff`, `black`, `mypy`, `bandit` & `mutmut` pour une qualité industrielle.

---

## 🛠️ Installation & environnement Poetry

### 1. Cloner

```bash
git clone https://github.com/raveriss/Leaffliction
cd Leaffliction
```

### 2. Installer

```bash
poetry install
```

### 3. Activer

```bash
poetry shell
```

ou :

```bash
poetry run <commande>
```

---

## ▶️ Exemples de commandes

Analyse :

```bash
poetry run python scripts/Distribution.py ./Apple
```

Augmentation :

```bash
poetry run python scripts/Augmentation.py ./Apple/apple_healthy/image.jpg
```

Transformations :

```bash
poetry run python scripts/Transformation.py -src ./Apple/apple_healthy -dst out/
```

Training :

```bash
poetry run python scripts/train.py ./Apple
```

Prediction :

```bash
poetry run python scripts/predict.py ./Apple/apple_healthy/image.jpg
```

---

## ✅ Qualité logicielle

⚠️ Toute erreur, crash, exception Python, ou arrêt inattendu dans un des scripts  
entraîne l’arrêt immédiat de l’évaluation (note potentiellement 0).

Tests :

```bash
poetry run pytest
```

Coverage :

```bash
poetry run pytest --cov=leaffliction --cov-report=term-missing
```

Mutation testing :

```bash
poetry run mutmut run
```

Lint:

```bash
poetry run ruff check src tests
```

Format :

```bash
poetry run black src tests
```

Typing :

```bash
poetry run mypy src
```

Sécurité :

```bash
poetry run bandit -r src
```

Pre-commit :

```bash
poetry run pre-commit run --all-files
```

---

## 📚 Stack technique
- ### Langage & packaging
   - Python 3.10+
   - Poetry (gestion des dépendances & scripts)
- ### Computer Vision & ML
  - PyTorch (CNN de classification)
  - NumPy / Pandas
  - Pillow / OpenCV / PlantCV
- ### Tests & qualité
  - pytest, coverage, Codecov
  - flake8 (norme 42 via norminette_python)
  - ruff, black, mypy
  - mutmut (mutation testing)
  - bandit (analyse de sécurité)
  - pre-commit (orchestration des hooks)
- ## CI/CD
  - GitHub Actions (lint + tests + coverage + upload Codecov)

---

## 🎯 Objectifs pédagogiques

- Pipeline complet de Computer Vision  
- Data augmentation avancée  
- CNN robuste avec >90% accuracy  
- Projet reproductible via Poetry  
- CI/CD & qualité logicielle niveau entreprise  

---

## © Licence

MIT License.

---

## 👤 Auteur

**Rafael Verissimo**  
Étudiant IA/Data — École 42 Paris  
GitHub : https://github.com/raveriss  
LinkedIn : https://www.linkedin.com/in/verissimo-rafael/<br>
Portfolio : https://raveriss.dev/
