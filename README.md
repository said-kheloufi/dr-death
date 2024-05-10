# Dr Death
## Le médecin meurtrier

# Introduction

Ce projet exploite la puissance de Microsoft Power BI pour déchiffrer et représenter graphiquement le modèle des crimes perpétrés par Harold Shipman, tristement célèbre sous le nom de Dr. Mort. Il a été jugé coupable de l’assassinat de 15 de ses patients, mais on soupçonne qu’il a fait un total de 215 victimes. Cette analyse vise à donner une vue détaillée des caractéristiques démographiques des victimes et du déroulement temporel des meurtres

## Context
Nous avons fait appel à deux jeux de données : shipman-confirmed-victims.csv et shipman-times-comparison.csv. Ces données englobent les décomptes de décès, à la fois confirmés et estimés, sur une période allant de 1975 à 1998. Elles ont été organisées en fonction de divers critères, tels que l’âge, le sexe, le moment et le lieu du décès des victimes.

# Power BI 

Power BI est une application gratuite que vous installez sur votre ordinateur local qui vous permet de vous connecter à, de transformer et de visualiser vos données. Avec Power BI, vous pouvez vous connecter à plusieurs sources de données différentes et les combiner (souvent appelé modélisation) en un modèle de données. Ce modèle de données vous permet de créer des visuels et des collections de visuels que vous pouvez partager sous forme de rapports avec d’autres personnes au sein de votre organisation.

## Tableau de bord Power BI

Un tableau de bord Power BI est une page unique, souvent appelée canevas, qui raconte une histoire à travers des visualisations. Parce qu’il est limité à une seule page, un tableau de bord bien conçu ne contient que les points forts de cette histoire. Les lecteurs peuvent consulter des rapports connexes pour obtenir plus de détails.

## Avantages de Power BI

- **Visualisations personnalisées** : Power BI offre une large gamme de visualisations personnalisées.
- **Intégration Excel** : Dans Power BI, vous avez également la possibilité de télécharger et de visualiser vos données dans Excel.

## Inconvénients de Power BI

- **Courbe d’apprentissage abrupte** : Power BI a une courbe d’apprentissage abrupte, en particulier pour les personnes qui ne sont pas familières avec les produits Microsoft ou les techniques d’analyse de données.
- **Personnalisation limitée** : Bien que Power BI offre une grande variété de possibilités de visualisation, certains utilisateurs peuvent découvrir que l’outil offre seulement quelques options de personnalisation.

## Principales fonctionnalités de Power BI

- Mise à jour mensuelle du produit.
- Extraction d’informations à partir de grands ensembles de données.
- Création de visualisations personnalisées avec R et Python.

## Sources de données Power BI

Power BI Desktop vous permet de vous connecter aux données de nombreuses sources différentes. Pour obtenir la liste complète des sources de données disponibles, consultez les sources de données Power BI6.

## Visualisations dans Power BI

Toutes ces visualisations peuvent être ajoutées à des rapports Power BI, spécifiées dans Q&A, et épinglées à des tableaux de bord. Les graphiques en aires, les graphiques à barres et les histogrammes, les cartes, les graphiques combinés sont quelques exemples de visualisations disponibles dans Power BI.

# analyse des données
D’après l’analyse des donnee, nous pouvons conclure que les crimes commis par le Dr. Mort présentent des tendances spécifiques. Les victimes étaient majoritairement des femmes âgés, avec une concentration particulière dans les groupes d’âge de 70 à 89 ans. Il y a eu une augmentation notable du nombre de décès autour de l’année 1995. De plus, la majorité des décès ont eu lieu à la maison personnelle des victimes. Ces informations auraient pu servir d’indicateurs précoces pour identifier les activités criminelles du Dr. Mort.

![alt text](<image/distribution des âges au moment du décès.png>)
On peut voir sur ce graphique que les cible de dr. Harold Shipman son principalement de âgée entre 70 et 89.

![alt text](<image/le nombre de décès par année.png>)
Ce graphique démontre le nombre de décès par année, on peut voir un pic de décès en 1997 avec plus de 36 morts. 

![alt text](<image/lieu de décès.png>)
On peut observer que la plupart des victimes sont décédées à leur domicile.