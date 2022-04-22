# SAE-21, Construire un réseau informatique pour une petite structure
Durant la SAE-21, nous avons été chargés de mettre en place un réseau informatique pour une petite entreprise. 

Une tâche que nous seront certainement amenés à réaliser dans un futur proche.


## Le cahier des charges est le suivant :
- Prévoir un plan d'adressage pour toutes les machines de notre réseau

- La structure de l'entreprise comprend un service administratif, un service commercial et un service informatique

- Configurer un serveur web externe (dans une DMZ) contenant une page Web statique, accessible aux personnes, à l'intérieur et à l'extérieur du réseau

- Un serveur DNS (dans une DMZ) qui assure la résolution des noms symbolique

- Un serveur Web interne (Intranet)

- Un serveur DHCP, qui fournira des IP à toutes les machines du réseau

- Mise en place d'un peu de sécurité

- Les différents accès : 
    - les administratifs devront pouvoir accéder à internet et aux serveurs internes et externe

    - Les commerciaux devront pouvoir accéder aux serveurs internes et externes

    - Le SI doit pouvoir avoir accès à toutes les machines en SSH

    - Aucun message provenant de l’internet ne doit pouvoir arriver vers le LAN. Par contre, ils peuvent atteindre le serveur web externe

# Travail réaliser lors de la SAE
Lors de la SAE, j'ai pris en charge l'organisation et la répartition des tâches. Nous avons tous choisie ce que l'on souhaiter faire en fonction de nos compétences.

# Shéma du plan d'adressage
Nous avons réfléchis à un plan d'adressage, une fois ceci fait. J'ai donc pus réaliser le plan d'adressage à l'aide de Vscode et de l'extention intégrée drawio.

</br>
 
<img src="https://github.com/Abdessabourbaali/SAE21-Construire-un-reseau-informatique-pour-une-petite-structure-BAALI_RAZZAKI_CAPELLE/blob/main/SAE-21/Plan_Addressage.png" style="width: 800px">

</br>