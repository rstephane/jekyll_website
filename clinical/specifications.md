---
layout: page
title: Spécifications
bigimg: /img/entete/installation-prototype-V0.jpeg
tags: [specifications]
---

Dans le cas du Corona-virus, l’assistance doit répondre à une situation particulière permettant la ventilation de patients atteints de la forme la plus sévère de l'insuffisance respiratoire aigüe à savoir le syndrome de détresse respiratoire aigü (SDRA).

Ce syndrome a pour caractéristique une atteinte pulmonaire bilatérale dont la gravité est définie par la définition de Berlin. Elle se caractérise par une altération de la compliance pulmonaire le plus souvent en lien avec un oedème alvéolo-capillaire lié à une atteinte de la membrane mais aussi une réaction inflammatoire.

# RECOVID spécifications

Recovid se différencie ([par rapport aux autres équipements existants](https://docs.google.com/spreadsheets/d/e/2PACX-1vTYAfldxoIiO46VAWH1NlhrwFBn9mguqS2bh1spnLEu4AVVN1cj1vaEm6vOp5Z6UnaAbUwd8dslCXdM/pubhtml#)) par les éléments suivants :

- Circuit patient n’utilisant que des composants certifiés CE médical,
- Dossier réglementaire complet (ramené au contexte de développement),
- Bien adapté au traitement COVID et complet (ex : courbes temps réel sur un écran),
- Économique, robuste et simple à assembler avec des moyens industriels réduits,
- Pas de vocation commerciale : après la crise, les respirateurs sont retirés du service,

RECOVID est basé sur l’automatisation d’un respirateur à main (Ambubag), il n’utilise pour le circuit patient que des composants (tubes, valve PEP...) certifiés CE médical.

Tous ces composants sont disponibles dans les hôpitaux. Le dispositif est facile à dupliquer avec des moyens industriels limités.

## Médical

  * Ventilation mécanique controlée (le patient ne contrôle plus sa respiration, la machine génère la ventilation dans son entièreté), il s’agit d’un asservissement du flux d’air en inspiration et expiration en respectant des contraintes stricts (pression/volume d’air, fréquence de la respiration, pause respiratoire, pression expiratoire positive, seuil plateau)
   * Le volume courant d’air qui doit être insufflé est de 6 ml/kg de poids théorique déterminé par la taille et le sexe. (Le poids réel n'est en aucan cas à considérer)
   * La pression de crête à 50 cmH20 - 60 cmH20 (peut passer à 70 ou 80)

## Mécanique

   * Circuit d’air controlé : l’air en entrée du système est ambiant, par contre l’air en sortie doit être filtré au moyen d'un filtre antibactérien, antiviral de type HEPA.
   * une PEP (pression d’expiration positive) doit être réglable entre 5 et 15 cmH2O), il s’agit de maintenir une faible pression dans les voies aériennes lors de l'expiration favorisant les échanges gazeux.
   * une fréquence respiratoire doit être réglable entre 12 et 35 cycles/min
   * un rapport inspiration/expiration de 1:2
   * une pause inspiratoire et expiratoire sont nécessaires afin de permettre le suivi du patient et de s'assurer de l'efficacité, l'innocuité de la ventilation invasive.

## Interface Utilisateur

   * les paramètres que la praticien doit pouvoir régler :
      * le taux de FiO2
      * le volume courant (Vt)
      * La débit inspiratoire exprimé en L./min
      * le PEP (pression expiratoire positive), pression qui reste dans le système de 0 à 50 mbar
      * la fréquence respiratoire (FR/min)
      * déclencher une pause inspiratoire (durée définie par une pression continue du praticien), débit réduit à 0,
      * déclencher une pause expiratoire (durée définie par une pression continue pression continue du praticien)
      * visualisation des valeurs spécifiques à instant de la courbe

   * les paramètres que la praticien doit pouvoir visualiser en temps réel sous forme graphique :
      * le volume d'air 0 à 600 mL,
      * Le débit 0 à 60 L/min
      * La pression Paw -20 à 100 mbar

   * informations temps réelles :
      * Fio2 21-100%
      * VT 300-1000ml
      * FR 10-35 bpm
      * PEP 0-15cmH2O
      * Débit max 30-90L/min

   * les alarmes en fonction de la pression d'insufflation :
      * dépassement d'un seuil d'insufflation maximum (ex : le flux d'air est obstrué)
      * passage sous le seuil d'insufflation minimum (ex : le flux d'air est laissé à l'air libre, patient débranché)
   * alarme liée au niveau de batterie de l'appareil

Enfin, ...

## Réplicabilité
