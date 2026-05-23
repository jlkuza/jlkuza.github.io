---
title: "AP SIO 2 : Supervision avec Zabbix"
date: 2024-01-09T13:35:33+01:00
draft: false
author: "Prof Connecté / Alexandre MARTIN"
tags:
  - AP
image: /images/ap-zabbix/zabbix.png
description: "Supervision des systemèmes avec Zabbix"
toc: true
mathjax: true
weight: 11
---

## I - Contexte
L’entreprise CUB possède de nombreuses machines virtuelles (les serveurs DNS dans les différentes zones, le serveur Web, le pare-feu) ainsi que des équipements réseaux (switchs CISCO). il est important pour la DSI d’avoir un tableau de bord permettant de voir en temps réel l’état des machines et des équipements réseaux.

## II - Les besoins
Il vous est demandé de mettre en place une solution de supervision du réseau (Switchs Cisco) et des machines virtuelles.

- La machine doit être intégré dans la bonne zone du lan de votre agence.
- La machine doit être accessible depuis son nom DNS : zabbix.lan.agence.cub.org
- Zabbix doit être installé en français.
- La machine doit utiliser le résolveur du lan comme serveur DNS.
- On doit avoir un tableau de bord qui permettent de voir l’état de tous les systèmes en temps réel.
- On doit recevoir les alertes sur Discord.

## III - Procédure

Voici le lien de ma procédure
