# Documentation publique — Suivi Manifold E0-M3

Ce dépôt est destiné à GitHub Pages. Il contient uniquement la présentation de l'application, sa politique de confidentialité et leur feuille de style.
Le code du collecteur, les captures de marché et tous les identifiants restent dans leurs emplacements privés.

Publication attendue : branche main, dossier /(root), mode Deploy from a branch.
L'activation et l'URL doivent être vérifiées dans Settings → Pages avant d'utiliser les liens dans Google Cloud.

Vérification Google :
1. Après publication effective, ouvrir Google Search Console avec le compte propriétaire du projet OAuth.
2. Ajouter une propriété de type Préfixe d'URL correspondant exactement à l'URL HTTPS du site.
3. Choisir la méthode Balise HTML et récupérer la balise google-site-verification.
4. Ajouter cette balise exacte dans le head de index.html; ne jamais utiliser une valeur inventée.
5. Attendre sa présence dans la page publique, puis demander la validation à Google.
6. Dans Branding, renseigner l'URL de présentation et l'URL privacy.html réellement publiées, puis le sous-domaine autorisé reconnu par Google.
7. Vérifier que le bouton de publication OAuth est devenu disponible. La création du site ne prouve pas à elle seule l'acceptation de Google.

Le niveau OAuth actuellement demandé est drive (accès large). La documentation le dit explicitement. Aucune collecte ni nouvelle autorisation n'est activée par ce site.
