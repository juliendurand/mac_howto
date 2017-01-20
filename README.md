# Procédure d'installation d'un Mac Managé


## Install MacOs

TODO

### Reinstall latest MacOs (optionnal)

## Configuration de la Souris

TODO

## Configuration du Finder

Pour voir toutes les extensions de fichier, ouvrer les préférences dans la barre de menu `Finder > Préférence` et sélectionner dans l'onget `Options Avancées` la case `Afficher toutes les extensions de fichier`.

![Préférences du Finder](img/finder/img1.png)

## Partition Disk

Lancer l'utilitaire de disque et créer une partition pour les sauvegardes Time Machine :

![Partition Disk 1](img/partition_disk/img1.png)

![Partition Disk 2](img/partition_disk/img2.png)

![Partition Disk 3](img/partition_disk/img3.png)

![Partition Disk 4](img/partition_disk/img4.png)

![Partition Disk 5](img/partition_disk/img5.png)

![Partition Disk 6](img/partition_disk/img6.png)

## Configuration TimeMachine

![Time Machine 1](img/time_machine/img1.png)

![Time Machine 2](img/time_machine/img2.png)

![Time Machine 3](img/time_machine/img3.png)

![Time Machine 4](img/time_machine/img4.png)

## FileVault

TODO

## AirWatch

Il faut tout d'abord vérifier auprès de votre support IT que vous faites partie du groupe ActiveDirectory 'CoreConnect'.

Télécharger l'agent sur : https://awagent.com

Installer AirWatch

![AirWatch 1](img/airwatch/img1.png)

![AirWatch 2](img/airwatch/img2.png)

![AirWatch 3](img/airwatch/img3.png)

![AirWatch 4](img/airwatch/img4.png)

![AirWatch 5](img/airwatch/img5.png)

![AirWatch 6](img/airwatch/img6.png)

![AirWatch 7](img/airwatch/img7.png)

## Enroller votre Mac

TODO

## Installation des XCode Command Line Tools

Les outils de ligne de commande XCode fournissent une longue liste d'outils utile pour le terminal, en particulier git et les compilateurs C, C++, Fortran, ...

	xcode-select --install

![XCode Command Line Tools 1](img/command_line_tools/img1.png)

![XCode Command Line Tools 2](img/command_line_tools/img2.png)

![XCode Command Line Tools 3](img/command_line_tools/img3.png)

![XCode Command Line Tools 4](img/command_line_tools/img4.png)

## Create SSH Keys

Taper la commande suivante dans un terminal en _**modifiant l'adresse email**_ :

	ssh-keygen -t rsa -b 4096 -C "your_email@example.com"

Ne pas mettre de "passphrase" et valider.

Lancer ensuite la commande :

	ssh-add ~/.ssh/id_rsa

## Installation de Brew

	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
	brew update

## Installation de Chrome

	brew cask install google-chrome

## Installation de R et RStudio

	brew install Caskroom/cask/rstudio

## Install Python3

	brew install python3

## Install Postgresql

	brew install postgresql
	brew services start postgresql

## Install PostGIS

	brew install postgis

## Install VirtualBox

	brew cask install virtualbox

## Install Sublime Text 3

### Base package

	brew cask install sublime-text

### Configuration du 'user profil'

Il est plus agréable de travailler avec une configuration spécialement conçue pour les développeurs. Pour cela aller dans le menu `Sublime Text > Preferences > Settings` et copier coller les paramètres suivants dans la partie droite de l'écran. Sauvegarder avec `cmd+S` et fermer la fenêtre.

```json
{
	"always_show_minimap_viewport": true,
	"bold_folder_labels": true,
	"ensure_newline_at_eof_on_save": true,
	"folder_exclude_patterns":
	[
		".svn",
		".git",
		".DS_Store",
		"__pycache__"
	],
	"highlight_line": true,
	"highlight_modified_tabs": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"rulers":
	[
		79
	],
	"shift_tab_unindent": true,
	"show_line_endings": true,
	"trim_trailing_white_space_on_save": true,
	"wrap_width": 80
}
```

### Package Control

Suivre les instructions pour la version 3 sur cette [page](https://packagecontrol.io/installation#st3) afin d'installer le gestionnaire de package de Sublime Text 3.

### SideBarEnhancements

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	SideBarEnhancements

### Anaconda

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	Anaconda

### git

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	git

### gitgutter

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	gitgutter

### terminal

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	terminal

### Markdown Preview

Dans sublime :

	cmd+shift+p
	Package Control : Install Package
	Markdown Preview

## Installation de MS Office for Mac

TODO

### Configurer la boîte de réception Outlook

TODO

## Installation de OneDrive

TODO

## Installation de Lync

TODO
