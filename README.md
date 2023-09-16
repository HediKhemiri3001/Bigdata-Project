# Introduction

Dans ce projet on envisage développer un système Bigdata qui permet l'analyse du niveau de stress des populations de nombreux pays envers la pandémie Covid, pour ceci on utilisera deux types de traitements, le traitment en batch et le traitment en streaming suivant l'architecture lambda.
Ainsi le résultat final sera une vue représentant le niveau d'iquiétude des habitants de plusieurs pays à propos de la pandémie.

# Traitments

## Traitment en batch

Pour le traitment en batch on eu a un dataset disponible sur Kaggle, qui englobe des statistiques et des metriques concernant la pandémie.
Sur ce dataset, on effectura un traitement qui pourra extraire les données nécessaires de chaque pays concerné par notre étude.

[Lien du dataset.](https://www.kaggle.com/datasets/sunayanagawde/countrywise-covid-cases)

## Traitment en streaming

Pour le traitment en streaming, on utilisera L'api de Twitter, avec lequel on va écouter les tweets qui mentionne le pandémie, et ceci en spécifiant des tags avec lesquelles on peut restreindre le domaine de données, et ainsi on pourra estimer l'engagement des internautes et leur intéret à propos de la pandémie après 3 ans de son déclenchement.
Tags : ("covid", "vaccine", "pandemic", "pandémie","vaccin", "corona") etc...
Pour ensuite les diviser selon le pays de l'internaute ainsi on aura une vision claire sur ce qu'on veut obtenir.

# Architecture envisagée

![L'architecture du système](https://i.ibb.co/Tm86gsV/Architecture.jpg)
