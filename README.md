# Bienvenue, sur La page Des tutos , Infos pratiques et plein d'autres .... 

### Ce n'est pas parce que vous ne savez pas vous servire d'un marteau qu'il faut planter des clous au tournevis !!!

					############################
					#       Dr.redfish         #
					#       Developper	   #
					#       -----------        #
					#       Verison : 0.1.0    #
					############################





----


# 1.Connaitre son materiel 

----
## Identifier sa carte graphique
*Pour connaître les caractéristiques de la ou des cartes graphiques, vous pouvez utiliser depuis un terminal les commandes suivantes, à copier-coller :*

>	lspci -vnn | grep -A 12 '\''[030[02]\]' | grep -Ei "vga|3d|display|kernel"

>	sudo lshw -enable pci -class display

>	xrandr 

----

## Connaitre les informations sur le processeur , la mémoire

>	cat /proc/cpuinfo

----

## Connaitre la distribution   

>	lsb_release  -a

----

# 2.Savoir ce qu'il ce passe sur le reseau
>
## netstat est un tres bon outils de monitoring

	 * netstat -l

*pour lister les port*
	
	* netstat -lntu
* TODO *		 


----


## La page sera alimenter au fur et a mesure si vous souhaiter participer merci d'envoyer un mail a l'adresse suivant:

[redfishaw@gmail.com](redfishaw@gmail.com)
