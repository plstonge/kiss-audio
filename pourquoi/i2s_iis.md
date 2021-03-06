---
layout: default

title: Pourquoi I²S ou IIS ?
---

## Le principe KISS (Keep it simple, stupid)

* Simplicité
* Éviter l'obsolescence

### Qu'est-ce que le I²S?

* C'est à la base l'état du signal audio-numérique avant d'être encodé en format S/PDIF
* On y retrouve le signal numérique des canaux de gauche et de droite, de même que des
  horloges de synchronisation
* Le format S/PDIF encapsule tous ces signaux dans un seul signal binaire
* Lors du décodage, le signal S/PDIF est décodé à nouveau en I²S

Autres sources d'information:
* Page [Wikipédia - I²S](https://fr.wikipedia.org/wiki/I2S)
* Vidéo [Youtube - What in the world is I2S?](https://www.youtube.com/watch?v=VrRV7hAKiIQ)
* Vidéo [Youtube - About I²S (à 5:19)](https://www.youtube.com/watch?v=a1a8l0-yDok&t=319)
* Test [Is I²S interface better for DACs than S/PDIF or USB?](https://www.audiosciencereview.com/forum/index.php?threads/study-is-i%C2%B2s-interface-better-for-dacs-than-s-pdif-or-usb.7105/)

### Y a-t-il une norme d'interconnexion?

[Malheureusement, pas encore](https://forum.psaudio.com/t/is-i2s-standard/15088),
mais une tendance semble converger vers la [spécification de PS Audio]({{ site.data.ref.i2shdmi }}) :
* Un câble HDMI passif, avec ses 19 fils, permet de transporter en parallèle tous
  les signaux numériques du I²S, et ce, de façon balancée
* Certaines interférences affectant le signal électrique pourront être annulées, ce qui
  augmente les chances de recevoir les signaux binaires tels qu'envoyés

### Est-ce répandu?

Voici plusieurs produits supportant la spécification PS Audio :

* PS Audio
  [Stellar Strata](https://www.psaudio.com/products/stellar-strata/),
  [Stellar Gain Cell](https://www.psaudio.com/products/stellar-gain-cell/),
  [PerfectWave SACD Transport](https://www.psaudio.com/products/perfectwave-sacd-transport/),
  [DirectStream DAC](https://www.psaudio.com/products/directstream-dac/)
* Audio-gd
  [R-1](http://www.audio-gd.com/R2R/R1/R1EN.htm),
  [R-8](http://www.audio-gd.com/R2R/R8/R8EN.htm),
  [R-7 version 2020](http://www.audio-gd.com/R2R/R720/R720EN.htm)
* Denafrips
  [Iris](https://www.denafrips.com/iris),
  [Gaia](https://www.denafrips.com/gaia),
  [Pontus](https://www.denafrips.com/pontus),
  [Venus](https://www.denafrips.com/venus),
  [Terminator](https://www.denafrips.com/terminator),
  [Terminator-*Plus*](https://www.denafrips.com/terminator-plus).
  Ces modèles sont compatibles avec différentes spécifications
* HoloAudio
  [Spring](https://www.stereophile.com/content/holoaudio-spring-kitsun%C3%A9-tuned-edition-level-3-da-processor)
* Matrix Audio
  [X-SABRE Pro (MQA)](https://www.matrix-digi.com/en/products/319.html)
* Topping
  [DX7 Pro](http://www.tpdz.net/productinfo/398244.html),
  [D70](http://www.tpdz.net/productinfo/398283.html),
  [D90](http://www.tpdz.net/productinfo/398270.html).
  Ces modèles sont compatibles avec différentes spécifications

Voici d'autres produits supportant une spécification différente :
* SMSL Audio
  [M400](https://www.smsl-audio.com/portal/product/detail/id/547.html)
* [RJ45 - AQlink] Aqua
  [LinQ](https://www.aquahifi.com/linq.html),
  [La Diva](https://www.aquahifi.com/la_divacd.html),
  [Formula](https://www.aquahifi.com/formula.html),
  [La Scala](https://www.aquahifi.com/la_scala.html),
  [La Voce](https://www.aquahifi.com/la_voce.html)

Bref, plusieurs nouveaux produits sur le marché ont déjà une entrée ou une sortie I²S,
que ce soit de la forme HDMI ou RJ-45.

## Pourquoi adopter l'interface I²S-HDMI comme technologie unique?

* Bien que la polyvalence de certains des produits listés ci-haut soit appréciable,
  il est ridicule d'avoir autant de normes d'interconnexions différentes :
  * difficulté supplémentaire de conception;
  * augmentation des coûts de production.
* Pour des produits à usage domestique, le meilleur choix semble être le I²S-HDMI :
  * pour la simplicité du transfert du signal audio-numérique;
  * pour la compatibilité avec tous les signaux PCM et DSD à haute définition,
    ce qui n'est pas nécessairement le cas des autres interfaces.

Pour les applications spéciales ou variées, un
[convertisseur I²S]({{ site.baseurl }}/numerique/convertisseur_i2s.html)
peut toujours être utilisé.

## Pourquoi ne pas adopter l'interface I²S-HDMI comme technologie unique?

* À court terme, il n'y a pas de norme unique
* L'interface I²S-HDMI ne semble pas bidirectionnelle comme le USB, ce qui ne permet
  pas une authentification entre appareils (pour les DRM et le MQA)
* Dans un DAC bien conçu, les prises S/PDIF peuvent mitiger tous les problèmes que
  l'on peut attribuer au S/PDIF :
  * transformation (inutile?) du signal
  * décalage temporel (jitter)
  * perte du signal si un bit est mal décodé

Le plus grand concurrent reste le USB, mais le décodage du signal numérique semble
encore plus élaboré que le S/PDIF. Dans tous les cas, une norme unique devrait être
privilégiée.
