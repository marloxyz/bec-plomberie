# Site B.E.C Plomberie – Villeneuve-Loubet

## Client
Plombier artisan à Villeneuve-Loubet (06). Plomberie, débouchage, remplacement de chauffe-eau et cumulus, pose et entretien de climatisation. Particuliers (et professionnels [À CONFIRMER]).
Zone : Villeneuve-Loubet + Cagnes-sur-Mer, Saint-Laurent-du-Var, La Colle-sur-Loup, Biot, Antibes [À CONFIRMER].
Fiche Google : 5,0 / 5, 23 avis (novembre 2026). Points forts cités dans les avis : réactif, ponctuel, travail propre et soigné, bons conseils, tarifs corrects, respect des délais.

## Coordonnées
- Tél : 07 49 65 68 85 (+33749656885)
- Adresse : 83 avenue de la Bermone, 06270 Villeneuve-Loubet
- Email : mubeneshacedric@gmail.com (reçoit aussi les demandes du formulaire)
- Horaires : lundi au samedi 07:30–20:00, dimanche 09:00–17:00
- Réseaux : [À CONFIRMER]
- SIRET / forme juridique / nom du dirigeant : [À FOURNIR]

## Pages
- Accueil (one-page) : hero (fond éclaboussure d'eau img/hero-eau.webp + voile bleu nuit), services, réalisations (galerie 7 photos + agrandissement), atouts, avis Google, horaires + adresse + zone, contact (téléphone + formulaire)
- Version anglaise : en/index.html (hreflang fr/en, bouton FR/EN dans l'en-tête, avis traduits du français avec mention). Les pages légales restent en français (liens « FR »).
- Mentions légales, Politique de confidentialité, 404

## Contenus
- Prestation mise en avant (carte bleu nuit pleine largeur) : « Installation haut de gamme » de salles de bain (douches à l'italienne, toilettes suspendues, salles de bain complètes). Puis 4 services : Plomberie, Débouchage, Chauffe-eau et cumulus, Climatisation. Liste détaillée des prestations [À CONFIRMER avec le client].
- Avis : 6 extraits réels de la fiche Google, signés prénom + initiale (Teo D., M. B., Florian G., Sagdana, Léo F., Anis). Ne pas modifier le sens.
- Ne rien inventer : pas de certifications, pas de prix, pas d'historique, pas de « 24h/24 ».
- Placeholders à remplacer : SIRET, clé Web3Forms.

## Stack
HTML + CSS statique (one-page, pas de build), déploiement Cloudflare Pages (dossier racine, pas de commande de build).
Formulaire de contact via Web3Forms (remplacer `ACCESS_KEY_A_FOURNIR` dans index.html).
Pas d'iframe Google Maps (cookies) : lien « Itinéraire » vers Google Maps à la place.

## SEO
- Mots-clés : plombier Villeneuve-Loubet, débouchage Villeneuve-Loubet, remplacement chauffe-eau / cumulus Villeneuve-Loubet, climatisation Villeneuve-Loubet, plombier Cagnes-sur-Mer, plombier Antibes
- Title + meta description uniques ; pages légales en noindex
- Schema.org `Plumber` avec NAP complet + horaires + services (pas d'aggregateRating : avis auto-hébergés non éligibles chez Google)
- sitemap.xml, robots.txt, Open Graph, URLs propres
- Domaine : https://www.bec-plomberie.fr [À CONFIRMER] (à remplacer dans canonical, og:url, sitemap, robots)

## Style
Couleurs du logo client : bleu nuit (#101D3B) et doré (#C9A66B, doré foncé #7F5F26 pour le texte sur blanc), blanc pour respirer. **Aucun orange.** En-tête et bandeau contact bleu nuit, boutons d'appel dorés à texte bleu nuit. Titres Barlow Condensed (majuscules), texte Barlow, nom de marque en Cinzel. Mobile-first, barre d'appel fixe en bas sur mobile. Thème sombre automatique.
Logo fourni par le client (robinet doré + écusson « BEC » sur fond bleu nuit) : `logo/logo-bec-plomberie.png` (original recadré), `logo-bec-plomberie-transparent.png`, `logo-bec-embleme.webp/png` (robinet + écusson détourés, utilisés dans l'en-tête avec « B.E.C / Plomberie » en texte), `logo-icone.png` + `apple-touch-icon.png` + `favicon.svg`. Image de partage `og-image.jpg` (1200×630).
Photos : 7 photos de la fiche Google dans `img/`. Vérifier avec le client qu'elles sont bien à lui.
Hero plein écran (hauteur de l'écran sur ordinateur et téléphone), sans texte d'intro sous le titre : images fournies par le client le 26/11 (salle de bain pierre sombre, baignoire îlot noire, miroir rond rétroéclairé, douche vitrée) : version paysage pour ordinateur/tablette, version verticale pour téléphone ; originaux dans /mnt/project-files/bec-plomberie/ : img/hero-salle-de-bain.webp 1672×941 (≥700px), img/hero-salle-de-bain-mobile.webp 800×1422, voile bleu nuit. Nom écrit « B.E.C » (sans point final) partout. Boutons : « Devis gratuit » / « Free quote ».

## Règles
- Textes en français
- Pas de librairies lourdes, images en WebP avec lazy-loading et alt
- Accessibilité : contrastes, focus visible, alt sur toutes les images
- Mentions légales : éditeur = le client ; hébergeur = Cloudflare, Inc., 101 Townsend St, San Francisco, CA 94107, USA
- Pas de traceurs (pas de bandeau cookies)

## Checklist de livraison
- [x] Responsive testé mobile / tablette / desktop (FR + EN, 25/11/2026)
- [ ] Lighthouse > 90 sur les 4 catégories
- [x] Logo du client intégré + image OG
- [ ] Formulaire fonctionnel (test d'envoi réel)
- [ ] Mentions légales + politique de confidentialité complétées (SIRET, email, dirigeant)
- [ ] Page 404
- [ ] Domaine branché sur Cloudflare Pages + HTTPS
- [ ] Fiche Google Business liée au site
