---
title: La sécurité applicative c'est quoi ?
author: Antoine Meheut
date: 2019-08-08 22:10:00 +0800
categories: [Sécurité applicative, Apprendre]
tags: [Apprendre]
render_with_liquid: false
---

La sécurité des systèmes d'information
La sécurité des systèmes d’information (SSI) ou plus simplement sécurité informatique, est l’ensemble des moyens techniques, organisationnels, juridiques et humains nécessaires à la mise en place de moyens visant à empêcher l'utilisation non autorisée, le mauvais usage, la modification ou le détournement du système d'information.

# La sécurité applicative
Définition ISO 27034 (Guide ISO sur la sécurité applicative) :
« La sécurité applicative est un processus effectué pour appliquer des contrôles et des mesures aux applications d’une organisation afin de gérer le risque de leur utilisation ».

« Les contrôles et les mesures peuvent être appliqués à l'application elle-même (ses processus, les composants, les logiciels et résultats), à ses données (données de configuration, les données de l'utilisateur, les données de l'organisation), et à toutes les technologies, les processus et acteurs impliqués dans le cycle de vie de l'application ».
 
# Pourquoi s'intéresser à la sécurité applicative ?
Aujourd’hui, les applications web sont les cibles privilégiées vis-à-vis des cyberattaques, car elles sont directement accessibles par les utilisateurs et parfois même directement depuis internet et qu’elles s’appuient sur de nombreuses dépendances logicielles/librairies qui augmentent la probabilité de faille.

Quelques malheureux exemples :
* Equifax (2017) : vulnérabilité struts non fixée -> fuite de données massive -> perte 700 M€,
* Log4j (2021) : faille de sévérité 10/10, encore exploitée aujourd’hui, car non « patchée » chez de nombreux utilisateurs,
* Librairie colors.js (2022) : sabotée par son développeur pour protester sur le manque de soutient aux développeurs open-source, par les utilisateurs de leur code, affichage de test en boucle,
* Librairie node-ipc (2022) : sabotée par son développeur pour protester contre l’invasion de l’Ukraine par la Russie, suppression des fichiers des ordinateurs des utilisateurs Russes (identification par adresse IP).

# Que peut-on faire contre cela ?
Beaucoup peut-être fait ! D'abord apprendre et comprendre comment cela peut exister. Comprendre le fonctionnement des réseaux, admettre qu'il y a du logiciel partout, dans notre vie aujourd'hui. Et qu'il peut être utilisé pour ce qu'il a été prévu, ou bien détourné pour un autre usage. Apprendre les bases des techniques utilisées par les personnes qui souhaite détourner un usage et apprendre ainsi à s'en protéger.

Et enfin vulgariser et partager ce savoir au plus grand nombre, car c'est l'ignorance, qui est la plus grande aide aux acteurs qui souhaitent détourner un système d'information.
