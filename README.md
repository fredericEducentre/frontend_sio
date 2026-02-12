# Frontend

Cette partie de l'application constitue l'interface utilisateur (UI) développée en HTML, CSS et JavaScript pur. Elle suit une architecture **découplée** et communique avec le backend via des API JSON.

## Structure du Projet

- `index.html` : Accueil du forum, affichage et publication des messages.
- `login.html` : Page de connexion utilisateur.
- `register.html` : Page d'inscription pour les nouveaux utilisateurs.
- `style.css` : Styles CSS partagés pour une interface moderne et responsive.

## Fonctionnement

1. **Architecture Découplée** : Le frontend est purement statique. Il n'a pas besoin de serveur PHP pour être affiché (il peut être servi par n'importe quel serveur statique ou ouvert directement).
2. **Communication API** : Il utilise la fonction `fetch()` de JavaScript pour envoyer et recevoir des données JSON aux points de terminaison situés dans `backend/api/`.
3. **Gestion de Session** : La "session" est gérée côté client via le `localStorage` du navigateur.

## Installation et Test

Modifier l'URL de l'API dans les fichiers `index.html`, `login.html` et `register.html` pour qu'elle corresponde à l'URL de votre serveur.
Assurez-vous que le backend est démarré
