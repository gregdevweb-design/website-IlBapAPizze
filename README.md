# Il Bar A Pizze — Site démo

Site vitrine de démonstration pour **Il Bar A Pizze**, pizzeria italienne à Montpellier
(Port Marianne, bord du Lez) — la pizzeria la mieux notée de la ville (★4,9, 2 300+ avis Google).

**Démo en ligne :** https://website-ilbapapizze.pages.dev

## Stack

- HTML / CSS / JS vanilla, statique, mobile-first — aucune dépendance, aucun build.
- SEO : meta + Open Graph par page, JSON-LD `Restaurant`, `sitemap.xml`, `robots.txt`, carte 100 % indexable en HTML.
- Légal FR : mentions légales + politique de confidentialité (RGPD), aucun cookie déposé.
- Hébergement : Cloudflare Pages.

## Notes démo

- Les photos sont chargées depuis le CDN du site actuel du restaurant (à remplacer par des fichiers locaux fournis par le client en production).
- La carte et certains prix sont illustratifs (signalé sur la page) — base : plats emblématiques relevés publiquement (burrata, pizza fritta, calzone, carbonara, tiramisu). La carte réelle sera intégrée avec l'équipe.
- La réservation pointe vers la fiche TheFork existante du restaurant.

## Déploiement

Les fichiers du site sont dans `public/` (seul dossier déployé) :

```powershell
npx wrangler pages deploy public --project-name=website-ilbapapizze
```

---

Site démo réalisé par Grégoire Fontaine.
