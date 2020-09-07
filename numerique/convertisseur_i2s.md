---
layout: default

title: Convertisseur numérique à I²S
---

## Le principe KISS (Keep it simple, stupid)

* Modularité

Afin de simplifier le
[convertisseur numérique-analogique]({{ site.baseurl }}/analogique/convertisseur_na.html)
(DAC), il peut être nécessaire à court terme d'avoir recours à un adaptateur pour les
différentes sources en format SPDIF et USB. Il devrait être possible de se procurer un
boîtier et des modules de notre choix à ajouter dans le convertisseur.

## Entrées (au choix)

* Module avec prise AES/EBU balancée (XLR)
* Module avec prise coaxiale
* Module avec prise Toslink (optique)
* Module avec prise HDMI régulière - possibilité d'ajouter une sortie HDMI pour le signal vidéo
* Module avec prise USB - possibilité d'y intégrer des fonctions de décodage ou de transcodage

## Fonctions

* Transformer tout encodage audio-numérique en format stéréo I²S
* Aligner les signaux numériques dans le temps avec une horloge de précision

## Sortie

* Prise [HDMI I²S avec spécification de PS Audio]({{ site.baseurl }}/pourquoi/i2s_iis.html)

## Design suggéré

{% include img_design.html ind=1 alt="Différents modules en entrée et une sortie numérique I²S" src="images/i2s_converter_back.png" %}
