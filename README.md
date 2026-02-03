# Bitcoin, Inflation et Croissance Économique  
### Analyse économétrique et empirique

##  Description du projet
Ce projet propose une analyse empirique approfondie du lien entre le rendement du Bitcoin, l’inflation et la croissance économique. L’objectif principal est d’évaluer si le Bitcoin peut être considéré comme un actif macroéconomique, notamment comme une couverture contre l’inflation ou un actif lié à l’économie réelle.

L’étude repose sur des données mensuelles et mobilise plusieurs outils économétriques afin d’analyser les relations statiques, dynamiques et causales entre les variables.

---

##  Données
- **Bitcoin** : Prix mensuel (USD)
- **Inflation** : Indice des prix à la consommation (CPI)
- **Croissance économique** : Indice de production industrielle (INDPRO)
- **Période** : 2015 – 2025
- **Fréquence** : Mensuelle

Les données sont transformées afin d’assurer la stationnarité des séries (rendements logarithmiques, différenciation).

---

##  Méthodologie
Les méthodes économétriques suivantes sont utilisées :

- Statistiques descriptives
- Analyse de corrélation (statique et dynamique)
- Régression linéaire (OLS)
- Tests de causalité au sens de Granger
- Modèle VAR (Vector AutoRegression)
- Fonctions de réponse impulsionnelle (IRF)
- Décomposition de la variance des erreurs de prévision (FEVD)

Cette approche permet d’examiner à la fois les relations moyennes et leur évolution dans le temps.

---

## Principaux résultats
- Le rendement du Bitcoin présente une volatilité nettement supérieure à celle des variables macroéconomiques.
- Les corrélations entre le Bitcoin, l’inflation et la croissance économique sont faibles et instables.
- Les estimations OLS montrent l’absence d’effet significatif de l’inflation et de la croissance sur le rendement du Bitcoin.
- Les tests de causalité de Granger n’indiquent aucune relation causale significative.
- Les analyses VAR et IRF confirment que les chocs macroéconomiques ont un impact faible et transitoire sur le Bitcoin.

Dans l’ensemble, les résultats suggèrent que le Bitcoin ne peut pas être considéré comme une couverture inflationniste fiable ni comme un actif étroitement intégré à l’économie réelle.

---

##  Technologies utilisées
- Python
- pandas
- numpy
- matplotlib
- seaborn
- statsmodels
- Google Colab

---

## Structure du projet
- `bitcoin_empirical_analysis.ipynb` : Notebook principal contenant l’ensemble de l’analyse empirique
- `README.md` : Description du projet et de la méthodologie

---

##  Conclusion
Ce projet met en évidence le caractère principalement financier et spéculatif du Bitcoin. Malgré certaines interactions ponctuelles avec l’économie réelle, le Bitcoin évolue selon une dynamique largement autonome, distincte des fondamentaux macroéconomiques traditionnels.

---

## Auteur
Fatma Zaarour  
Analyse économétrique et data analysis

