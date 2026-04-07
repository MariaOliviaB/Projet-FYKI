# Projet de Physique des Matériaux (LMAPR1492) - Étude du AlGaN₂

Ce README contient le travail de groupe réalisé par Antoine Julianne, Bohy Maria-Olivia, Dumont Louisa ainsi que Salée de Béthune Apolline, dans le cadre du cours **LMAPR1492**. L'objectif est l'analyse approfondie des propriétés cristallographiques, électroniques et vibrationnelles d'un matériau spécifique via un notebook Jupyter.

## Matériau étudié
* **ID Materials Project** : [mp-1008556](https://next-gen.materialsproject.org/materials/mp-1008556)

## Fonctionnalités du Notebook
Le dépôt `Projet-FYKI` (répertorié localement sous le nom `Projet_PhysMat`) permet de réaliser les analyses suivantes : 

### 1. Cristallographie (fichier lattice.ipynb)
* Télécharger la structure du matériau attribué.
* Détermination des réseaux direct et réciproque.
* Identification du système cristallin, du type de maille et du groupe ponctuel.
* Calcul du diffractogramme (Cu Kα).

### 2. Symétrie (fichier symmetry.ipynb)
* Visualisation de l'effet de trois opérations de symétrie ponctuelle distinctes.

### 3. Structure électronique (fichier el_bands.ipynb)
* Télécharger la structure de bandes électroniques.
* Analyse de la bande interdite.
* Étude de la dispersion des bandes de valence et de conduction.
* Calcul des masses effectives.

### 4. Bandes de phonons (fichier ph_bands.ipynb)
* Télécharger la structure de bandes de phonons.
* Visualiser la zone de Brillouin.
* Calcul de la vitesse du son dans différentes directions.

### 5. Densité de phonons (fichier ph_dens.ipynb)
* Télécharger la densité d'états de phonons.
* Calculer les températures de Debye ΘD et d'Einstein ΘE 
* Modélisation de la chaleur spécifique ($C_v$) via les modèles de Debye et Einstein.
* Comparaison des densités d'états de phonons.

## Sources
- cours LMAPR1492
- https://next-gen.materialsproject.org/materials/mp-1008556
- Intelligences artificielles (ChatGPT et Gemini)

## Installation
Pour exécuter ce notebook, vous aurez besoin de Python 3 et des bibliothèques indiquées dans l'encardé au début de chaque fichier ipynb. 
Vous pouvez utiliser la commande :
```bash
pip install 
