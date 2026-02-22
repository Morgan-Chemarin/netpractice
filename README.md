( en italic ) This project has been created as part of the 42 curriculum by mchemari

# Description



# Instructions



# Ressource
TCP/IP adressing = deux protocoles importants, modele de reseaux utilisé dans la pratique

subnet mask = permet de differencié le reseau de l'hote

default gateway

adressing

routers = connecte plusieurs reseaux ensemble

switches = connecte des appareils d'un meme reseau local grace a l'adresse mac ( couche 2 TCP/IP )

OSI layers = modele de reseau plus academique


###
Host (Hôte : ton PC, un serveur) : C'est un utilisateur final du réseau. Il a des applications (navigateur web, jeu...) qui veulent communiquer. Il doit donc utiliser toutes les couches du modèle.

Ton navigateur web (Couche 7) crée une requête HTTP.
Le système d'exploitation l'encapsule dans une session TCP (Couche 4).
Puis dans un paquet IP (Couche 3) avec l'IP de destination.
Puis dans une trame Ethernet (Couche 2) avec l'adresse MAC du prochain saut (le routeur ou un autre hôte).
Et enfin, la carte réseau envoie les bits (Couche 1).