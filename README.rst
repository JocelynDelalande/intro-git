Introduction à GIT
==================

Cours d'introduction à GIT :

- théorie
- usage de ligne de commande ``git``.

Ce cours a été adapté pour les besoins d'une formation continue *Développeur web* à l'`École Centrale de Nantes` par `Jocelyn Delalande`.

Il a initialement été écrit et enseigné par `Pierre-Antoine Champin`_ et
`Amélie Cordier`_ au département informatique de l'`IUT de Lyon 1`_.

.. _Pierre-Antoine Champin: http://champin.net/
.. _Amélie Cordier: http://acordier.net/
.. _IUT de Lyon 1: http://iut.univ-lyon1.fr/
.. _Jocelyn Delalande_: https://jocelyn.delalande.fr
.. _École Centrale de Nantes_: http://www.ec-nantes.fr

Contribuer
++++++++++

Toute contribution à ce cours est la bienvenue.

Pour installer localement les sources et générer les fichiers HTML,
vous avez besoin de Sphinx_ et Hieroglyph_.
Après avoir cloné ce dépôt,
vous devez exécuter une fois les commandes suivantes
afin de récupérer le thème utilisé ::

  git submodule init
  git submodule update

puis, pour générer les documents ::

  make publishable

.. _Sphinx: http://sphinx-doc.org/
.. _Hieroglyph: http://hieroglyph.io/
