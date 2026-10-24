# Yelema, page d'accueil v3 : liste des changements par rapport à la v2

Koffi, 24/10/2026. Préversion non indexée (balise noindex conservée).

## Ce qui n'a pas bougé
- L'ordre des dix sections, la charte (couleurs, Space Grotesk, Funnel Display) et les textes de la v2, mot pour mot, sauf les deux corrections signalées plus bas.
- Les 24 Experts, les six équipes, les prix, les témoignages et les logos clients.

## Hero (la plus grosse évolution)
1. Mise en page en deux colonnes : le message à gauche, l'équipe au travail à droite. On voit l'équipe dès l'arrivée sur la page, sans avoir à défiler.
2. Le « mur d'équipe » devient une démonstration : les quatre Experts se passent le relais un par un (coche verte à chaque étape). Puis la demande d'accord s'allume (« Publier les douze publications du mois ? », avec Valider et Modifier), et enfin le livrable. En cinq secondes, le visiteur comprend qu'il achète une équipe qui fait le travail, et qu'il garde la décision.
3. Chaque Expert affiche sa tâche concrète, reprise du cycle de la section 4.
4. La rotation s'arrête quand le visiteur survole le bloc, le parcourt au clavier, choisit une fonction ou quitte le hero.

## Design
5. Les sections apparaissent en douceur au défilement, carte par carte.
6. Les survols sont soignés : cartes qui se soulèvent, logos clients en gris qui prennent leurs couleurs, flèche « Voir l'équipe au travail » qui avance.
7. Dans le menu, la section en cours est soulignée. Le menu passe en fond clair dès qu'on quitte le haut de page.
8. Les titres s'adaptent à la largeur de l'écran et se coupent de façon équilibrée.
9. Le cycle de la section 4 se déroule étape par étape à chaque changement de fonction.

## Mobile (360 px)
10. Un menu mobile a été ajouté : la v2 n'en avait pas, la navigation disparaissait sur téléphone. Il se ferme avec la croix, avec la touche Échap ou au choix d'un lien.
11. Aucun défilement horizontal, vérifié à 360 px.
12. Boutons pleine largeur et menus déroulants de 50 px de haut, faciles à toucher au pouce.

## Accessibilité
13. Contrastes AA : le violet #8D68FA restait sous le seuil sur fond blanc (3,8 pour 1). Pour les petits textes sur fond clair, il passe à #6A45E0 (5,9 pour 1), et le corail à #B5452C (5,4 pour 1). Les couleurs de la charte restent inchangées sur fond sombre et pour les grands titres.
14. Un lien « Aller au contenu » est ajouté pour la navigation au clavier, avec un contour de focus visible partout.
15. Les portraits portent le nom de l'Expert pour les lecteurs d'écran, et les motifs décoratifs leur sont masqués.
16. Le réglage « réduire les animations » est respecté : plus aucune rotation ni apparition, l'équipe s'affiche complète.

## Performance
17. Images converties en WebP, à la bonne taille : le site pèse 399 Ko au total.
18. Deux polices variables en woff2, préchargées, au lieu de six fichiers.
19. Aucune bibliothèque externe.

## Textes
20. Offre Exécutif : « sans frais d'installation » est conservé, confirmé par Leslie le 24/10/2026 (les frais d'installation ne concernent pas l'Exécutif).
21. FAQ : « c'est même le conseil que nous donnons » devient « c'est même ce que nous recommandons ». Le mot « conseil » est exclu du vocabulaire.

## À proposer, non intégré (repris de la v1)
- A. Une page Offres détaillée : ce que l'Expert prend en charge, ce que le salarié garde.
- B. Les cas d'usage par secteur : banque, distribution, industrie, télécoms, administration, assurance.
- C. Une page par équipe, à la place des douze anciennes fiches individuelles.
