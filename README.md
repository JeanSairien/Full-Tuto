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

**TODO**		 


----

# 3.Apprendre le language PYTHON version 3
>
## Le python est un language serveur tres puissant et multi usage
### voici quelques liens:

[La doc officiel](https://docs.python.org/fr/3.5/tutorial/appetite.html)
**La documentation officiel et plutot bien faite**

[apprendre python](http://apprendre-python.com/)
**Plutot claire et en francais**

[tutoriel interactif en ligne](https://www.learnpython.org/)
**Bien qu'en anglais cette plateforme est tres bien faite et interactive**

[tuto.com(video)](https://fr.tuto.com/python/gratuit-python-les-bases-pour-debutant-python,46272.html)
**tuto de base avec une video**


# Vendors. Retrouvez sur ce depots des liens pour divers ressources et domaines
>	
[link-utils sur github](https://github.com/JeanSairien/link-utils)
	
**Ce dépot est mise a jours de temps en temps n'hesitez pas a aller y faire un tours régulierement et a me soumettre par email vos liens, merci**


## La page sera alimenter au fur et a mesure si vous souhaiter participer merci d'envoyer un mail a l'adresse suivant:
[redfishaw@gmail.com](redfishaw@gmail.com)
