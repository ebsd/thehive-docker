
https://github.com/TheHive-Project/CortexDocs/blob/master/admin/quick-start.md

- Cr�er un compte "superadmin" lors de la 1ere connexion
- Cr�er une organisation dans Cortex.
- Cr�er un nouvel utilisateur admin de cette organisation.
- Cr�er un user avec api key dans Cortex, sur la nouvelle organisation.
- Placer la apikey dans le fichier .env
- D�marrer : `docker-compose down && docker-compose up -d`
- V�rifier dans thehive > about que le statut de Cortex soit OK. Ceci peut prendre qq minutes apres demarrage.
- Se connecter � Cortex avec le compte admin de la nouvelle organisation.
- Dans Orga > onglet Analyzers Config, configurer les analyzers.

Pour l'installation de [Shuffle lire ici](https://github.com/Shuffle/Shuffle/blob/main/.github/install-guide.md).
