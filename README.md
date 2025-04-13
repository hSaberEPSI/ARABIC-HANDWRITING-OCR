# Arabic Handwriting OCR

Reconnaissance automatique de l'écriture manuscrite arabe à partir d'images de mots ou de lignes manuscrites, pour des cas d’usage tels que la transcription, l’archivage et l’analyse linguistique.

## 🧠 Objectifs

- Construire un modèle OCR entraîné sur plusieurs datasets (Calliar, HICMA, etc.).
- Implémenter un pipeline MLOps modulaire et reproductible.
- Fournir une API pour l’inférence utilisable dans une application web.

## 🗂️ Structure du projet

```bash
arabic-handwriting-ocr/
├── data/           # Données brutes et traitées
├── notebooks/      # Analyses exploratoires
├── src/            # Code source : preprocessing, training, models
├── scripts/        # Scripts exécutables (train, predict, etc.)
├── experiments/    # Résultats d’entraînement
├── config.yaml     # Configuration centralisée
├── requirements.txt
└── README.md
```

## 🚀 Lancer l'entraînement

```bash
python scripts/train_model.py --config config.yaml
```

## 🧪 Prédiction

```bash
python scripts/predict_from_image.py --image_path path/to/image.png
```

## 📦 Datasets supportés

- Calliar
- HICMA
- IFN/ENIT
- AHCD
- Hijja

## 📄 Licence

Projet sous licence MIT.
