# 🌿 Leaffliction — Plant Disease Classification (Computer Vision)

![License](https://img.shields.io/github/license/raveriss/Leaffliction)
![Python 3.10](https://img.shields.io/badge/python-3.10-blue.svg)
[![CI](https://github.com/raveriss/Leaffliction/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/raveriss/Leaffliction/actions)
[![Coverage](https://codecov.io/gh/raveriss/Leaffliction/branch/main/graph/badge.svg)](https://codecov.io/gh/raveriss/Leaffliction)
[![Lint](https://img.shields.io/badge/lint-ruff%20✔-yellow.svg)]()
[![Typing](https://img.shields.io/badge/mypy-checked-purple.svg)]()
[![Mutation](https://img.shields.io/badge/mutmut-≥90%25-orange.svg)]()
[![Pre-commit](https://img.shields.io/badge/pre--commit-enabled-brightgreen?label=pre--commit)]()
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)]()
[![Security](https://img.shields.io/badge/security-bandit-green.svg)]()

---

## 📌 Overview

**Leaffliction** est un projet de **Computer Vision** visant à détecter automatiquement les maladies présentes sur des feuilles de plantes à partir d’images.  
Ce projet suit le sujet Leaffliction de l’École 42 et implémente un pipeline complet :

- 📊 Analyse du dataset  
- 🔄 Data augmentation (≥ 6 techniques)  
- 🎨 Transformations d’images (≥ 6 transformations)  
- 🧠 Classification via CNN (Deep Learning)  
- 📦 Export du modèle & génération d’une signature SHA1  
- ✔️ Accuracy ≥ 90 % sur la validation (≥ 100 images)

Le projet utilise **Python**, géré avec **Poetry** et outillé pour la qualité logicielle (tests, linter, CI, coverage, mutation testing).

---

## 📁 Structure du projet

```
Leaffliction/
├── src/
│   └── leaffliction/
│       ├── __init__.py
│       ├── distribution.py
│       ├── augmentation.py
│       ├── transformation.py
│       ├── training.py
│       ├── prediction.py
│       └── cli.py
│
├── scripts/
│   ├── Distribution.py
│   ├── Augmentation.py
│   ├── Transformation.py
│   ├── train.py
│   └── predict.py
│
├── tests/
├── .github/workflows/ci.yml
├── .pre-commit-config.yaml
├── .ruff.toml
├── mypy.ini
├── .coveragerc
├── codecov.yml
├── pyproject.toml
├── LICENSE
└── README.md
```

---

## ▶️ Installation (Poetry)

```bash
poetry install
poetry shell
```

---

## ▶️ Commandes principales

### Analyse du dataset
```bash
poetry run python scripts/Distribution.py ./Apple
```

### Data augmentation
```bash
poetry run python scripts/Augmentation.py ./Apple/apple_healthy/image.jpg
```

### Transformations
```bash
poetry run python scripts/Transformation.py -src ./Apple/apple_healthy/ -dst out/
```

### Entraînement
```bash
poetry run python scripts/train.py ./Apple
```

### Prédiction
```bash
poetry run python scripts/predict.py ./Apple/apple_healthy/image.jpg
```

---

## 🔐 Signature SHA1

```
sha1sum leaffliction_dataset_model.zip
```

---

## 📚 Stack technique

- Python 3.10+  
- PyTorch  
- Pillow / OpenCV / PlantCV  
- Pandas / NumPy  
- Poetry  
- pytest / coverage / Codecov  
- ruff / black / mypy / bandit / mutmut / pre-commit  
- GitHub Actions CI  

---

## © Licence

Licence **MIT**.

---

## 👤 Auteur

**Rafael Verissimo**  
Étudiant IA/Data – École 42 Paris  
GitHub : https://github.com/raveriss  
LinkedIn : https://www.linkedin.com/in/verissimo-rafael/
