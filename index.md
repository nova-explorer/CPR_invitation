---
title: /
layout: home
permalink: /
---

# Index
<br />
```
>mkfs.ext4 /dev/sda4
>mount /dev/sda4 /mnt
>pacstrap /mnt base base-devel zsh efibootmgr
>genfstab -pU /mnt >> /mnt/etc/fstab
>chroot /mnt /bin/bash
>useradd -m -g users -G wheel,storage,power -s /bin/zsh NEW_PLAYER
```
<br />
-- Description de la partie
Bonjour **$NEW_PLAYER**.
Ceci constitut ton invitation à une partie du jeu de rôle Cyberpunk Red. Cette partie sera présentée comme une aventure one-shot contenant un maximum de **{$nb_scenario}**
<br />
```
Error nb_scenario has not been initialized. Please define nb_scenario:
>4
```
<br />
Cette partie sera présentée comme une aventure one-shot contenant un maximum de 4 scénarios courts de 3 à 5 joueurs. Les personnages pourront être changés entre les scénarios et les joueurs pourront être interchangés aussi. L'univers est un futur dystopique où règnent les méga corporations et le crime.
<br />
## Si cette proposition vous intéresse vous devez:
- Contacter le GM(moi lol) pour qu'il vous ajoute au Discord.
- Contacter le GM pour fixer un rendez-vous pour la création de votre personnage.
- Idéalement lire les sections /game, /world et /rules dans le haut du site
- Avant la création de votre personnage, lire soit la section /char ou les templates de personages (seront disponibles sur le Discord)
- Si vous avez du temps, le rulebook et le worldbook seront aussi disponibles sur le Discord
