---
title: Le modèle OSI la base de tout.
author: Antoine Meheut
date: 2019-08-09 20:55:00 +0800
categories: [Cybersécurité, OSI, Apprendre]
tags: [Apprendre]
pin: true
---

# Le modèle OSI
Le modèle OSI (de l'anglais Open Systems Interconnection) est une norme de communication, de tous les systèmes informatiques. C'est un modèle de communications entre ordinateurs proposé par l'ISO (Organisation internationale de normalisation) qui décrit les fonctionnalités nécessaires à la communication et l'organisation de ces fonctions.

# A quoi peut-il servir ?
Ce modèle pourra vous être très utile pour comprendre comment l'informatique fonctionne globalement au niveau des différentes couches qui sont présentées dans le modèle. Cela vous permettra aussi de choisir les couches ou vous préférez étudier et travailler. Car bien souvent, une personne qui souhaite attaquer ou défendre va se spécialiser sur une couche de modèle OSI. Il est donc normal de trouver à la vente par des acteurs malveillants d'informations sur une couche du modèle, ce qui permet à d'autres acteurs malveillants d'œuvrer à partir de ces informations sur les couches supérieures du modèle.

# A quoi cela ressemble ?
![OSI_Model_v1](/images/OSI_Model_v1.png)

* Couches logiciel :
  * 7 Application : Point d'accès aux services réseau
  * 6 Présentation : Gère le chiffrement et le déchiffrement des données, convertit les données machine en données exploitables par n'importe quelle autre machine
  * 5 Session : Communication Interhost, gère les sessions entre les différentes applications
  * 4 Transport : Connexion de bout en bout, connectabilité et contrôle de flux ; notion de port (TCP et UDP)
* Couches matérielles :
  * 3 Réseau : Détermine le parcours des données et l'adressage logique (adresse IP)
  * 2 Liaison : Adressage physique (adresse MAC)
  * 1 Physique : Transmission des signaux sous forme numérique ou analogique

# Première notions de logs (traces)
TODO
