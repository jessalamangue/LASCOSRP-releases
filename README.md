# LASCOSRP — fichiers publiés

Ce dépôt contient uniquement les fichiers distribués aux joueurs du serveur RP BONELAB **LASCOSRP** :
le launcher, le mod `LascoSRP.dll` et sa bibliothèque `Npgsql.dll`.

Le launcher lit `manifest.json` pour savoir quelle est la dernière version et vérifie chaque fichier
téléchargé grâce à son empreinte SHA-256 avant de l'installer.

Ne pas modifier ce dépôt à la main : il est mis à jour par le script `scripts/publish.ps1` du projet.
