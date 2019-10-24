# Ansible-debian-fresh-install
Petit script Ansible permettant de configurer un serveur Debian rapidement &amp; simplement.


Celui-ci va donc installer des paquets de base (zip, htop, neofetch, iptables, sudo...) puis télécharger un script pare-feu Iptables, l'exécuter, et faire de même pour une jail SSH Fail2Ban. Enfin, il rajouter l'utilisateur "it-anthony" au groupe des sudoers.


![alt text](https://i.imgur.com/WLuNwZU.png)


Ce script est bien entendu à adapter à chaque configuration, et il a été réalisé dans le cadre d'un travail de fin d'étude. Plus d'infos sur mon site personnel directement : https://notamax.be/creation-dun-reseau-informatique-tfe-2019/
