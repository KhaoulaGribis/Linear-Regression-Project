# Régression Linéaire simple et multiple - Analyse des Données

Ce projet contient une analyse de données publicitaires à l'aide de modèles de régression linéaire simple et multiple. Les données utilisées proviennent du fichier `TV_Advertising.csv` et `donnees_clients1.xlsx`, et les analyses sont réalisées dans des notebooks Jupyter.

## Structure du projet

### Description des fichiers

- **`Régression Linéaire.ipynb`** : Notebook principal contenant les analyses de régression linéaire. Il inclut :
  - Chargement des données depuis `TV_Advertising.csv` pour la  régression linéaire simple et `donnees_clients1.xlsx` pour la  régression linéaire multiple .
  - Visualisation des relations entre les variables (nuages de points, droites de régression).
  - Ajustement de modèles de régression linéaire simple et multiple.
  - Tests statistiques (Durbin-Watson, White, Shapiro-Wilk) pour évaluer la qualité des modèles.
  - Résumé des résultats des modèles (coefficients, R², etc.).


- **`.ipynb_checkpoints/`** : Dossier contenant des sauvegardes automatiques des notebooks Jupyter.

## Instructions pour exécuter le projet

1. **Cloner le dépôt GitHub** :
   ```bash
   git clone <URL_DU_DEPOT>
   cd <NOM_DU_DEPOT>

2. **Installer les dépendances**  :
```bash pip install pandas numpy statsmodels matplotlib seaborn scipy scikit-learn```

3. **Exécuter le notebook** :
Ouvrez le notebook principal dans Jupyter Notebook ou JupyterLab :

```bash jupyter notebook Régression Linéaire.ipynb```