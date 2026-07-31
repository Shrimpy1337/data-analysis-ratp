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


- Station la plus fréquentée : Gare du Nord, avec 34 503 097 entrées annuelles.
- Part du trafic total concentrée par le top 10 des stations : les 10 stations les plus fréquentées (Gare du Nord, Saint-Lazare, Gare du Nord-RER, Gare de Lyon, Gare de Lyon-RER, Châtelet-Les Halles-RER, Montparnasse-Bienvenüe, La Défense-RER, Nanterre-Préfecture, Gare de l'Est) totalisent environ 250 millions d'entrées, soit près de 20 % du trafic total du réseau, alors qu'elles représentent moins de 3 % des 371 stations étudiées.
- Écart de fréquentation entre métro et RER : les deux réseaux ont une médiane de trafic très proche (~2,3 millions d'entrées par station), mais le RER présente une queue de distribution un peu plus étirée vers le haut, portée par les grandes gares d'interconnexion (Châtelet-Les Halles, La Défense, Gare de Lyon-RER).

## 👤 Auteur

**Yegor Tsyro** — Étudiant ingénieur, ISEP Paris
[yegor.tsyro@eleve.isep.fr](mailto:yegor.tsyro@eleve.isep.fr)
