# ecercice3.md

# Exercice 3

1. cat /ect/passwd

2.chmod 744 myfile

3. la différence entre  une variable d'environement et une variable local est que la variable d'environement  est accecible par tout les processus enfantsqui sont définie avec export alors que la variable locale elle est eccecible uniquement dans le script ou la fonction où elle est définie sans export.


4.  la structure if en bash permet d'exécuter des commande ssi une conditions est vrai
   exemple:

#!/bin/bash

fichier="monfichier.txt"

if [ -e "$fichier" ]

then 

echo "le fichier existe"

else 

echo " le  fichiern'existe pas"

fi

5. echo 'Malgré le prix élevé de 100$, il a dit'
echo '"Bonjour !" au vendeur:'
echo '"Bonjour est-ce que ce clavier fonctionne bien ?"'
echo '"Evidemment ! On peut tout écrire avec, que ce soit des pipe | ou bien des backslash |\ !"'
echo '"Même des tildes ~ ?"'
echo '"Evidemment !"'

6. fg %1

7. 	Couche 2 :

	Switch : Gère les adresses MAC, relie les appareils sur un même réseau.
	Pont : Relie des segments de réseau.
	Couche 3 :

	Routeur : Gère les adresses IP, relie différents réseaux.
	Passerelle : Relie des réseaux de types différents.

8.	cd : cd

	cp : Copy-Item

mkdir : mkdir 

9. 	Payload : C’est les données utiles dans une trame Ethernet.
       CIDR remplace les classes IP pour mieux gérer les adresses et éviter le gaspillage.


