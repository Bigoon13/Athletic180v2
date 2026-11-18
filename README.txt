ATHLETIC 180 — V3

Application web progressive (PWA) de suivi sportif, nutritionnel et de récupération.

FICHIERS
- index.html : interface
- app.js : logique, programme et données locales
- style.css : présentation responsive
- sw.js : cache hors connexion
- manifest.webmanifest : installation PWA

DÉPLOIEMENT GITHUB PAGES
1. Décompresser le dossier athletic180.
2. Copier le contenu du dossier à la racine du dépôt GitHub (index.html doit être à la racine).
3. Déployer avec GitHub Actions / Deploy static content to GitHub Pages.

INSTALLATION IPHONE
1. Ouvrir l'URL HTTPS dans Safari et attendre le premier chargement complet.
2. Partager > Sur l'écran d'accueil.
3. Ouvrir l'application depuis l'icône. Les ressources sont mises en cache pour un usage hors connexion.

DONNÉES
Les données sont stockées localement dans le navigateur (localStorage). Utiliser régulièrement Exporter pour créer une sauvegarde JSON. Pas de synchronisation entre appareils.

V3 — ÉVOLUTIONS
- Rituel mobilité quotidien détaillé avec une seule validation globale.
- Calendrier : vert si séance + 4 repas validés ; orange si l'un des deux objectifs est validé ; neutre sinon.
- Trois cycles de musculation de 8 semaines avec exercices, séries et répétitions distincts.
- Natation, course et vélo structurés en base, développement et spécifique triathlon, avec semaines allégées.
- Upper Body ramené à 65–70 minutes échauffement compris.
- Mobilité/gainage du mercredi détaillés dans Training.
- Liste de courses classée par rayons.
- Poids saisi avec les mensurations, courbe consolidée des anciennes et nouvelles mesures.
- Données personnalisées de séances de la V2 archivées sous legacySessionEdits dans l'export local ; elles ne remplacent plus les nouvelles séances des cycles.

NOTES
Les durées, volumes et intensités sont des cibles de départ à ajuster à la récupération réelle. Les séances d'endurance sont majoritairement faciles ; les blocs tempo restent contrôlés. Les recettes et macros sont des estimations.
