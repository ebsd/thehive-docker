
https://github.com/TheHive-Project/CortexDocs/blob/master/admin/quick-start.md

- Créer un compte "superadmin" lors de la 1ere connexion
- Créer une organisation dans Cortex.
- Créer un nouvel utilisateur admin de cette organisation.
- Créer un user avec api key dans Cortex, sur la nouvelle organisation.
- Placer la apikey dans le fichier .env
- Démarrer : `docker-compose down && docker-compose up -d`
- Vérifier dans thehive > about que le statut de Cortex soit OK. Ceci peut prendre qq minutes apres demarrage.
- Se connecter à Cortex avec le compte admin de la nouvelle organisation.
- Dans Orga > onglet Analyzers Config, configurer les analyzers.

Pour l'installation de [Shuffle lire ici](https://github.com/Shuffle/Shuffle/blob/main/.github/install-guide.md).
