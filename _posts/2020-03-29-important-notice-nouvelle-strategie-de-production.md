---
layout: post
title: Important notice / Changement de stratégie pour la production
image: /img//icons/bars.png
gh-repo: recovid/documentation
gh-badge: [star, fork, follow]
tags: [news]
---

> Important à lire

Le projet avance bien dans les différents domaines.

Au vu de l'actualité, de l’accélération futures des besoins en appareils respiratoires, l'organisation du projet a été modifié (en accord avec l'ensemble des membres) pour procéder par lot avec un responsable par domaine. Les pages WIKI et la landing page ont été modifié en conséquence. Une time line du projet pour les deux semaines prochaines a été aussi publié sur le site WIKI du projet.

# Dégradation du contexte actuel

> Manque de respirateurs sur la région Auvergne Rhônes-Alpes

Les différents acteurs de la santé projettent un besoin proche de 50000 respirateurs alors que les autorités sanitaires ont recensés 30000 équipements disponibles sur la France.

Le responsable des urgences du CHU de Grenoble, confirme cet état de fait; il doit faire face à l’afflux de malades de plus en plus nombreux, dans des états sévères qui requiert l'utilisation de respirateurs.  Au vu de l'augmentation de patients en état critiques, il manquera des ventilateurs/respirateurs d'ici 3 semaines (il faudra doubler le nombre de lit disponibles d'ici les prochains jours', passer d’environ 100 lits à 200 lits sous 10 jours pour le CHU de Grenoble).

L'Open source et l'Open Hardware permet de faciliter l'accès et la fabrication des composants utiles pour fabriquer des respirateurs.  En donnant les codes sources et les schémas aux fablabs et Maker de France, nous serions en capacité de refaire une centaine de pièces.

> Le besoin évolue

Cependant, au fil des discussions et avancées positives du projet (prototype V1 validé), l'équipe rencontre deux problèmes de taille; juridique et capacité de fabrication à grande échelle.

Tout d'abord, ce n'est pas - à terme - 100 équipements qu'il faut fabriquer mais bien plus, une fabrication de lots de pièces par les différents Fablabs et Makers de France ne résoudront pas le problème d'approvisionnement, l'approche de la fabrication des ventilateurs doit changer (la production).

Deuxièmement, pour passer en tests clinique "réel", il faut passer des étapes procédures dictée par le conseil sanitaire qui valident le bon fonctionnement des respirateurs (ex: pas de risque de rupture de l'appareil, pas de défaut, pas de risque d'entrainer la mort, pas de mise en cause des soignants, etc.). Le niveau de qualité requit par les normes est 99,9% et une étude clinique est obligatoire (certification de l'équipement et ses composants).

> Des sociétés privée lancent des productions de ventilateurs

En parallèle, la société AIR LIQUIDE a annoncé avoir lancé la production de nouveaux ventilateurs (certifiés) qui seront livrés dans les prochaines semaines (il faut compter 6 à 8 semaines minimum) aux différents hôpitaux de la région.  

Au vu de l'explosion du nombre de patients en état grave sur la région, le responsable des urgences du CHU de Grenoble signale que d'ici une à deux semaines (fin mars), il manquera des respirateurs, il faudra alors procéder à des transferts de patients vers d'autres structures (cliniques, maison, etc.). **L'urgentiste nous alerte sur un manque immédiat de respirateurs ! Il projette qu'il va y avoir très rapidement un trou, un manque de ventilateurs sous 10 jours.**  Ce manque pourrait durer de 2 à 8 semaines. Par la suite, le CHU devrait recevoir les respirateurs fabriqués par Air Liquide.

> Il y aura une pénurie de respirateurs avec l'impossibilité de soigner tout les patients. **C'est pour cela qu'il faut continuer les efforts, AGIR DE SUITE et FORT.**

Le responsable des Urgences souhaite une production de 100 respirateurs (dans le cadre d’un essai clinique) à mettre à disposition du CHU progressivement dans les prochaines semaines.

# Evolution de la stratégie du projet

> Répondre au besoin du CHU de Grenoble dans un délai le plus court possible. Tout choix de matériel et de solution doit être guidé par cela.

A la lumière de ces éléments; le besoin de 100 unités en 3 semaines et le besoin d'un ventilateur "certifié", il faut que l'organisation du projet évolue avec la mise en oeuvre d'un partenariat avec un fabriquant d'équipements médicaux (la stratégie de réplication par les FabLabs ou des individus bénévoles n’est pas adapté à la situation actuel).

Deuxièmement, au vu du besoin de certification de l'équipement, il faut soumettre un dossier (réglementaire) aux autorités sanitaires ARS ou ANSM, qui inclut un protocole de recherche clinique visant à valider l’appareil.

Il est nécessaire que les tests cliniques soit portés par une personne morale identifié comme fabriquant de cet équipement médical.

Pour pouvoir aller jusqu’au bout, cad. jusqu’au patients, **la société MinMaxMédical (MMM) s'est proposé de prendre la responsabilité du fabriquant.**

Le fabriquant MMM porte un degré de responsabilité et doit fournir un ensemble de gages concernant la procédure de conception et de production pour que le dossier puisse être évalué positivement.

MMM a une grande expérience du domaine médical et sont adéquatement structurés pour répondre aux exigences réglementaires d’un essai clinique (Ces essais seraient coordonnés par le CIC-IT). C'est donc une très bonne nouvelle.

> Mixmaxmedical, en acceptant de contribuer activement au projet, permet de poursuivre un chemin qui n'est pas habituelle: on va allier un **design collaboratif et open source** avec une **production qui requiert étude clinique, standardisation de la fabrication**, selon les normes requiert par le meilleur de la santé, afin d'obtenir un produit certifié (méthodologies ARISK, QARA, 60601).

MMM va réutiliser le travail effectué lors de la mise en oeuvre du prototype V1 pour fabriquer la V2 (version industrielle).

# Evolution de la stratégie Open Source du projet ?
La stratégie de dissémination des livrables ne change pas.

MMM adhère au principe de partage et de diffusion que nous nous sommes fixés, et le projet reste open source / open hardware avec les mêmes licences.

> On reste sur notre ligne, notre fil conducteur; publier des livrables libres.

# Evolution de l'organisation du projet ?
En conséquence, nous devons revoir note organisation de travail.

En accord avec l'ensembles des membres du projet, nous avons définis des lots avec une personne responsable à la tête de chaque lot:

  * LIRE ABSOLUMENT la section [Organisation](https://github.com/Recovid/Documentation/wiki/02-Organisation).

Il est possible que dans certains lots nous allons avoir deux équipes travaillant sur des solutions alternatives du même problème dans le but d’avoir un plan B (voir de la redondance).

Le projet est en mode PORTAGE par MMM (on rappelle que MinMaxMedical prend la responsabilité du fabriquant, il faut donc que la société puisse garantir que la conception et la fabrication respectent les étapes permettant "la certification").

Les coordinateurs du projet sont: le CHU de Grenoble, MMM et INRIA.

# Coordination avec les autorités locales et nationales
Adrien est entré en contact avec le centre de crise sanitaire du ministère de la santé et la région pour impliquer autant que possible les autorités dans le déploiement et la coordination nationale des essais (CHU Brest - Nantes). Les contacts sont en cours en ce moment même, il reviendra vers nous très prochainement avec plus d’informations.

# Nouvelle feuille de route (29 Mars 2020)
![RECOVID TIME LINE](https://github.com/Recovid/Documentation/blob/master/images/RECOVID_Timeline_2903.png)

# Recadrage des actions en cours
(désolé pour l'utilisation du mot ''recadrage'')

## Conception / Fabrication

* Premier objectif: avoir sous 8 à 15 jours, 100 appareils (inscrit comme des prototypes, essai clinique, avec comme objectif la protection du fabriquant MMM, les soignants, et nous).

* MMM demande que la fabrication suive les normes (QARA, ARISK, 60601), il demande à intervenir sur la conception pour garantir une meilleure intégration pour la  fabrication ultérieure sur leur ligne de production.

## Approvisionnement
* Pour 100 équipements, il faut **commander les composants des lundi 30 mars.**

## Moteurs

* Commande de pièces au plus vite. Un premier prototype est quasi terminé (V1) et validera le concept pour continuer et aller vers une version productible (V2).

## Alimentation
* On prend une pièce sur le marché pour être plus proche des normes.

## Batterie

* Batterie électroportatif intermittente : pour déplacement patient.
* La batterie sera prise des systèmes venant du bricolage (magasin de bricolage). 10' d'autonomie.
* Sur l'équipement final, on va mettre un emplacement pour encastrer la batterie, cela simplifie la conception tout en garantissant un niveau de qualité élevé.

## Vannes PEP

* MMM va proposer des vannes (pour être proche des normes) mais leurs propositions sera discuter avec le reste du groupe.
* Ludovic continue de réfléchir à cette problématique.
* Contrôle PEP. Stan continue de réfléchir de son coté aussi.

Il ne faut pas s'arrêter.

## Sensor, capteur de pression
* Capteur identifié. on continue, on commande.

## Capteur FIO2

* Non obligatoire.
* Il peut être gérer de manière approximative : le personnel ouvre les vannes et taux oxygène dans le sang vérifié par un autre équipement. On peut donc faire autrement, mais c’est pas mal s’il y en a une :)

## Firmware

* MMM commence un développement en C++ (sans Arduino) pour être plus proche des normes requises par les autorités de certification.
* Le travail sur les cartes Arduino continue. On souhaite proposer un plan B, voir une redondance dans la solution final proposé (implémentation secondaire, indépendante, qui suit les mêmes consignes et en cas de défaillance de la carte électronique principale, la solution Arduino prendrait le relai, on augmente le taux de disponibilité de la solution et on réduit le risque d'arrêt).

## IHM

  * Travail terminé,
  * Test Users a planifier et faire.

## Carte et câbles de connexions

  * MMM se charge de cette partie.
  * Connexion/carte connexion : assemblage dans les locaux MMM.

## Risques

* L'analyse de risque est à revoir en conséquence.
* MMM est responsable de cette activité.

# Budget

* 1 équipement = 1000 euros environ,
* 100 équipements = 100ke environ.

INRIA évalue si l'institut peut payer une partie du budget requit.
Un appel à proposition est en cours d'écriture et sera soumis à la DGA (qui pourrait financer le projet). A suivre :)

# Glossaire

* ARISK: Analyse des risques.
* QARA : _Quality Assurance and Regulatory Affairs for Medical Devices (QARA)_.
* 60601 : Norme médicale en matière de sécurité de base et de performances essentielles des appareils électro médicaux.
* CIC-IT : [Centre d'investigation clinique](http://cic-it.fr/cic-it-grenoble.php)

# Fin
