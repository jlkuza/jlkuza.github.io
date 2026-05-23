---
title: "AP SIO 2 : Sauvegarde avec Veeam"
date: 2024-01-11T14:08:33+01:00
draft: false
author: "Prof Connecté / Alexandre MARTIN"
tags:
  - AP
image: /images/ap-veeam/veeam.png
description: "AP - Mise en place d’une solution de sauvegarde sur le réseau avec des NAS et Veeam Backup & Replication"
toc: true
mathjax: true
weight: 13
---

## I - Contexte
L’entreprise CUB possède de nombreuses agences. Chacune dispose de serveurs et il est impératif de procéder à des sauvegardes régulière de ces serveurs.

Afin de ne pas tout perdre en cas d’attaque par Cryptolocker/Ransomware il est impératif de mettre en place une stratégie de sauvegarde immuable.

## II - Les besoins

L’entreprise CUB a donc besoin :

- Mettre en place un serveur de sauvegarde sous Windows server avec VEEAM Backup and Replication
- Installer le serveur de sauvegarde dans le bon VLAN de l’entreprise CUB et prévoir un disque d’au moins 80 GiO pour l’installation de Veeam.
- Sauvegarder le serveur Windows sur le NAS (172.17.50.211 ou 172.17.50.212 ou 172.17.50.213 ou 172.17.50.214 selon votre bâtiment) avec les identifiants admin/btssio.
- Sauvegarder 1 serveur Linux sur le NAS.

## III - Procédure

Voici le lien de ma procédure
