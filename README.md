# script-status
Introduction :

Ce script permet de connaitre le satus d'un ou plusieurs services installés sur un serveur.

Conditions de tests :

Ce script a été établi dans le cadre d'un projet qui consistait à automatiser une tâche d'administration. Il a été donc été mis en place un serveur sur lequel plusieurs services ont été installé et ou nous avons créé le script permettant donc de connaitre le satus des service.
Il nous permet de connaitre le status de tous les service installés sur notre machine serveur et de remédier au problème si les services sont down.
Ce script lancé au démarrage nous permet de connaitre aussi les services qui ne sont pas  démarrés et qui sont down.


Prérequis :

Un serveur ubuntu 20.04 
Installation d'un service dhcp sur un serveur existant
Installation d'un service dns sur un serveur existant
Installation d'un service squid sur un serveur existant
Installation d'un service ntp sur un serveur existant


Resultat : 
Une fois nos services (dhcp, dns, ntp, squid) sont opérationnels sur le serveur avec pour status RUNNING.
Notre script nous permet de toujours connaitre le status et disponibilité des services avec la commande (systemectl status + le nom de service).
