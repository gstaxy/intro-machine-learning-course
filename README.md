[🇬🇧 English](README.en.md) | **🇫🇷 Français**

# Introduction à l'Apprentissage Automatique avec Python

> ⚠️ *This course have been created, developed and thought in a French speaking environment. There's no plan to translate the content to English unless there's is a strong demand. Given the amount of generally available content in English, this will serve as an alternative for French speakers. A light version of this readme in English is available on the link a the top ⬆.*

## Préparation au cours
Ce cours requiert une connaissance de base de programmation avec python. Si vous n'avez jamais ou très peu utilisé python dans le passé, il est fortement recommendé de compléter un cours d'introduction en ligne. 

Je recommande personnellement le cours *[Codeacademy: Learn Python 3](https://www.codecademy.com/learn/learn-python-3)* pour une courbe d'apprentissage adaptée à tous les niveaux.

## Guide d'utilisation

Le repo contient 4 dossiers principaux:
- `/cheatsheets`: Collection d'aides mémoire pour l'utilisation des librairies python.
- `/cours`: Contenu du cours, chapitre par chapitre.
- `/docs`: Documents divers associés au cours.
- `/données`: Données en format `.csv` utilisées durant le contenu théorique et pratique du cours, prêtes à être importées dans un notebook.

### Curriculum
Un curriculum complet du cours est [disponible dans les docs](docs/curriculum_du_cours.pdf).

Vous y retrouverez chaque thème abordé et toutes les techniques enseignées dans le cadre de ce cours en détail.

### Environnement de travail
Avant de débuter le cours, il est important de préparer son environnement de travail python.

> 💡 Si votre environnement n'est pas encore prêt, vous pouvez suivre les instructions du [chapitre 1 - mise en place de l'environnement python](cours/chapitre_1_mise_en_place_environnement_python).

### Apprentissage

Chaque chapitre de cours comprends:
1. `.pdf` théorique sous forme de diapositives (contenu abrégé)
2. notebook `.ipynb` théorique démontrant les concepts et techniques du `.pdf` théorique
3. notebook `.ipynb` pratique + un corrigé pour valider les réponses

Il est recommandé de lire le pdf rapidement d'abord, puis d'ouvrir le notebook théorique à côté par la suite pour expérimenter.

### Notebooks pratiques
Il y a en plus 2 notebooks pratiques qui seront réutilisés incrémentallement de chapire en chapitre:
1. [notebook_pratique_classification_binaire.ipynb](cours/chapitre_3_charger_données/notebook_pratique_classification_binaire.ipynb) pour les exercices pratiques de classification binaire
2. [notebook_pratique_régression.ipynb](cours/chapitre_9_évaluation_algorithmes/notebook_pratique_régression.ipynb) pour les exercices pratiques de régression

Il est recommandé de réutiliser les deux mêmes notebooks tout au long du cours en rajoutant au même notebook pratiques les nouveaux exercices/questions décrits dans le notebook théorique de chaque chapitre.

## Structure du repo

```bash
.
├── cheatsheets
│   ├── Cheatsheet_Jupyter_Notebook_Markdown.pdf
│   ├── Cheatsheet_Python_Matplotlib.pdf
│   ├── Cheatsheet_Python_Numpy.pdf
│   ├── Cheatsheet_Python_Pandas.pdf
│   ├── Cheatsheet_Python_Scikit_Learn.pdf
│   └── Cheatsheet_Python_Seaborn.pdf
├── cours
│   ├── chapitre_00_programmation_python
│   │   ├── 0_introduction_intelligence_artificielle.pdf
│   │   ├── 0_introduction_programmation.pdf
│   │   └── 0_test_installation.ipynb
│   ├── chapitre_01_mise_en_place_environnement_python
│   │   ├── 1_écosystème_python_avec_anaconda.pdf
│   │   ├── 1_écosystème_python_avec_google_colaboratory.pdf
│   │   ├── 1_guide_installation_anaconda.pdf
│   │   ├── 1_guide_installation_google_colaboratory.pdf
│   │   └── 1_notebook_exploratoire.ipynb
│   ├── chapitre_02_python_scipy
│   │   ├── 2_notebook_pratique_corrigé.ipynb
│   │   ├── 2_notebook_pratique.ipynb
│   │   ├── 2_notebook_théorique.ipynb
│   │   └── 2_théorie.pdf
│   ├── chapitre_03_charger_données
│   │   ├── 3_notebook_théorique.ipynb
│   │   ├── 3_pratique_classification_binaire_corrigé.ipynb
│   │   ├── 3_théorie.pdf
│   │   └── notebook_pratique_classification_binaire.ipynb
│   ├── chapitre_04_statistiques_descriptives
│   │   ├── 4_notebook_théorique.ipynb
│   │   ├── 4_pratique_classification_binaire_corrigé.ipynb
│   │   └── 4_théorie.pdf
│   ├── chapitre_05_visualisation_données
│   │   ├── 5_notebook_théorique.ipynb
│   │   ├── 5_pratique_classification_binaire_corrigé.ipynb
│   │   └── 5_théorie.pdf
│   ├── chapitre_06_traitement_données
│   │   ├── 6_notebook_théorique.ipynb
│   │   ├── 6_pratique_classification_binaire_corrigé.ipynb
│   │   └── 6_théorie.pdf
│   ├── chapitre_07_sélection_variables
│   │   ├── 7_notebook_théorique.ipynb
│   │   ├── 7_pratique_classification_binaire_corrigé.ipynb
│   │   └── 7_théorie.pdf
│   ├── chapitre_08_échantillonnage
│   │   ├── 8_notebook_théorique.ipynb
│   │   ├── 8_pratique_classification_binaire_corrigé.ipynb
│   │   └── 8_théorie.pdf
│   ├── chapitre_09_évaluation_algorithmes
│   │   ├── 9_notebook_théorique.ipynb
│   │   ├── 9_pratique_classification_binaire_corrigé.ipynb
│   │   ├── 9_pratique_régression_corrigé.ipynb
│   │   ├── 9_théorie.pdf
│   │   └── notebook_pratique_régression.ipynb
│   ├── chapitre_10_algorithmes_classification
│   │   ├── 10_notebook_théorique.ipynb
│   │   ├── 10_pratique_classification_binaire_corrigé.ipynb
│   │   └── 10_théorie.pdf
│   ├── chapitre_11_algorithmes_régression
│   │   ├── 11_notebook_théorique.ipynb
│   │   └── 11_théorie.pdf
│   └── chapitre_12_
│       ├── 12_notebook_théorique.ipynb
│       └── 12_théorie.pdf
├── docs
│   └── curriculum_du_cours.pdf
├── données
│   ├── banknote.csv
│   ├── concrete.csv
│   ├── diabetes.csv
│   └── energy_efficiency.csv
├── README.en.md
└── README.md
```

---
### *Notes:*
- *Ce cours a été développé sur la base des dernières technologies et versions de librairies python de 2021. Avec l'essor des LLM, de nombreux concepts enseignés pourraient désormais être adaptés à la réalité actuelle. Cependant, le contenu reste très pertinent lorsque l'on aborde l'apprentissage à partir d'un point de vue pragmatique et fondamental.*

---
*Disclaimer / Clause d'utilisation: Ce cours est à but non-lucratif, non-commercial et éducatif seulement.*