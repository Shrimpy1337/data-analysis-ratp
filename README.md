# 🚇 Analyse du trafic annuel entrant — Réseau ferré RATP

Analyse exploratoire (EDA) du trafic voyageurs entrant sur le réseau ferré (métro + RER) de la RATP, à partir des données ouvertes publiées par la RATP.

## 🎯 Objectif

Identifier les stations les plus fréquentées du réseau et comprendre la distribution du trafic entre les différentes stations, afin d'en tirer des insights exploitables (concentration du trafic, écarts métro/RER, etc.).

## 📊 Source des données

[Open Data RATP — Trafic annuel entrant par station du réseau ferré](https://data.ratp.fr/explore/dataset/trafic-annuel-entrant-par-station-du-reseau-ferre-2021/export/), publié sous licence ouverte (Etalab).

## 🧱 Stack technique

- Python (Pandas, NumPy)
- Visualisation : Matplotlib, Seaborn
- Jupyter Notebook

## 🚀 Reproduire l'analyse

```bash
git clone https://github.com/Shrimpy1337/data-analysis-ratp.git
cd data-analysis-ratp
pip install -r requirements.txt

# Place le fichier CSV téléchargé depuis data.ratp.fr dans le dossier data/
jupyter notebook analyse_trafic_ratp.ipynb
```

## 🔍 Démarche

1. Chargement et inspection du dataset
2. Nettoyage : gestion des valeurs manquantes, doublons, conversion de types
3. Analyse exploratoire (EDA) : statistiques descriptives, top stations
4. Visualisations : classement des stations, distribution du trafic, comparaison métro/RER
5. Extraction d'insights

## 📈 Résultats clés

*(à compléter après exécution du notebook sur les données)*

- Station la plus fréquentée : —
- Part du trafic total concentrée par le top 10 des stations : —
- Écart de fréquentation entre métro et RER : —

## 👤 Auteur

**Yegor Tsyro** — Étudiant ingénieur, ISEP Paris
[yegor.tsyro@eleve.isep.fr](mailto:yegor.tsyro@eleve.isep.fr)
