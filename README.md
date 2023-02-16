
# Rina Stat's

Un bot adapté pour le serveur Supremity et des commandes de statistiques ainsi que d'aides.
Dernière MAJ : **13/02/2023 - 22:00**

[Discord Clan Supremity](https://discord.gg/Y8jnqTT55S/)


## Commandes (préfix du bot sur discord : '`r/`')

**\<Facultatif\> | [Obligatoire] | 🔰 : COMMANDE ADMIN !**

- `help` - Affiche cette page.
   <br />
   Aliases : 'h'

- `stats <username>` - Affiche les statistiques Bedwars du pseudo voulu, affiche les votres si 'username' n'est pas renseigné.
   <br />
   Aliases : 'bw'
  
- `rinastats` - Affiche les statistiques du serveur Rinaorc.
   <br />
   Aliases : 'rs'
   
- `carte` <usrname> - Affiche les statistiques du Joueur sous forme de carte (interface graphique png).
   <br />
   Aliases : None
   
- 🔰 `gdiscord [username]` - Affiche le discord du joueur renseigné (username Rinaorc).
   <br />
   Aliases : 'ds'
 
 - 🔰 `updateMemberCount` - Actualise les membres du serveur discord via le channel.id 1071931013896351876.
   <br />
   Aliases : 'umc'



## Licence






[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)



## Auteur

- [@BenjiPy](https://github.com/BenjiPy)

*TrqyHarD* à aussi mis en oeuvre la création de ce bot.
## Support

Pour toute demande de code source ou de support merci de me contacter par discord !

* **Benji's#0001**


## Utilisation/Exemple API Rinaorc

![Python](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f8/Python_logo_and_wordmark.svg/131px-Python_logo_and_wordmark.svg.png)


```
pip install requests
```

```python
import requests

token = "VOTRE CLEF API (/api in game)"
headers = {"API-Key": f"{token}"}
rname = "Bornea"
response = requests.get(f"https://api.rinaorc.com/player/{name}", headers=headers)

```


## 🔗 Links
[![Instagram](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Instagram_icon.png/20px-Instagram_icon.png)](https://www.instagram.com/benbikzz/?hl=fr/)

[![Discord](https://upload.wikimedia.org/wikipedia/fr/thumb/9/98/Discord_logo.svg/langfr-90px-Discord_logo.svg.png)](https://discord.gg/Y8jnqTT55S/)





