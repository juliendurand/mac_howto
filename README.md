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

## Install Python3

	brew install python3

## Install Postgresql

	brew install postgresql

## Install PostGIS

	brew install postgis

## Install VirtualBox

	brew cask install virtualbox

## Install Sublime

## Base package

	brew cask install sublime-text

### Package

### Anaconda

### git

### gitgutter

### terminal

### configure user profil

## Install MS Office for Mac

## Install OneDrive

## Install Lync
