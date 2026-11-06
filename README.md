# Classe Live

Outil de visioconférence pour les cours à distance : son, caméra, partage d'onglet avec défilement depuis la visio, salle d'attente, main levée, chat, tableau blanc, sondage éclair, minuteur et liste de présence.

- **Enseignant** : ouvrir le site, « Créer une nouvelle salle », puis « Inviter » pour copier le lien et le code.
- **Élèves** : ouvrir le lien reçu, saisir prénom et nom, puis attendre d'être admis.

Fonctionnement : WebRTC (son et vidéo de navigateur à navigateur, en étoile autour de l'enseignant) et Supabase Realtime pour la mise en relation. Conseillé jusqu'à 10-15 élèves.

Démo sur un seul ordinateur : ajouter `?local=1` à l'adresse et ouvrir plusieurs onglets.
