 Langages et Technologies Utilisés
HTML – Structure de la page du chat.

CSS – Mise en forme responsive et moderne.

JavaScript (Vanilla) – Côté client pour l'interaction temps réel avec Socket.IO.

Node.js – Côté serveur.

Express – Framework pour créer le serveur HTTP.

Socket.IO – Pour gérer la communication en temps réel (WebSockets).

🧩 Détails des fichiers
server.js
Lance un serveur HTTP avec Express.

Sert les fichiers du dossier public.

Initialise Socket.IO.

Gère la réception et la diffusion des messages à tous les utilisateurs connectés.

public/index.html
Affiche un formulaire pour entrer un pseudo.

Masque le chat jusqu’à validation.

Contient une zone de messages + champ d'envoi.

Charge Socket.IO et script.js.

public/style.css
Centre et stylise le formulaire et le chat.

Design moderne responsive (mobile et desktop).

public/script.js
Gère le pseudo de l’utilisateur.

Envoie les messages au serveur via Socket.IO.

Affiche dynamiquement les messages reçus.

Bascule entre l’écran de login et le chat.

🚀 Fonctionnalités
Chat en temps réel avec Socket.IO.

Interface simple et responsive.

Aucun backend complexe : tout est en mémoire
