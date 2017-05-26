Jardin connecté Arduino version mega !
===================

Bonjour, voici mon projet de jardin connecté d'appartement.


Contexte du projet
-------------
Je vis en appartement et je souhaitais faire un peu de jardin.
Impossible direz vous ? Et bien non :-) c'est tout à fait possible.
Deuxième objectif, étant un peu (beaucoup) Geek, je décide de connecter le jardin.
Je dispose d'une centrale domotique à base de raspberry pi et de l'application Domoticz. je souhaite connaitre l'état du jardin et potentiellement pouvoir l'arroser à distance que le jardin en a besoin.


Présentation 
------------

 - 1 x Arduino Mega
![Arduino Mega](https://cdn-reichelt.de/bilder/web/xxl_ws/B300/ARDUINO_MEGA_A03.png)
 - 1 x Arduino Ethernet Hanrun
![Module Ethernet](https://www.mysensors.org/uploads/57c1a7eaf40891c215911e3f/image/wiznet.png)
 - 1 x Module Afficheur LCD & boutons
 ![Afficheur avec boutons](https://arduino-info.wikispaces.com/file/view/LCD-Pushbuttons-1-600.jpg/230299482/LCD-Pushbuttons-1-600.jpg)
 - 4 x modules de test d'humidité du sol
![Capteur d'humidité](https://images-na.ssl-images-amazon.com/images/I/51YJV7u7mYL._SY355_.jpg)
 - 1 x Module TSL2561 capteur de luminosité
 ![Luxmètre](https://images-na.ssl-images-amazon.com/images/I/61-CGRW3OJL._SL1020_.jpg)
 - 1 x capteur de niveau d'eau à 5 niveau (6 fils)

Le besoin
-------------
Expression du besoin :

 - Mesurer l'humidité du sol sur plusieurs bacs
 - Mesurer le niveau d'eau dans la cuve (par pas de 20%)
 - Mesure de la luminosité du jardin.
 - Envoyer des notifications régulières à la centrale domotique
 
