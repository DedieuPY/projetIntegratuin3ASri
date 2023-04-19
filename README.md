# Projet Intégration Robotique

Afin de reproduire le lancement des fonctionnalités du robot, voici les commandes à utiliser :

# Lancement de la configuration MoveIt Setup Assistant
- roslaunch moveit_setup_assistant setup_assistant.launch 
- Sélectionner le dossier hc10_moveit_config

# Scripts python 
Les scripts se trouvent dans le répertoire hc10_moveit_config
Depuis le répertoire hc10_moveit_config :
- python3 demo_move_hc10.py
- python3 path_move_hc10.py

Le premier correspond à la série d'exécutions utilisant des positions pré-enregistrées, cartésiennes, joint-pose. Il ajoute également un parallélépipède ayant pour objectif de gêner le robot afin de tester l'évitement d'obstacle.

Le second contient une série de mouvement pré-programmés permettant de survoler le cube à modéliser

# Environnement de simulation : lancement de Gazebo et RViz
- roslaunch hc10_moveit_config demo_gazebo.launch 


