# Unsecure / Open Source Project 

Unsecure is an Open Source Project, you can contribuate at any time.

While respecting the good practices of Github Flow.

For each features or contribution on the project : 

* Create a branch from the repository.
* Send a pull request from your branch with your proposed changes to kick off a discussion.
* Make changes on your branch as needed. Your pull request will update automatically.
* The pull request will be merged once the reviewers will be agry with the modifications.
* Tidy up your branches using the delete button in the pull request or on the branches page.

## Issue

[issue report](https://github.com/ESGI-IW/Unsecure/issues/new)

## Bug fix

[bug fix](https://github.com/ESGI-IW/Unsecure/issues/new?template=bugfix.md)

## Feature

[feature request](https://github.com/ESGI-IW/Unsecure/issues/new?template=feature.md)

## Installation Unsecure

* If on windows, install git bash for windows
* Generate ssh key : ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
* Generate a gpg key : gpg --gen-key
* Follow the procedure to add your ssh and gpg key on your github account
* Clone the project (using your ssh key) : git clone git@github.com:ESGI-IW/Unsecure.git
* Install Docker (docker toolbox if not on windows 10 pro)
* Start a docker quickstart terminal and use "docker-compose up" (docker-compose build if the images are not on the hub)
* to shutdown the process : docker-compose stop and to restart them use docker-compose start
* Then you can acces in the application with : [ESGI-IW](https://warm-citadel-11705.herokuapp.com/)