# Favoris Deemply (UPF - SJSV)

Scripts des deux favoris « Calendrier Deemply » et « Poste de garde », qui s'ouvrent par-dessus [Deemply](https://app.deemply.com) pour le site UPF - SJSV.

| Fichier | Favori |
| --- | --- |
| `calendrier.js` | Calendrier Deemply |
| `poste-de-garde.js` | Poste de garde |

Ces fichiers sont générés (code minifié) : ne pas les modifier à la main. Le favori installé dans Chrome est un petit chargeur qui ne change jamais : à chaque clic, il lit le fichier ici, via jsDelivr :

```
https://cdn.jsdelivr.net/gh/ejyzio/deemply-favoris@main/calendrier.js
https://cdn.jsdelivr.net/gh/ejyzio/deemply-favoris@main/poste-de-garde.js
```

Il garde une copie de la dernière version dans le navigateur, utilisée si jsDelivr ne répond pas.

Aucun mot de passe ni jeton ici : les scripts utilisent la session Deemply déjà ouverte dans le navigateur de l'utilisateur.
