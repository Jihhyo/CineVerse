# CineVerse
CineVerse est une plateforme sociale pour cinéphiles. Les utilisateurs peuvent noter, commenter, lister et recommander des films. Le but : partager sa passion du cinéma, découvrir de nouvelles pépites et échanger avec d'autres amateurs.

Étape 1 – Plan du projet
🧑‍💻 Fonctionnalités MVP (version de base mais solide)
🔐 Authentification
Signup / login / logout

Profils publics + avatars + bio

🎬 Catalogue de films
Recherche de films (via API TMDB)

Fiches détaillées (synopsis, cast, trailer, etc.)

Ajout en "Déjà vu", "Watchlist", ou "Favoris"

⭐ Avis & critiques
Noter un film (1 à 5 étoiles)

Écrire une critique visible publiquement

Like / dislike sur les critiques

🧑‍🤝‍🧑 Réseau social
Follow d’autres utilisateurs

Feed d’activités (films vus, critiques publiées, etc.)

Profil public avec stats : films vus, moyenne, genres préférés, etc.

Fonctionnalités BONUS possibles plus tard :
Groupes de cinéphiles (genre mini clubs)

Recos intelligentes (films similaires à ce que t’aimes)

Système de quizz ou de badges

Intégration "où voir ce film" (Netflix, Prime, etc.)

Liste collaborative (ex : “films à regarder en couple”)
🛠️ Stack technique proposée
🌐 Frontend
React (ou Next.js si tu veux SSR)

TailwindCSS pour un UI clean + rapide

Framer Motion pour des animations douces

🧠 Backend
Node.js + Express (ou NestJS si t’aimes le clean archi)

Authentification via JWT

Intégration TMDB API pour les données film

Appels API via Axios / fetch

🗃️ Base de données
PostgreSQL (relationnelle, propre pour ce genre de données)

Avec Prisma ou Sequelize pour ORM

🧩 Étape 2 – Structure de l’app
🔹 Pages principales :
/signup / /login

/films (recherche + listes)

/film/:id (fiche film)

/profil/:username (profil utilisateur)

/dashboard (page perso avec stats, watchlist, etc.)

/feed (activité de tes followings)

/critique/:id (page de critique complète)
