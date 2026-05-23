---
title: "AP SIO 1 : Découvrir et utiliser le JavaScript"
date: 2024-01-09T12:40:33+01:00
draft: false
author: "Prof Connecté / Alexandre MARTIN"
tags:
  - AP
image: /images/ap-clic/Unofficial_JavaScript_logo_2.svg.png
description: "AP : Découvrir et utiliser le JavaScript"
toc: true
mathjax: true
weight: 3
---

## I - Présentation du contexte

Vous travaillez pour une entreprise qui souhaite se lancer dans les petits jeux ludiques en ligne.
II. Mission 1 : Les besoins

On vous demande de coder en JavaScript un jeu dont le principe est simple :

- il faut cliquer sur une image.
- à chaque clic le score augmente de 1.
- pour arriver au niveau 1, il faut 15 clics, puis pour chaque niveau suivant on multiplie par 2 le nombre de clics nécessaires au niveau précédent (niveau 1 : 15 clics, niveau 2 : 30 clics, niveau 3 : 60 clics, niveau 4 : 120 clics, …).
- a chaque fois que l’on arrive au niveau supérieur, le nombre de clics actuel devient le nombre de clics auquel on retire le nombre de clics utilisés pour passer au niveau supérieur.
- On veut que les joueurs puissent se connecter avec leur nom / mot de passe grâce à un formulaire de connexion.
- Lorsqu’un joueur se connecte, le jeu s’initialise avec le nombre de clics et le niveau qui correspondent à son compte dans la base de données.

## II - Résultat à obtenir

<center>
<img src="/images/ap-clic/ap-clics.png">
</center>