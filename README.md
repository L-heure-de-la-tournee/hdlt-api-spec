# HDLT

L'**h**eure **d**e **l**a **t**ourné est un née au seins d'un groupe d'amis universitaire, qui a pour but de faire boire ! :beers:
Un certain nombre d'*article* prédéfini (ou ajouté au fil du temps) régissent quand une personne doit payer sa tourné : c'est dans le cadre d'*un changement de status*.

Le groupe originel avait, par exemple, défini un changement de status par : 
* un changement de relation (célibataire, en couple, cocu...)
* passer son permis
* se teindre les cheveux...

... et bien d'autre ! Toutes les raisons sont bonnes pour boire :beer:.

## But du projet

HDLT était initiallement écrit en PHP/MySQL... Sans framework (:wink:), tout à la main.

Dans l'optique de découvrir de nouvelles technologies, une idée a germé : pouvoir faire plusieurs frontend (React, Vuejs, Angular...) intercompatible.
Et puisqu'au cours de nos recherches, nous avons récouvert OpenAPI pour décrire et documenter le comportement de notre backend, pourquoi pas aussi en avoir plusieurs ?

C'est aussi un bon moyen d'apprendre à utiliser git et github comme un pro. Voici [un lien](https://www.codeheroes.fr/2020/06/29/git-comment-nommer-ses-branches-et-ses-commits/) vers une convention pour nommer ses commits.

Nous voilà donc partie, ce dépôt sera la première pierre de l'édifice !

## Concepts

* Participer ! Que vous soyez pro ou étudiant, le but est de partager les bonnes pratiques de différents framework backend/frontend pour apprendre tous ensemble :books:
* Les dépôts sont volontairement en français :fr:. C'est une décision discutable, qui pourra être reconsidérée
* Une technologie vous intéresse mais n'est pas présente ? Demandez à un membre de l'organisation d'ouvrir un nouveau dépôt.
     - Il est possible d'avoir plusieurs dépôt dans un même language mais utilisant des frameworks différents (Django/Flask, Angular/Vuejs...)


## Ce dépôt

Ce dépôt contient le fichier `hdlt-api.yaml`, qui décrit au format OpenAPI 3 le fonctionnement (en français :fr:) de l'API d'HDLT.
Le fichier étant peut digeste, on sortira très vite une documentation généré par Swagger UI, RapiDoc, autre...

C'est aussi un dépôt on l'on apprend, étant donnée qu'à l'heure ou j'écris ces lignes, je ne sais pas comment sa s'écrit.

## Conventions

Ce dépôt essaye d'être le plus propre possible, et nous vous incitons à en faire de même en utilisant le *workflow* [git-flow](https://www.atlassian.com/fr/git/tutorials/comparing-workflows/gitflow-workflow).
Il s'appuie sur les branches et est utilisé sur des gros projets. Ce n'est pas le cas ici, mais ça permet d'avoir les bonne pratiques.

Heureusement, il existe des extensions git pour gérer les branches à notre place (voir gitflow).

