# PlantEvoViewer

Site web statique (HTML/CSS) pour expliquer l'origine et l'évolution des plantes.
Le projet est encore en cours de réalisation.

## Lancer le site

Aucune installation n'est requise.

1. Télécharger ou cloner le dépôt
2. Ouvrir `index.html` dans le navigateur

## Organisation des fichiers

```
plantEvo/
├── index.html              page d'accueil
├── algues.html
├── mousses.html
├── fougeres.html
├── coniferes.html
├── graminees.html
├── dicotyledones.html
├── styles/                 un fichier CSS par page (+ style.css pour l'accueil)
├── images/                 logos, bannières et schémas (.webp, .jpg, .png)
└── assets/
    ├── dataset.csv                   points relevés sur le terrain
    ├── zone-dechantillonnage.qgz     projet QGIS de la zone d'étude
    ├── Photo de terrain/             photos classées par groupe de plantes
    └── Rapports/
        ├── Rapport_SIG_PlantEvo.odt
        └── Rapport_TP_PlantEvo.odt
```

## Les données de terrain

Le fichier `assets/dataset.csv` contient 6 points d'observation (un par groupe de plantes).
Les photos prises sur place sont dans `assets/Photo de terrain/`, et la carte de la zone est dans `images/carte.png`.

## Outils utilisés

HTML, CSS, Git, QGIS (pour la carte), Figma (pour la maquette).

## DESIGN FIGMA
*NB: Design inachévé*<br>
<https://www.figma.com/design/VrveYFoDuGGxFGvqJEkt1E/Sans-titre?node-id=0-1\&p=f\&t=7PMPAMyR7h4h6F84-0>

## DIFFICULTES

* gestion du temps avec les cours, les exercies, et le brief projet
* manque de pratique avec CSS

