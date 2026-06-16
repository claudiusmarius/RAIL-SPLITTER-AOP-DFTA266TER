# RAIL-SPLITTER-AOP-DFTA266TER
Alimentation symétrique

Générateur BF DIY - Partie Alimentation Symétrique ±12V
Présentation

Cette étape du projet est consacrée à la réalisation de l'alimentation analogique du générateur BF.

L'objectif est de produire une alimentation symétrique ±12V à partir d'une alimentation unique 24V DC afin d'alimenter les différents étages analogiques du générateur.

La solution retenue repose sur la création d'une masse virtuelle active à l'aide d'un amplificateur opérationnel LT1006 associé à un étage push-pull complémentaire BD139 / BD140.

Principe de fonctionnement

Une alimentation à découpage Hi-Link HLK-40M24 fournit une tension continue de 24V.

Un pont diviseur réglable génère une tension de référence égale à la moitié de cette tension.

Cette référence est appliquée à un amplificateur opérationnel monté en suiveur.

La sortie de l'amplificateur pilote un étage push-pull composé de :

BD139 (NPN)
BD140 (PNP)

La contre-réaction est prélevée directement sur le point commun des résistances d'émetteur, qui constitue également la masse virtuelle du système.

Cette architecture permet :

une bonne stabilité du point milieu ;
une faible impédance de sortie ;
un courant disponible nettement supérieur à celui que pourrait fournir l'amplificateur opérationnel seul.
Caractéristiques
Alimentation d'entrée
24V DC
Module Hi-Link HLK-40M24
Masse virtuelle
LT1006
Réglage du point milieu à 12V
Buffer de puissance
BD139
BD140
Résistances
Résistances de base : 50 Ω
Résistances d'émetteur : 0,5 Ω
Tension obtenue
+12V
0V (masse virtuelle)
-12V
Démonstration

La vidéo associée présente :

l'analyse complète du schéma ;
les choix de conception ;
le rôle des différents composants ;
la réalisation sur breadboard ;
les premiers essais pratiques du système.
Suite du projet

Les prochaines étapes porteront notamment sur :

validation sous charges équilibrées ;
validation sous charges déséquilibrées ;
caractérisation du comportement dynamique ;
intégration dans le générateur BF complet ;
finalisation du PCB.
Vidéo associée

DFTA266TER  - Générateur BF DIY - RAIL SPLITTER AOP : https://youtu.be/D2XhKlnVvlU


Comme toujours :

Et à bientôt pour de nouvelles vidéos !
