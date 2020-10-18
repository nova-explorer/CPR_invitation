---
title: /rules
layout: page
permalink: /rules
---
```
:: Retrieving packages...
cyberpunk_red-0.1.0.7-3-x86_64      40.6 MiB [--------------c o o o o o o o o o o o ] 30%
cyberpunk_red-0.1.0.7-3-x86_64      91.9 MiB [----------------------------c o o o o ] 70%
cyberpunk_red-0.1.0.7-3-x86_64     133.7 MiB [--------------------------------------] 100%
(1/1) checking keys in keyring               [--------------------------------------] 100% 
(1/1) checking package integrity             [--------------------------------------] 100% 
(1/1) loading package files                  [--------------------------------------] 100%
(1/1) upgrading cyberpunk_red                [--------------------------------------] 100%
:: Searching databases for updates...
>ssh-keygen -t rsa -b 4096
Generating public/private rsa key pair.
Enter file in which to save the key(~/.ssh/id_rsa) : RABIDS
Your identification has been saved in RABIDS.
The key fingerprint is 1C:01:8950911:978P:1R
>ssh -p 22 -L 1C:01:8950911:978P:1R.CPR@reframe.g1s NET.CPR.RABIDS -l $NEW_PLAYER
Last login : 30th May 2020 @ 13:01:46
Welcome to Cyberpunk Red $NEW_PLAYER!
>lspci -vv -d | grep ‘’rules’’
```
<br />
# Description des règles
Les grandes règles seront résumées ici. Rapide rappel que les règles sont une sorte d’entente entre les joueurs et le Game Master afin que tout le monde travaille sur la même base mais qu’ultimement les règles sont définies par moi et moi uniquement. Le but d’un jeu de rôle est essentiellement de s’amuser et de vivre une aventure qui est mise en scène par le Game Master.
<br />
Les tests de compétences se font contre un DV (Difficulty Value). Si le résultat du test est plus grand que le DV, l’action réussit. Le DV est déterminé soit par le test du personnage défendant si l’action est faite contre une personne, soit par une valeur prédéterminée si l’action est faite contre un objet inanimé. Les DV prédéterminés sont compris généralement entre 10 et 30, correspondant pour la difficulté à une action très facile (niveau enfant) à légendaire (une fois par génération). Des malus ou bonus situationnels peuvent s’ajouter aussi. *La suite est gérée par Roll20* Pour faire un jet, on roule un dé 10 et on y additionne le modificateur de compétence et de STAT. Si le dé tombe sur 10, c’est une réussite critique et un autre d10 est roulé et additionné au résultat. Si le dé tombe sur 1, c’est un échec critique et un autre d10 est roulé et soustrait au résultat.
<br />
Au début du round, un test d’initiative est fait pour déterminer l’ordre du round. Un round dure typiquement 3 secondes. L’entièreté de la partie ne se fera pas en round parce que c’est chiant est souvent juste utile dans les combats ou les situations de stress. Lors de votre tour dans un round, vous pourrez faire une action de mouvement et une action basique. Lors de votre action de mouvement, vous pourrez vous déplacer de MOVE*2 mètres. Cette distance peut être modifiée si vous êtes en voiture ou dans certaines conditions. Pour votre action basique vous pouvez :
<br />
-	Attaquer : Voir la section TNTD juste après
-	Attraper : Attraper et tenir une personne ou un objet. Le test est soit sur Brawling ou Athletics. Tout les personnages impliqués dans une saisie subissent un malus de -3. La personne saisie doit faire une action pour se libérer.
-	Étrangler : Si vous êtes un attaquant dans une saisie vous pouvez étrangler le défendant. Les dégâts sont la stat BODY, ignorent l’armure et ne baissent pas la SP de l’armure. Selon les circonstances les dégâts peuvent être modifiés.
-	Lancer : Vous pouvez lancer une personnage ou un objet que vous tenez. La distance ou les dégâts sont définis par la stat BODY.
-	Courir : Vous pouvez utiliser une action supplémentaire pour vous déplacer une 2e fois.
-	Utiliser une compétence : Certaines de vos compétences peuvent être utiliser en combat. Certaines actions peuvent durer plus qu’un round.
-	Utiliser un objet : Utiliser un objet que vous tenez ou dans votre inventaire.
-	Préparer une action : Vous pouvez retarder une action pour plus tard dans le tour.
-	Tout autre action que vous pouvez imaginer
<br />
Les combats sont gérés par les règles Thursday Night Throwdown (TNTD). Cette section fait référence à plusieurs tables Ez_Reference.pdf. Si vous attaquez à distance (fusil), votre Marksmanship est comparé au DV de l’adversaire. Si REF sont de 10, le défendant peut faire un test d’évasion. Sinon le DV est déterminé selon l’arme et la distance de tir. Vous pouvez viser la tête pour un malus de 6 et doubler les dommages qui passent à travers l’armure. Le armes automatiques peuvent tirer en rafale. Chaque points de votre test de tir de plus que le DV vous donne une balle de plus dans la rafale pour un maximum de 3. La table de DV est différente. Vous pouvez faire un tir de couverture afin de forcer vos ennemis à se couvrir s’ils ne réussissent pas un test de Concentration. Les dégâts que vous infligez à un ennemis sont soustrais à leur valeur de Stopping Power (SP). Pour chaque attaque qui perce votre armure (vous inflige des dégâts), le SP de cette pièce d’armure diminue de 1. Si vous êtes à portée de 3 mètres d’un ennemi, vous pouvez attaquer avec une arme de mêlée. Votre Attaque de Mêlée est comparée à l’Évasion de l’ennemi. Deux attaques peuvent aussi être fait dans le même tour. Les attaques de mêlées ignorent la moitié de l’armure. Vous pouvez aussi attaquer avec vos points et alors vous comparez Brawling à Évasion. Si la cible a une armure, vos attaques seront nullifiées (0). Vos dégâts sont déterminés selon votre BODY.
<br />
Votre nombre de points de vie est déterminé comme 5*BODY. Lorsque vous vous tombez à la moitié de votre vie, vous recevez un malus de -3 à tous vos tests. Si vous tombez sous 1PV, vous aurez un malus de -5, sauf pour les tests de sauvegarde de mort. À chaque début de tour où vous êtes mortellement blessés, vous devrez faire un test de sauvegarde de mort. Vous roulez un d10 et si le résultat est sous BODY, vous vivez et continuez votre tour. Chaque sauvegarde de mort subséquente aura un malus de 1. Un personnage mortellement blessé qui est soigné remonte ses PV à 1.
<br />
La réputation est un test spécial qui est lié à l’ampleur de vos actions et de votre légende. Avec une bonne réputation (lire street cred) une personnage, même s’il n’a pas un bon charisme peut influencer son entourage. Tous les personnages commencent à 1 de réputation, l’équivalent de : Les gens ayant fait de votre passé savent qui vous êtes. La réputation peut tomber dans les négatifs si votre personnage fait preuve de lâcheté
<br />
```
>exit
>sudo shutdown -h now
[sudo] password for $NEW_PLAYER :
>***********
Shutting down...
Goodbye NEW_PLAYER...
```
