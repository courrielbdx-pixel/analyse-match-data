# analyse-match-data

Flux de données publié automatiquement par **Grok Bot** pour le site **Analyse Match v6**.

- `DATA_BASE_URL` : `https://raw.githubusercontent.com/bruno76-grok/analyse-match-data/main`
- Contenu (section 7 du cahier des charges, `schema_version` 6.0) : `meta.json`, `fixtures/AAAA-MM-JJ.json`, `picks/AAAA-MM-JJ.json`, `live/AAAA-MM-JJ.json`, `details/{fixture_id}.json`, `results/bilan.json`.
- Méthode `dc-v1` : modèle statistique Dixon-Coles **sans cotes en entrée** ; un pick par match et par lecture ; TICKET ou SKIP selon des règles fixes (voir `meta.json` → `rules`).
- **Suivi papier** : le backtest 2024–2026 ne montre aucun avantage contre les cotes. Rien ici n'est un conseil de pari.
- Les cotes affichées sont « pour information » (bookmakers internationaux via API-Football ; aucun bookmaker agréé ANJ disponible dans cette source).
- Ce dépôt ne contient **aucune clé, aucun jeton, aucun code moteur** : uniquement des fichiers JSON publics, en lecture seule.
