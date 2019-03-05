# b1-reseau-tp6 

# Lab 2 : Un peu de complexité (et d'utilité ? ...)

## Mise en place du lab

### Checklist IP Routeurs
* Definitions des IPs statique.  
Pour R1 : <img src="router1.png">  
Pour R2 : <img src="router2.png">
Pour R3 : <img src="router3.png">
Pour R4 : <img src="router4.png">
Pour R5 : <img src="router5.png">  

* Définition du nom de domaine.  
Pour cela il suffit juste de faire un `conf t` puis un `hostname <nom du router>`.


### Checklist VMs  
La carte nat est deja enlevé normalement.  

* Définition des IPs statiques   
Pour client1 : <img src="client1.png">    
Pour client2 : <img src="client2.png">
Pour server1 : <img src="serv1.png"> 

* Définition du nom de domaine 
Pour changer le nom de domaine des VMs il suffit de faire `echo 'nom de la vm' | sudo tee /etc/hostname` puis on eteint et rallume les VMs.  

* Remplir les fichier `hosts`  
On va dans le fichier `hosts` en faisant `cd /etc/hosts` et on rajoute l'adresse ip des vm qu'on veut ping et on écrit le nom de la vm.