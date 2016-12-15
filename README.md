# Procédure d'installation d'un Mac Managé

## Install MacOs

### Reinstall latest MacOs (optionnal)

## Configuration de la Souris

## Configuration du Finder

## Partition Disk

## Configuration TimeMachine

## FileVault

## AirWatch

Il faut tout d'abord vérifier auprès de votre support IT que vous faites partie du groupe ActiveDirectory 'CoreConnect'.

Télécharger l'agent sur : https://awagent.com

Installer AirWatch

## Installation des XCode Command Line Tools

	xcode-select --install
	
The Command Line Tools provide many useful programs.

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

## Base package

	brew cask install sublime-text
	
### configure user profil

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

## Install MS Office for Mac

## Install OneDrive

## Install Lync
