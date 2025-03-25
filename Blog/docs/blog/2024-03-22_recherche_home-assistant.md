---
title: "Home Assistant : recherches de solutions domotiques"
date: 2025-03-25 10:17:00
authors:
  - Killian Kopp
summary: "Recherche de solutions domotiques pour supprimer la passerelle IKEA"
categories:
  - domotique
tags:
  - Zigbee
  - Home Assistant
  - Raspberry Pi
publish: true
slug: "home-assistant-recherches-solutions-domotiques"
---

Le protocole Zigbee est un protocole de communication sans fil basse consommation et à faible puissance. 
Il est utilisé pour la communication entre les appareils domotiques. Il est basé sur la norme IEEE 802.15.4.  
J'utilise actuellement des produits Zigbee de la marque IKEA.

![Ampoule GU10](https://www.ikea.com/fr/fr/images/products/tradfri-ampoule-led-gu10-345-lumen-sans-fil-a-variateur-dintensite-spectre-couleur-et-blanc__1211136_pe909984_s5.jpg?f=xxxs)  
[Ampoule GU10](https://www.ikea.com/fr/fr/p/tradfri-ampoule-led-gu10-345-lumen-sans-fil-a-variateur-dintensite-spectre-couleur-et-blanc-70547474/)

![Interrupteur](https://www.ikea.com/fr/fr/images/products/styrbar-telecommande-connecte-blanc__0956695_pe804773_s5.jpg?f=xxxs)  
[Interrupteur IKEA](https://www.ikea.com/fr/fr/p/styrbar-telecommande-connecte-blanc-30488363/)

![Détecteur de porte](https://www.ikea.com/fr/fr/images/products/parasoll-capteur-fenetre-porte-connecte-blanc__1209776_pe909547_s5.jpg?f=xxxs)  
[Détecteur de porte IKEA](https://www.ikea.com/fr/fr/p/parasoll-capteur-fenetre-porte-connecte-blanc-80504308/)  

Pour ne citer que quelques exemples!  

Je trouve les produits très bons et ils sont vraiment pas chers. Ils utilisent le protocole Zigbee pour communiquer entre eux.  
Je voudrais maintenant me débarrasser de la passerelle IKEA et utiliser un autre moyen pour contrôler mes appareils et créer une API pour les contrôler.  
Je vais utiliser un Raspberry Pi pour cela et un dongle Zigbee.  

## Projet

Je vais utiliser Home Assistant pour contrôler mes appareils. [Home Assistant](https://www.home-assistant.io/).  
J'ai trouvé un site de vente de produits domotiques qui propose des produits Zigbee : [Domadoo](https://www.domadoo.fr/fr/).  
J'ai déjà un raspberry pi qui traine, je vais installer Home Assistant dessus.  

Liste des courses :  
- [Dongle Zigbee](https://www.domadoo.fr/fr/noel/7188-nabu-casa-dongle-usb-zigbee-30-connect-zbt-1-pour-home-assistant-0860011789710.html)