# Introduction à R


## Avant la formation

1. Installer les packages R suivant

```R
install.packages(c("tidyverse", "sf", "raster", "mapview", "vegan", "ade4",
  "scales", "xaringan"))
# Manipulation de données et figures
library(tidyverse) # charge 8 packages
# Spatial
library(sf)
library(raster)
library(mapview)
# Ordinations
library(ade4)
library(vegan)
library(scales)
# Pour reproduire la présentation
library(xaringan)
```

## Plan de la formation

- [ ] Introduction générale (*0.5h*) => Kev
  - [ ] Qu'est-ce que R?
  - [ ] Pourquoi utiliser R?
  - [ ] Quelques references importantes
  - [ ] ouvrir R et RStudio
  - [ ] répertoire de travail
  - [ ] objets et functions
- [ ] Manipulation de données avec `dplyr` (*1h*) => Kev
  - [ ] lecture d'une table `csv`
  - [ ] ajout de colonnes
  - [ ] modifications de colonnes
  - [ ] changement de format du tableau (long/large)
  - [ ] aggregations
  - [ ] Joindre des tableaux de données
  - [ ] enregistrement
- [ ] Graphiques avec base plot et ggplot2 (*1.5h*) => KC
  - [ ] plot de base (boxplot, nuage de point, histogramme...)
  - [ ] Ajouter des couches, changer les axes
  - [ ] taille et couleur de symbole
  - [ ] layout
  - [ ] Enregistrer une figure
- [ ] Cartes avec `sf` (*1.5h*) => MH
  - [ ] importer données spatiales (shapefile et raster)
  - [ ] mettre dans le même système de références
  - [ ] faire une carte assez complète
  - [ ] petit exemple mapview
- [ ] Ordinations: PCA et RDA (*1.5h*) => MH
  - [ ] faire une pca et une rda
  - [ ] faire les tests et interprétations
  - [ ] transformation des données
  - [ ] figures
