---
layout: default
---

# Administrer Garden  
## Les commandes de base  
Tout le contenu de base pour administrer le serveur est dans la commande `mcpanel`  
## Les fichiers  
Le serveur est lancé par le root dans le répertoire `/srv/minecraft/`    
Les scripts sont stockés dans `/srv/scripts/`  
## Installer un plugin
Il suffit de le télécharger dans `/srv/minecraft/plugins/`   
Vous pouvez l'héberger sur [transfer.sh](http://transfer.sh)    
Et le télécharger avec `wget url`  
Il est nécessaire de connaitre les commandes de base linux.  
Un redémarrage est nécessaire pour lancer un plugin  
## Commandes de base linux  
`mv fichier.tmp texte.tmp` => Renommer un fichier (fichier.tmp => texte.tmp)  
`mv fichier.tmp dossier/` => Déplacer fichier.tmp dans dossier  
`cd chemin` => Se déplacer  
## Les logs  
Les logs sont dans le dossier `/srv/minecraft/logs`  
## Mettre a jour le serveur
Vous pouvez mettre à jour le serveur avec `mcpanel`.  
Les derniers builds sont ici: [Jenkins Paper](https://papermc.io/ci/job/Paper-1.13/)  
Vérifiez régulièrement la version avec `/ver`  
## Taches automatiques
Les taches automatiques sont gérées avec crontab.  
Editer le crontab => `crontab -e`
