## Analyse des œuvres et des thèmes de la littérature russe

Ce dépôt contient les fichiers associés à une étude personnelle consacrée aux œuvres et aux thèmes de la littérature russe.

L’objectif du projet est d’analyser un corpus d’œuvres littéraires russes à partir d’une matrice binaire indiquant la présence ou l’absence de différents thèmes dans chaque œuvre. Les analyses produisent notamment des tableaux, des graphiques, des cartes factorielles, des classifications et des représentations de réseaux de co-occurrence thématique.

Contenu du dépôt

Le dépôt est organisé de la manière suivante :

- Data/ : données utilisées pour les analyses, notamment le fichier CSV principal.
- Notebooks/ : notebooks Jupyter permettant de reproduire les calculs et les graphiques.
- Images/ : graphiques produits par les notebooks.
- Docs/ : document final au format PDF.
- Scripts/ : éventuels scripts Python complémentaires.
- Document final

Le document final est disponible dans le dossier Docs/.
[Lire le document final](Docs/LittRu_analysis.pdf)
Si l’aperçu GitHub n’affiche pas correctement toutes les pages (70), utiliser le bouton
**Download raw file** pour télécharger le PDF complet.

Reproduire les analyses

Les notebooks du dossier Notebooks/ peuvent être exécutés séparément.
Ils utilisent les données contenues dans le dossier Data/ et produisent les graphiques enregistrés dans le dossier Images/.

Données

Les données sont construites à partir d’un codage thématique personnel des œuvres étudiées.
Chaque œuvre est associée à un ensemble de thèmes codés sous forme binaire : 1 lorsque le thème est présent, 0 lorsqu’il est absent.

### Logiciels utilisés

Les analyses ont été réalisées avec Python, notamment avec les bibliothèques suivantes :

- pandas
- numpy
- matplotlib
- scikit-learn
- scipy
- networkx

### Auteur

André Mery

### Licence

Le document, les données et les figures sont mis à disposition sous licence
Creative Commons Attribution 4.0 International (CC BY 4.0).

Les notebooks et scripts Python peuvent être réutilisés sous licence MIT.

### Remarques et corrections

Les remarques, questions ou corrections peuvent être signalées dans l’onglet Issues du dépôt.
