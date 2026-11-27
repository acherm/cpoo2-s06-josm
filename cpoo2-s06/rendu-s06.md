---
title: "CPOO2, S06 : les patrons de JOSM"
author: "NOM Prénom, NOM Prénom"
lang: fr
---

<!-- Remplissez ce fichier, sans changer son plan. Tout ce qui est écrit
     À COMPLÉTER doit avoir disparu avant le rendu.

     Diagrammes (questions 1 à 4) : ils servent de support à votre explication
     du patron et de l'organisation du code. Une photo du dessin sur papier, ou une
     image faite avec un outil, dans diagrammes/ (q1.jpg, q1.png ou q1.svg).
     Changez l'extension dans la ligne ![Question 1](...) si besoin.
     Les diagrammes doivent apparaître dans le PDF : vérifiez-le avant de rendre.

     Pour obtenir le PDF, depuis ce dossier :
         pandoc rendu-s06.md -s --embed-resources -o rendu-s06.html
     puis ouvrez rendu-s06.html dans un navigateur et imprimez en PDF. -->

Code lu : JOSM r19700, dépôt `acherm/cpoo2-s06-josm`.

# Question 1 : placer le texte d'une surface

Code lu : `gui/mappaint/styleelement/placement`, `TextElement`, `StyledMapRenderer.drawText`.

## a. Diagramme de classes

![Question 1](diagrammes/q1.svg)

## b. Patron et rôles

Patron : À COMPLÉTER

| Rôle ou étape | Classe ou méthode |
|---|---|
| À COMPLÉTER | |
| | |
| | |
| | |

## c. Pour ajouter une quatrième façon de placer le texte

À COMPLÉTER

# Question 2 : les onglets des préférences

Code lu : `PreferenceSettingFactory`, `GridPreference` et sa `Factory`, `PreferenceTabbedPane.buildGui`.

## a. Diagramme de classes

![Question 2](diagrammes/q2.svg)

## b. Patron de création le plus proche et rôles

Patron : À COMPLÉTER

| Rôle | Classe ou méthode |
|---|---|
| À COMPLÉTER | |
| | |
| | |

## c. Pourquoi une liste de fabriques plutôt qu'une liste d'onglets

À COMPLÉTER

# Question 3 : prévenir quand les données changent

Code lu : `DataSetListener`, `DataSetListenerAdapter`, `DataSet.addDataSetListener`, constructeur d'`OsmDataLayer`.

## a. Diagramme de classes

![Question 3](diagrammes/q3.svg)

## b. Les deux patrons et leurs rôles

Patrons : À COMPLÉTER

| Rôle ou étape | Classe ou méthode |
|---|---|
| À COMPLÉTER | |
| | |
| | |
| | |

## c. L'annotation `@FunctionalInterface` : ce qu'elle garantit, qui en profite

À COMPLÉTER

# Question 4 : parler au serveur

Code lu : `io/OsmServerWriter`, `io/OsmApi` (`createPrimitive`, `sendRequest`).

## a. Diagramme de classes

![Question 4](diagrammes/q4.svg)

## b. Le rôle d'`OsmApi`

À COMPLÉTER : son rôle, et le patron si vous en reconnaissez un.

| Rôle ou étape | Classe ou méthode |
|---|---|
| À COMPLÉTER | |
| | |
| | |
| | |

## c. Ce qu'`OsmServerWriter` n'a pas besoin de savoir

À COMPLÉTER

# Question 5 : fabriquer une erreur de validation

Code lu : `Highways.testWrongRoundabout`, `TestError`.

## a. Dans le code actuel, l'ordre des appels de `Highways` à l'objet `TestError` terminé

| Étape | Classe ou méthode |
|---|---|
| À COMPLÉTER | |
| | |
| | |
| | |

## b. Le changement de 2016

- **Ce que le changement de 2016, toujours présent dans le code actuel, a apporté (avec un exemple du diff, avant et après) :** À COMPLÉTER
- **Le patron de création du cours qui se rapproche le plus du code actuel :** À COMPLÉTER
- **Ce qui l'en distingue :** À COMPLÉTER

# Question 6 : ouverture

## Notre usage de l'IDE

| Fonction de l'IDE | Exemple précis (classe ou méthode de départ, ce qu'on a trouvé) |
|---|---|
| À COMPLÉTER | |
| | |
| | |
| | |

## Et avec une IA ?

- **Ce qu'un assistant IA aurait pu nous apporter pour lire ce code :** À COMPLÉTER
- **Ce que nous aurions dû vérifier nous-mêmes avant de le croire :** À COMPLÉTER
