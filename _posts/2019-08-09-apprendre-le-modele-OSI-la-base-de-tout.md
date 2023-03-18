---
title: Le modèle OSI la base de tout.
author: Antoine Meheut
date: 2019-08-09 20:55:00
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

Tous les systèmes qui véhiculent des informations disposent de mécanisme d'enregistrement de leur utilisation, c'est ce que l'on nomme les logs ou encore traces. Lorsque vous utilisez votre téléphone portable, celui-ci échange avec les antennes-relais qui servent à véhiculer vos appels et y laisse des traces. Idem avec votre ordinateur ou votre tablette sur Internet. Lorsque vous vous connectez à un serveur, celui-ci pourra enregistrer des informations sur votre connexion, que ce soit le serveur de votre FAI (Fournisseur d'Accès à Internet) ou bien le serveur d'un blog que vous êtes en train de lire.

Les logiciels sont partout dans nos vies aujourd'hui et donc les traces aussi. Même votre voiture, car à moins que vous ayez un modèle construit dans les années 20, l'ordinateur de bord enregistre des informations sur votre utilisation.

Imaginons que vous décidiez d'éteindre tous vos équipements informatiques et de les laisser chez vous lors de votre prochaine promenade. Vous laisserez quand même des traces de votre déplacement, avec votre carte électronique de transport en commun. Bon, OK, vous décidez de marcher, c'est chouette pour la santé et vos baskets ne vont quand même pas laisser trop de traces sur le bitume. Et bien pendant que vous regarderez vos chaussures, une caméra de surveillance placée sur un réverbère aura enregistré votre passage.

Pensez donc à cela, avant que nous passions à la pratique, dans les prochains articles, ne pas laisser de traces dans notre vie actuelle est une chose excessivement difficile à réaliser.

Dans les prochains articles, nous étudierons comment les hackers travaillent, vous partager les bases et la compréhension des théories et des outils et un très bon moyen de vous informer sur les risques d'attaque, ainsi que de vous apprendre à vous en protéger.

Les exercices pratiques seront donc réalisés dans ce que l'on appelle un réseau local (en gros chez vous et pas sur Internet), si vous attaquez votre propre site web ou des serveurs qui sont chez vous, personne en théorie ne vous en voudra. Si vous utilisez ces techniques pour sortir de votre réseau local et de vos serveurs, pensez bien au fait que vous allez laisser des traces et que les personnes qui pourraient vous en vouloir, pourront vous retrouver et demander aux autorités de vous retrouver.

Nous verrons donc aussi dans les prochains articles ce que sont les réseaux informatiques et comment ils sont organisés, pour vous apprendre à naviguer et à vous aider à identifier où vous êtes, avant de pratiquer quoi que ce soit.
