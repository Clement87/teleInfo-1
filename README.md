# arduino-TeleInfo
Librairie arduino permettant de lire la téléinfo d'un compteur ERDF français.

Testé sur un arduino mini pro 3.3v.

# Installation
Copier le dossier dans votre répertoire librairies d'Arduino, relancez Arduino, importez les exemples

# Schéma de cablage
![Schéma de cablage](https://raw.githubusercontent.com/jaysee/mySensors-TeleInfo/master/Cablage%20t%C3%A9l%C3%A9info.png)

NOTE: Le schéma indique de connecter la resistance sur le 5v, si votre adruino est en 3.3v, connectez sur le 3.3 (c'est à dire VCC)

# mySensors

Dans les exemples vous trouverez le code pour transmettre ces informations à une passerelle mySensors.

IMPORTANT: utilisez la version dev du github mysensors sinon vous aurez une erreur de compilation


# Crédits

Pour créer ce projet je me suis inspiré des projets et doc suivants :

* Version de Filoucaenais - https://forum.jeedom.fr/viewtopic.php?f=35&t=1737
* Librairie InterfaceCOmpteurERDF de mea-edomus - https://code.google.com/p/mea-edomus/source/detail?r=1ab529c296c460fa76b717d8f12fd0fedaacda4f
* Documentation officielle ERDF - http://www.magdiblog.fr/wp-content/uploads/2014/09/ERDF-NOI-CPT_02E.pdf
