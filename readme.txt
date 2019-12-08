TP Scala MowItNow réalisé par le binôme : 
Chahba BENRBIA
Adélaïde BONHOURE


Tout d’abord nous avons créé la classe « LectureFichier.scala » qui va lire le fichier « Input_Test.txt ». 
Dans cette classe, nous avons isolé les coordonnées de la pelouse, les coordonnées initiales de chaque tondeuse et les commandes à appliquer sur chaque tondeuse. 

Puis, nous avons créé la classe « Tondeuses.scala » qui hérite de la classe « LectureFichier.scala », et qui contient les méthodes permettant de faire avancer ou tourner les tondeuses. 

Enfin, le test du mouvement des tondeuses est réalisé dans l’objet "Test_tondeuse.scala ». Pour chaque tondeuse, il applique les méthodes définies dans la classe « Tondeuses.scala », en fonction des commandes lues dans la classe « LectureFichier.scala ». 

