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
Lors de la SAE, j'ai pris en charge l'organisation et la répartition des tâches. Nous avons tous choisi ce que l'on souhaitait faire en fonction de nos compétences.

# Schéma du plan d'adressage
Nous avons réfléchi à un plan d'adressage, une fois ceci fait. J'ai donc pu réaliser le plan d'adressage à l'aide de Vs code et de l'extension intégrée drawio.

</br>
 
<img src="https://github.com/Abdessabourbaali/SAE21-Construire-un-reseau-informatique-pour-une-petite-structure-BAALI_RAZZAKI_CAPELLE/blob/main/SAE-21/Plan_Addressage.png" style="width: 800px">

</br>

# Création de la page web
J'ai réalisé la page web HTML5 pour le serveur web (intranet).

# Mise en place du serveur Apache 2
J'ai réalisé la configuration du serveur Apache 2 en reprenant les base qu'on avait pu réaliser lors de la ressource R203.

# Rédaction du compte rendue de 
Au cours des séances, j'ai écrit ce que nous avons réalisés pour finalement écrire un compte rendu de groupe qui est disponible sur notre GitHub.

# Problème rencontré
Lors de la configuration du routeur pour la partie physique, notre routeur ne répondez plus et ne possédais pas d'adresse IP. Nous avons ainsi du passer par le logiciel WinBox pour le reconfigurer.

# Compétences traitées durant la SAE-21
Nous sommes essentiellement évalué sur la compétence administrer :

- Il choisit les solutions et technologies réseaux adaptées
Utilisation de GNS3; logiciel de simulation réseau.

- Il respecte les principes fondamentaux de la sécurité informatique
Respect de la sécurité avec des règles de filtrage sur le firewall, des ACL et la restriction des connexions sur le service SSH.

- Il utilise une approche rigoureuse pour la résolution des dysfonctionnements
Pour résoudre les problèmes rencontrés, nous avons utilisé les documentations, vidéos YouTube et WinBox pour la configuration de notre routeur MikroTik.

- Il respecte les règles métiers
Plan d'adressage professionnel à l'aide de drawio, tout en respectant les normes d'un schéma réseau.

- Il assure une veille technologique
Nous nous sommes renseignés sur les différentes solutions technologiques afin de réaliser la SAE-21. Par exemple pour le choix du serveur web, la sécurité avec les ACL.

- Il sait installer un poste client
On a installé des machines Linux sur GNS3, installation également d'un serveur web.