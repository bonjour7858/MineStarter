# Minestrator Starter Panel

Panneau de contrôle web sécurisé pour piloter un serveur Minecraft hébergé sur Minestrator via Supabase.

## 🚀 Fonctionnalités
- **Authentification sécurisée** : Accès restreint au compte administrateur autorisé.
- **Commandes en un clic** : Démarrer, arrêter, redémarrer et consulter le statut du serveur.
- **Sécurité API** : Les clés API Minestrator sont conservées au niveau de la base de données et ne sont jamais exposées côté navigateur.
- **Logs automatiques** : Traçabilité des actions dans la table `server_logs`.

## ⚙️ Configuration
1. Dans `index.html`, renseignez les variables `SUPABASE_URL` et `SUPABASE_ANON_KEY`.
2. Activez l'hébergement dans l'onglet **Settings > Pages** du dépôt GitHub :
   - Branch : `main`
   - Folder : `/ (root)`
