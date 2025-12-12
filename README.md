# Fashion Trend Intelligence – Segmentation Vestimentaire

## Contexte
Ce projet s’inscrit dans le cadre du parcours **AI Engineer – OpenClassrooms**.  
Il vise à évaluer l’utilisation d’un modèle de segmentation vestimentaire
pré-entraîné (`SegFormer clothes`) via l’API serverless de Hugging Face.

L’objectif est de segmenter automatiquement les pièces vestimentaires
présentes sur des images d’influenceurs mode.

---

## Fonctionnalités
- Envoi d’images à l’API Hugging Face (serverless)
- Récupération des masques de segmentation
- Visualisation côte à côte : image originale / segmentation
- Traitement en batch (50 images)
- Estimation des coûts d’utilisation à l’échelle

---

## Technologies utilisées
- Python 3.9+
- Hugging Face Inference API
- Requests
- Pillow
- Matplotlib
- NumPy
- dotenv

---

## Installation

```bash
git clone https://github.com/TON_USER/fashion-trend-intelligence.git
cd fashion-trend-intelligence
pip install -r requirements.txt
