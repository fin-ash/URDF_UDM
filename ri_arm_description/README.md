# Projet : Création et Visualisation de l'URDF d'un Robot avec Déplacement des Joints

Ce projet consiste à créer un modèle URDF pour un robot existant, à l'intégrer dans MoveIt pour le contrôle de la trajectoire, et à créer des services pour la cinématique directe et indirecte du bras.

## Étape 1 : Mise en place de l'URDF

1. Créez un catkin workspace et un package pour le projet.
2. Dans le package, créez un dossier `urdf` pour stocker les fichiers URDF.
3. À l'intérieur du dossier `urdf`, créez un fichier `robot.urdf`.
4. Modifiez le fichier `robot.urdf` pour décrire le modèle du robot existant. Assurez-vous d'inclure les liens et les joints appropriés en fonction des spécifications du robot.
5. Enregistrez le fichier `robot.urdf`.

## Étape 2 : Visualisation sur RViz

1. Lancez un environnement ROS et exécutez `roscore`.
2. Ouvrez un terminal et lancez RViz en exécutant la commande `rosrun rviz rviz`.
3. Dans RViz, ajoutez un visualiseur pour le modèle URDF en utilisant le plugin `RobotModel`.
4. Spécifiez le fichier URDF `robot.urdf` pour charger le modèle du robot.
5. Vous devriez maintenant voir le modèle du robot dans RViz. Vous pouvez configurer les options d'affichage selon vos besoins.

## Étape 3 : Déplacement des Joints

1. Pour déplacer les joints du robot, vous pouvez utiliser les outils fournis par MoveIt.
2. Intégrez l'URDF du robot dans MoveIt en créant un package MoveIt spécifique.
3. Configurez les fichiers de configuration MoveIt pour correspondre au modèle URDF et aux spécifications du robot.
4. Utilisez les bibliothèques et les API fournies par MoveIt pour contrôler la trajectoire et déplacer les joints du robot.
5. Réalisez des tests et des démonstrations pour vous assurer que le déplacement des joints fonctionne correctement.
