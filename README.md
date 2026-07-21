## Analyse des œuvres et des thèmes de la littérature russe

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21206585.svg)](https://doi.org/10.5281/zenodo.21206585)

Ce dépôt contient les fichiers associés à une étude personnelle consacrée aux œuvres, aux auteurs et aux thèmes de la littérature russe.

L’objectif du projet est d’analyser un corpus d’œuvres littéraires russes à partir d’une matrice binaire indiquant la présence ou l’absence de différents thèmes dans chaque œuvre.

Les analyses produisent notamment des tableaux, des graphiques, des cartes factorielles, des classifications, des représentations de réseaux de co-occurrence thématique et une analyse des correspondances entre auteurs et thèmes.

## Contenu du dépôt

Le dépôt est organisé de la manière suivante :

- `Data/` : 25 fichiers CSV et XLSX contenant les données utilisées ou produites par les analyses ;
- `Notebooks/` : 23 notebooks Jupyter organisés par objets d’étude et par méthodes d’analyse ;
- `Images/` : 40 figures générées par les notebooks et utilisées dans le document ;
- `Docs/` : document complet au format PDF, au format Word et dans une version PDF compressée.

## Document final

Le document complet de 87 pages est disponible dans le dossier `Docs/`.

- [Lire le document complet au format PDF](Docs/LittRu_analysis_X.pdf)
- [Télécharger le document au format Word](Docs/LittRu_analysis_X.docx)
- [Télécharger la version PDF compressée](Docs/LittRu_analysis_X_compressed.pdf)

Si l’aperçu de GitHub n’affiche pas correctement toutes les pages du document PDF, utiliser le bouton **Download raw file** pour télécharger le fichier complet.

## Reproduire les analyses

Les notebooks du dossier `Notebooks/` peuvent être exécutés séparément.

Ils utilisent les fichiers contenus dans le dossier `Data/` et produisent notamment les tableaux et les graphiques enregistrés dans le dossier `Images/`.

Chaque notebook fonctionne indépendamment, dans la mesure où il peut accéder aux fichiers nécessaires du dossier `Data/`.

## Données

Les données sont construites à partir d’un codage thématique personnel des œuvres étudiées.

Chaque œuvre est associée à un ensemble de thèmes codés sous forme binaire :

- `1` lorsque le thème est présent ;
- `0` lorsque le thème est absent.

Des fichiers intermédiaires au format CSV ou XLSX sont également produits par certaines analyses afin d’être réutilisés dans d’autres notebooks.

## Logiciels utilisés

Les analyses ont été réalisées avec Python, notamment avec les bibliothèques suivantes :

- pandas
- numpy
- matplotlib
- scipy
- scikit-learn
- networkx
- prince
- adjustText
- openpyxl

## Auteur

André Mery

## Licence

Le document, les données et les figures sont mis à disposition sous licence Creative Commons Attribution 4.0 International — CC BY 4.0.

Les notebooks Python peuvent être réutilisés sous licence MIT.

## Remarques et corrections

Les remarques, questions ou corrections peuvent être signalées dans l’onglet `Issues` du dépôt.