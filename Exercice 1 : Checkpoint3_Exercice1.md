## Exercice 1 : Manipulations pratiques sur VM Windows 

### Partie 1 : Gestion des utilisateurs

**Q.1.1.1** Créer l'utilisateur **Lionel Lemarchand** avec les même attribut de société que **Kelly Rhameur**.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.1.1a.png?raw=true)
![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.1.1b.png?raw=true)

**Q.1.1.2** Créer une OU **DeactivatedUsers** et déplace le compte désactivé de **Kelly Rhameur** dedans.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.1.2.png?raw=true)


**Q.1.1.3** Modifier le groupe de l'OU dans laquelle était **Kelly Rhameur** en conséquence.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.1.3.png?raw=true)

**Q.1.1.4** Créer le dossier Individuel du nouvel utilisateur et archive celui de **Kelly Rhameur** en le suffixant par **-ARCHIVE**.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.1.4.png?raw=true)


### Partie 2 : Restriction utilisateurs

**Q.1.2.1** Faire en sorte que l'utilisateur **Gabriel Ghul** ne puisse se connecter que du lundi au vendredi, de 7h à 17h.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.2.1.png?raw=true)


**Q.1.2.2** De même, bloquer sa connexion au seul ordinateur **CLIENT01**.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.2.2.png?raw=true)

**Q.1.2.3** Mettre en place une stratégie de mot de passe pour durcir les comptes des utilisateurs de l'OU **LabUsers**.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.2.3a.png?raw=true)
![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.2.3b.png?raw=true)

### Partie 3 : Lecteurs réseaux

**Q.1.3.1** Créer une GPO **Drive-Mount** qui monte les lecteurs **E:** et **F:** sur les clients.

![img](https://github.com/shagoi/Checkpoint-3/blob/main/ressources/Q1.3.1.png?raw=true)
