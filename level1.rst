Level 1 : élève ingénieur 4A
============================

.. figure:: /_static/1up.png

Caractéristiques
================

.. rst-class:: build

- Projet : concevoir un automate de distribution de DVD pour agence de location
- Ressources : 1 élève ingénieur
- Client : professeur-e
- Contraintes de temps : fixée par le-la professeur-e

Etapes du projet
================

.. rst-class:: build

- Traduction de l'énoncé en spécifications techniques et architecture
- Specs -> Implémentation
- Vérification (phase de recette)
- Remise du projet, éventuellement présentation

  .. note::
     * donner des exemples par rapport au projet
     * concevoir un automate de distribution de DVD pour agence de location

Modèle : Waterfall
==================

.. figure:: /_static/Waterfall_model.png

   CC BY-SA https://en.wikipedia.org/wiki/File:Waterfall_model.svg

.. note::

   * reprendre le projet pour expliquer comment il s'y applique
   * pas tout à fait un vrai modèle, c'est un modèle intuitif
   * correspond au modèle "à l'arrache"
   * modèle employé quand on se sent pris par le temps

Modèle : V-Model
================

.. figure:: /_static/vee_model.png

.. note::

   * reprendre par rapport au projet de conception d'un automate
   * vrai modèle construit en opposition au modèle Waterfall
   * on conçoit les tests et le processus de validation quand on démarre le projet
   * on ne commence à implémenter que lorsqu'on a fixé toutes les phases du projet

Problèmes
=========

.. rst-class:: build

- Le retour client se fait au moment où on rend le projet
- Pas de possibilité d'intégrer les retours client

.. note::

   * si on a pas compris le problème, on se prend un mauvaise note
   * c'est définitif

Plus largement
==============

.. rst-class:: build

- Pas de garantie sur l'adéquation demande client/solution
- Le client ne sait pas toujours ce qu'il veut
- Le client peut changer d'avis pendant le projet
- Le client peut critiquer les choix d'implémentation
- On peut aussi se rendre compte en cours de projet que les choix d'implémentation étaient mauvais

.. note::

   * typiquement, pour un site web
   * le client voudra que le développeur s'occupe de changer l'implémentation

Fin du niveau
=============

.. figure:: _static/fin_niveau.png
   :class: fill

.. rst-class:: build

- Rendu du projet dans les temps : **10pt. XP**
- Briefing du binôme en 5 min. avant la présentation : **5pt. XP**
- Camouflage des bugs du programme pendant la présentation : **15pt. XP**
- Total : **30pt. XP**
- Nouvelles compétences débloquées : 3

Unlocked 1 : retours client
===========================

- Meilleures garanties de satisfaction
- Impliquer le client dans le projet

.. note::

   * permet de limiter les risques de conflits en fin de projet

Unlocked 2 : tests auto
=======================

.. rst-class:: build

- ::

        from mon_projet import recherche_min
        
        assert recherche_min([3, 4, 1, 8]) == 1
        assert recherche_min([1, 1, 1, 1]) == 1
        assert recherche_min([10, 100000]) == 10

- ::

        from mon_projet import sha1

        assert sha1("it's") == "79bbc535e98fe7e64ace715175a9b3d6e4167bf0"
        assert sha1("me") == "b1c1d8736f20db3fb6c1c66bb1455ed43909f0d8"
        assert sha1("mario") == "addb47291ee169f330801ce73520b96f2eaf20ea"

.. note::

   * important pour vérifier que tout fonctionne encore
   * utile quand on bosse à l'arrache, quand on est fatigué, quand on est peu attentif
   * dans l'idéal, on aborde toujours un projet reposé, l'esprit frais
   * dans la pratique, ça m'est arrivé de finir des projets à 5h du matin le jour avant

Unlocked 3 : Diagramme de Gantt
===============================

.. rst-class:: build

- Faire un planning suivant les différentes tâches
- Prendre en compte les dépendances entre les tâches

.. slide:: Exemple
   :level: 2
   
   .. figure:: _static/gantt_chart.png
      :class: fill
