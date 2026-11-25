# Site B.E.C Plomberie – Villeneuve-Loubet

## Client
Plombier artisan à Villeneuve-Loubet (06). Plomberie, débouchage, remplacement de chauffe-eau et cumulus, pose et entretien de climatisation. Particuliers (et professionnels [À CONFIRMER]).
Zone : Villeneuve-Loubet + Cagnes-sur-Mer, Saint-Laurent-du-Var, La Colle-sur-Loup, Biot, Antibes [À CONFIRMER].
Fiche Google : 5,0 / 5, 23 avis (novembre 2026). Points forts cités dans les avis : réactif, ponctuel, travail propre et soigné, bons conseils, tarifs corrects, respect des délais.

## Coordonnées
- Tél : 07 49 65 68 85 (+33749656885)
- Adresse : 83 avenue de la Bermone, 06270 Villeneuve-Loubet
- Email : [À FOURNIR]
- Horaires : lundi au samedi 07:30–20:00, dimanche 09:00–17:00
- Réseaux : [À CONFIRMER]
- SIRET / forme juridique / nom du dirigeant : [À FOURNIR]

## Pages
- Accueil (one-page) : hero (fond éclaboussure d'eau img/hero-eau.webp + voile bleu nuit), services, réalisations (galerie 7 photos + agrandissement), atouts, avis Google, horaires + adresse + zone, contact (téléphone + formulaire)
- Version anglaise : en/index.html (hreflang fr/en, bouton FR/EN dans l'en-tête, avis traduits du français avec mention). Les pages légales restent en français (liens « FR »).
- Mentions légales, Politique de confidentialité, 404

## Contenus
- 4 services : Plomberie, Débouchage, Chauffe-eau et cumulus, Climatisation. Liste détaillée des prestations [À CONFIRMER avec le client].
- Avis : 6 extraits réels de la fiche Google, signés prénom + initiale (Teo D., M. B., Florian G., Sagdana, Léo F., Anis). Ne pas modifier le sens.
- Ne rien inventer : pas de certifications, pas de prix, pas d'historique, pas de « 24h/24 ».
- Placeholders à remplacer : email, SIRET, clé Web3Forms, image OG (og-image.jpg 1200×630).

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
Bleu ciel (#1E9BE0) et blanc dominants, touches d'orange (#D9670F) sur les boutons d'appel et les points du logo. Texte en bleu nuit (#12344D) pour la lisibilité. Titres Barlow Condensed (majuscules), texte Barlow. Mobile-first, barre d'appel fixe en bas sur mobile. Thème sombre automatique.
Logo créé (goutte blanche dans un rond bleu ciel + « B.E.C » / « PLOMBERIE ») : dossier `logo/` (SVG texte vectorisé + PNG ×4, version couleur, version blanche, icône). Favicon = icône.
Photos : 7 photos de la fiche Google dans `img/` (salle-de-bain, cabine-douche 720×960 ; douche-italienne, chauffe-eau, salle-de-bain-moderne, meuble-vasque, baignoire 600×800). Vérifier avec le client qu'elles sont bien à lui (certaines peuvent venir d'avis clients).
Hero : éclaboussure d'eau générée par code (img/hero-eau.webp 2560×800 pour ≥700px, img/hero-eau-mobile.webp 1200×1800 pour téléphone), libre de droits. Nom écrit « B.E.C » (sans point final) partout. Boutons : « Devis gratuit » / « Free quote ».

## Règles
- Textes en français
- Pas de librairies lourdes, images en WebP avec lazy-loading et alt
- Accessibilité : contrastes, focus visible, alt sur toutes les images
- Mentions légales : éditeur = le client ; hébergeur = Cloudflare, Inc., 101 Townsend St, San Francisco, CA 94107, USA
- Pas de traceurs (pas de bandeau cookies)

## Checklist de livraison
- [x] Responsive testé mobile / tablette / desktop (FR + EN, 25/11/2026)
- [ ] Lighthouse > 90 sur les 4 catégories
- [ ] Logo validé par le client + image OG
- [ ] Formulaire fonctionnel (test d'envoi réel)
- [ ] Mentions légales + politique de confidentialité complétées (SIRET, email, dirigeant)
- [ ] Page 404
- [ ] Domaine branché sur Cloudflare Pages + HTTPS
- [ ] Fiche Google Business liée au site
