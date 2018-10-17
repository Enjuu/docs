---
title: "LoliBot Commandes"
old_id: 3
---
Ce sont les commandes supportées par LoliBot, notre chat bot.  

### Commandes générales
- `!roll` - Donne un nombre aléatoire de 0 à 100  
- `!roll num` - Donne un nombre aléatoire de 0 au nombre que vous avez mis 
- `!help` - Affiche le message d'aide
- `!pp [mode]` - Affiche vos PP actuels. Si `mode` n'est pas présent, LoliBot vous indiquera le montant de PP de votre mode de jeu actuel. Si le mode est présent (ça peut être `std/taiko/ctb/mania`), LoliBot vous indiquera le montant de PP pour ce mode de jeu. **Cette commande fonctionne seulement dans les MP**
- `!update` - Met à jour la beatmapset que vous avez /np dans notre téléchargement de map alternative.  Utilisez-la si vous venez de télécharger une beatmap depuis osu!direct et que celle-ci est obsolète ou si une beatmap ne peut pas être téléchargée depuis osu!direct car elle est trop récente.
- `!bloodcat` - Si osu!direct ne marche pas, vous pouvez utiliser cette commande pour obtenir la beatmap en multijoueur.

### Commandes FAQ
- `!faq rules`  
- `!faq swearing`  
- `!faq spam`  
- `!faq offend`  
- `!faq english`  
- `!faq github`  
- `!faq discord`  
- `!faq blog`  
- `!faq changelog`  
- `!faq status`  

### Commandes du bot Tillerino
Lolibot a des commandes similaires à Tillerino. Ces commandes ne fonctionnent que si vous les envoyez à LoliBot via un MP. Rappelez-vous que le système de PP a été implémenté uniquement sur osu!standard et en osu!mania. Le bot ne sipporte pas les recommandations de beatmaps pour le moment, cette fonctionnalité viendra plus tard, espérons-le.

- `/np` - Affiche les PP pour la musique en cours de lecture (seulement si s'est une beatmap en osu!standard)
- `!last` - Affiche les infos (et le nombre de PP gagné(s), si c'étais un score en osu!standard) concernant le dernier score soumis
- `!with <mods>` -  Affiche les PP pour la beatmap précédente demandée avec les mods écrits. Les mods supporter sont `NF, EZ, HD, HR, DT, HT, NC, FL, SO.`. N'utilisez pas d'espaces pour plusieurs mods (ex: `!with HDHR`)

### Commandes d’administrateurs
- `!system restart` - Redémarre le serveur. Tout le monde sera déconnecté et reconnecté automatiquement  
- `!system status` - Affiche le statut du serveur  
- `!system reload` - Recharge les paramètre de Bancho (ceux qui sont modifiables depuis EAP)  
- `!system maintenance on/off` - Active/désactive le mode de maintenance de Bancho
- `!moderated on/off` - Active/désactive le mode de modération du canal actuel 
- `!silence <username> <count> <unit (s/m/h/d)> <reason>` - Silence l'utilisateur  
- `!removesilence <target>` - Supprime le silence de la cible   
- `!kick <username>` - Kick l'utilisateur du serveur
- `!ban <username>` - Ban et kick l'utilisateur 
- `!unban <username>` - Unban L'utilisateur  
- `!restrict <username>` - Restricte l'accès à l'utilisateur au serveur 
- `!unrestrict <username>` - Donne le droit d'accès à l'utilisateur au serveur  
- `!fokabot reconnect` - Reconnecte LoliBot s'il n'est plus sur la liste des utilisateur en ligne
- `!alert <message>` - Envoye une notification à chaque utilisateur connecté à Bancho  
- `!alertuser  <username> <message>` - Envoye une notification à un utilisateur spécifique
