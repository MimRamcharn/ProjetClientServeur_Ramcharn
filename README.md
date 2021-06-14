# ProjetClientServeur_Ramcharn

# Projet Client - Serveur

## BUT du projet
Le but de ce projet est d'établir une connexion de client et serveur entre deux processus qui se trouve en locale.

## Fonctionalité du projet
Pour faire cette connexion :
 - Dans un premier terminal, il faut lancer le code coté serveur
 - Dans un autre terminal, il faut lancer le code coté client
 - Le serveur se patiente jusqu'à qu'une demande soit faite
 - L'utilisateur (chez le client), envoie une demande
 - Le serveur peut maintenant répondre à cette demande.

## Compiler les scripts

Afin de compiler ce projet, les lignes de codes suivant sont insérées dans le terminal. 

```sh
cd bin
cmake ..
make
```

## Comment exécuter les codes
Du coté du serveur, le programme est lancé en utilisant :
```sh
./server
```
Du coté du client, 
```sh
./client
```
Tout cela se fait dans le <bin>.
