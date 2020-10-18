---
title: /game
layout: page
permalink: /game
---

>mkfs.ext4 /dev/sda4
>mount /dev/sda4 /mnt
>pacstrap /mnt base base-devel zsh efibootmgr
>genfstab -pU /mnt >> /mnt/etc/fstab
>chroot /mnt /bin/bash
>useradd -m -g users -G wheel,storage,power -s /bin/zsh NEW_PLAYER
> mkinitcpio -p cyberpunk
>exit
>umount -R /mnt
>lsblk

-- Description de la partie
Bonjour $NEW_PLAYER.
Ton intérêt pour une partie test du jeu Cyberpunk Red a été notée. Cette partie est construit sur le Jumpstart kit et est présentée comme une aventure one-shot contenant un maximum de {$nb_scenario}

Error nb_scenario has not been initialized. Please define nb_scenario:
>4

Cette partie est construit sur le Jumpstart kit et est présentée comme une aventure one-shot contenant un maximum de 4 scénarios courts. Les personnages pourront être changés entre les scénarios et les joueurs pourront être interchangés aussi. La création des personnages sera simplifiée et basée sur des templates.
Des ressources sont disponibles à l’adresse suivante :

>echo $player_ressources.location
https://1drv.ms/u/s!At74YwoeDnLKgesBf0cnUZFosWgGpw?e=KDB3sY 

Ces ressources sont distribuées à titre d’aide et leur distribution est interdite (j’ai le droit de les avoir parce que j’ai acheté le jeu).
Dans le dossier charCreation, vous trouverez les ressources nécessaires pour la conception de votre personnage. La création en soit se fera avec moi en vidéo conférence. Le fichier pregen.pdf contient les templates de personnages. Le dossier charExamples contient des personnages joués dans des streams promotionnels si vous avez besoin d’inspiration.
Le fichier reference.pdf contient un aide de jeu avec un résumé des règles et des tables.
Le fichier rulebook.pdf contient l’ensemble des règles décrite dans le Jumpstart kit. Les règles importantes pour les joueurs seront résumées avant la première partie et un peu plus bas.
Le fichier worldbook.pdf contient l’ensemble de la description de l’univers tel que décrit dans le Jumpstart kit. La section contenant la description des scénarios a été enlevée de ce document. Les parties du lore nécessaires au scénario seront mentionnées en cours de partie. La section Description de l’univers sert aussi principalement à vous mettre dans l’ambiance.
Les joueurs sont encouragés à consultés rulebook.pdf et worldbook.pdf avant la première partie mais ce n’est pas nécessaire.

Les joueurs intéressés sont invités à rejoindre le serveur Discord [lien].

