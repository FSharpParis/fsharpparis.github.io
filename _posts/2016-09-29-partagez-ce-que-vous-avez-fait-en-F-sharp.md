---
layout: post
title: Partagez ce que vous avez fait en F#
date: '2016-09-29T00:00:00.000-00:00'
author: Pierre Irrmann
tags:
- Meetups
---

Lors de cette première soirée depuis les vacances d'été, nous avons inauguré un nouveau format, avec 4 présentations au cours de la soirée :

## Des dessins avec Pierre Irrmann [@pirrmann](https://www.twitter.com/pirrmann)

J'ai (ben oui c'est moi) fait une démo de dessin en F#, autour d'une experience dont le but est de pouvoir s'attacher à une session de F# Interactive d'afficher automatiquement une représentation graphique des valeurs évaluées dans la session. L'idée est ensuite d'utiliser ces visualisations dans le cadre de dojos / ateliers de code pour obtenir un rendu graphique.
Le code est disponible [sur GitHub](https://github.com/pirrmann/FSketch)

## Agents et acteurs avec Etienne Magreault [@emagreault](https://twitter.com/emagreault)

Etienne nous a fait une présentation du concept d'agent, avec quelque premiers exemples utilisant les MailboxProcessor inclus dans F#, puis du modèle acteur autour de Akka.Net. Il nous a ensuite montré un POC réalisé autour de ce modèle.

## 3 projets avec Julien Roncaglia [@virtualblackfox](https://twitter.com/virtualblackfox)

Julien nous a parlé de 3 de des projets effectués en F#.

Le premier consistait à choisir un prénom pour son enfant en cherchant des idées parmi les prénoms donnés à Paris, en utilisant les [données publiées en open data](http://opendata.paris.fr/explore/dataset/liste_des_prenoms_2004_a_2012/?disjunctive.prenoms&disjunctive.annee&sort=nombre) et en attribuant des notes aux prénoms, jusqu'à obtenir des suggestions personnalisées.

Le deuxième est une librairie permettant de générer automatiquement des classes C# d'identifiants fortement typés, en utilisant Roslyn. Le projet est dispo sur GitHub [https://github.com/vbfox/stidgen](https://github.com/vbfox/stidgen).

Le troisième est une expérience autour du module `Printf` et du type `Format`, qui permet de founir des implémentions générant un autre type qu'une string en sortie d'une expression de type printf, comme par exemple une SqlCommand ou une url formattée. Attention c'est expérimental ! Dispo également à l'adresse [https://github.com/vbfox/MasterOfFoo](https://github.com/vbfox/MasterOfFoo)

## Suave, Swagger et Android avec Romain Flechner [@rflechner](https://twitter.com/rflechner)

Romain nous a montré comment il occupe ses loisirs à fabriquer toutes sortes d'applications mobiles :)

Ses projets utilisent Suave pour développer des services REST, avec Swagger pour générer la documentation des services. Dans le cadre de ses essais, il a développé un TypeProvider pour obtenir des routes typées dans Suave, et des computation expressions qui permettent d'introduire dans le code les éléments nécessaires à la documentation des API avec Swagger.

Enfin, il nous a montré une appli sont déployée sur deux téléphones, qui se sont envoyés des SMS.

Sa présentation en FsReveal est disponible sur [https://rflechner.github.io/SuavePresentation/](https://rflechner.github.io/SuavePresentation/), les projets présentés sont tous sur Github / Github pages:

- [https://rflechner.github.io/Suave.RouteTypeProvider/](https://rflechner.github.io/Suave.RouteTypeProvider/)
- [https://rflechner.github.io/Suave.Swagger/](https://rflechner.github.io/Suave.Swagger/)
- [https://github.com/rflechner/SmsServer](https://github.com/rflechner/SmsServer)

## Le(s) mot(s) de la fin

Merci à tous les intervenants et à tous les participants !

[Voir l'événement sur meetup](http://www.meetup.com/fr-FR/Functional-Programming-in-F/events/233992293/)
