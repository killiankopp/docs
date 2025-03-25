---
title: "Voiture RC autonome : premier pas"
date: 2025-03-25 10:56:00
authors:
  - Killian Kopp
summary: "Premier pas dans l'utilisation d'une voiture RC autonome."
categories:
  - robotique
tags:
  - Raspberry Pi
  - Arduino
publish: true
slug: "voiture-rc-autonome-premier-pas"
---

J'ai récemment acheté une voiture RC dans le but de la rendre autonome.  
Je vais partir d'un kit [Freenove](https://www.freenove.com/) pour cela et plus particulièrement le [FNK0089](https://store.freenove.com/products/fnk0089h?_pos=1&_sid=31c575e66&_ss=r)  

![Freenove FNK0089](https://store.freenove.com/cdn/shop/files/FNK0089L.MAIN.jpg?v=1704792844&width=1346)  

Le kit contient :  
- détection de ligne
- détection d'obstacle à ultrason
- afficheur led
- raspberry pi pico W
- moteur
- roues mecanum
- carte de contrôle

Il manque simplement les batteries (18650) et le chargeur mais cela fera l'objet d'autres recherches.  

Les documents se trouvent sur le site de Freenove : [Freenove FNK0089](https://freenove.com/FNK0089)

J'ai téléchargé le logiciel [Arduino IDE](https://www.arduino.cc/en/software) pour programmer le raspberry pi pico W.  
Puis j'ai suivi les instructions pour installer le support du raspberry pi pico W dans l'IDE.  

Je vais maintenant commencer à programmer le raspberry pi pico W pour qu'il puisse contrôler la voiture.  
Pour cela je vais utiliser l'IDE Arduino. Il faut que je commence par charger le firmware sur le raspberry pi pico W.  
Il faut pour cela appuyer sur le bouton BOOTSEL et brancher le raspberry pi pico W sur le port USB de l'ordinateur.  
[![Load firmware](https://img.youtube.com/vi/IZKpCz6LEdg/0.jpg)](https://www.youtube.com/watch?v=IZKpCz6LEdg)  

Après avoir changé le câble USB qui était certainement un câble de charge uniquement, j'ai pu charger le firmware sur le raspberry pi pico W.  
Je vais maintenant commencer à programmer le raspberry pi pico W pour qu'il puisse contrôler la voiture.  

J'ai commencé par le célèbre Blink pour tester que tout fonctionne bien.  

J'ai déroulé les sketches fournis par Freenove pour tester les différents composants.  
Je suis arrivé au 02.2 qui permet à la voiture d'avancer de manière autonome.  

Je m'arrête là pour aujourd'hui !  
Voici une petite vidéo de la voiture en action :  
[![Voiture RC autonome](https://img.youtube.com/vi/Cp-0RsHFpxo/sddefault.jpg)](https://youtube.com/shorts/Cp-0RsHFpxo)