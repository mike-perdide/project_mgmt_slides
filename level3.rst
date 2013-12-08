Level 3 : ingénieur dans une équipe R&D
=======================================

.. figure:: /_static/3up.png

Caractéristiques
================

.. rst-class:: build

- Projet : développer un logiciel d'administration d'un pare-feu
- Ressources : 6 développeurs, 1 responsable qualité
- Clients : direction commerciale, utilisateurs du produit (admin. sys)
- Contraintes de temps : négociées avec le service marketing et la direction commerciale

Etapes du projet
================

.. rst-class:: build

- Prototypage au tout début du projet
- Phase initiale de développement d'1 an (modèle en V)
- Commercialisation
- Retours réguliers client via le service commercial/support

.. note::

   * il y a du mieux : on a du développement itératif, on peut corriger le tir

Etapes du projet
================

.. rst-class:: build

- Développement par lots d'une durée de 3 à 6 mois (MAJ)
- Contenu des lots : négociation direction technique / direction commerciale
- Chiffrage des tâches : négociation direction technique / l'équipe R&D

Problèmes
=========

.. rst-class:: build

- Risque de retard sur chaque lot pour des raisons organisationnelles
- Similitude avec le modèle en V : on fait des promesses de date de livraison
- Retards à répétition : démoralisation de l'équipe, manque de confiance des autres services

.. note::

   * parce qu'il y a plusieurs niveaux de séparation entre les clients et les développeurs
   * chaque niveau veut satisfaire le précédent
   * résultat, chaque niveau va avoir tendance à sous-chiffrer
   * dev pense 6 mois, dit 4 mois, DT dit 2 mois, COM dit 1 mois
   * la gestion de projet doit aussi prendre en compte ce qu'il y a autour du projet

Fin du niveau
=============

.. figure:: _static/fin_niveau.png
   :class: fill

.. rst-class:: build

- Pot d'arrivée : **30 pt.XP**
- Proposition de nouvelles méthodes : **25 pt.XP**
- Le chef de projet se sent remis en question : **- 10 pt.XP**
- Vous quittez l'entreprise 6 mois avant la faillite et créez votre entreprise : **300 pt.XP**
- Total : **345 pt.XP**
- Nouvelles compétences débloquées : 3

Unlocked 1 : Réunion quotidienne debout
=======================================

.. rst-class:: build

- La réunion quotidienne : permet d'accentuer le sentiment d'équipe
- Debout : limiter le temps pris, fluidifier (chacun parle 2 minutes MAX)

Unlocked 2 : Kanban
===================

.. rst-class:: build

- Au lieu du bug tracker avec 6K+ bugs, la DT choisit un ensemble de tâches
- Focaliser sur une période courte
- Effet visuel : on progresse
- Affichage au mur vs affichage virtuel

.. note::

   * plutôt que de se mettre face à une montagne de bug, on présente des objectifs réalisables
   * effet sur le moral
   * chiffrer la célérité de l'équipe : en combien de temps les post-its progressent
   * facteur ludique

.. slide:: Exemple
   :level: 2

   .. figure:: _static/kanban_board.png
      :class: fill

Unlocked 3 : Test-driven developpement
======================================

.. rst-class:: build

- On écrit des tests de haut niveau au début du projet, ou de la période
- Tests correspondant aux scénarios d'utilisation
- Le projet est fini quand les tests passent
- Rendre le développement ludique : les voyants passent au vert quand on a fini

.. note::

   * dynamiser le développement, rendre le projet ludique
   * se focaliser sur les fonctionnalités demandées
   * quand ça marche, on arrête de développer
