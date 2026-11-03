# Jonathan Zvara — Développeur d'application Python

Développeur **Python back-end** en reconversion. J'ai terminé en novembre 2026 le parcours
OpenClassrooms **« Développeur d'application Python »** : 14 projets professionnalisants, de
l'algorithmique jusqu'au déploiement continu d'une application Django.

🎯 **Je recherche un poste de développeur Python junior (CDI / CDD), en télétravail.**

📫 jonathan.zvara@gmail.com · 📒 [Ma veille professionnelle et technique](VEILLE.md)

---

## Compétences

| Domaine | Outils |
|---|---|
| **Langage** | Python 3 |
| **Web & API** | Django · Django REST Framework · JWT · Flask |
| **Données** | PostgreSQL · SQLAlchemy · SQLite · JSON · CSV |
| **Qualité** | PEP 8 vérifiée avec flake8 · pytest · pytest-cov · Locust (tests de charge) · tests unitaires, d'intégration, fonctionnels |
| **DevOps** | Docker · GitHub Actions (CI/CD) · Render · Sentry · Sphinx / Read the Docs |
| **Sécurité** | OWASP Top 10 · hachage Argon2 · moindre privilège · RGPD |
| **Front** | HTML · CSS · JavaScript (API `fetch`) |
| **Méthode** | Git / GitHub · cahier des charges · backlog · décisions d'architecture documentées |

---

## Projets à la une

### 🏠 [OC Lettings](https://github.com/Hermes3x/OC_Lettings) — industrialisation d'un site Django

Refonte d'un site Django monolithique en **architecture modulaire** (applications `lettings` et
`profiles`), sans perte de données, puis mise en production.

- Pipeline **GitHub Actions** : flake8, tests avec **couverture minimale de 80 %**, image
  **Docker** publiée sur Docker Hub, déploiement automatique sur **Render**
- Supervision des erreurs avec **Sentry**, documentation **Sphinx** sur Read the Docs
- Décisions d'architecture tracées dans un [`DECISIONS.md`](https://github.com/Hermes3x/OC_Lettings/blob/master/DECISIONS.md) versionné

`Django 5.2` `Docker` `GitHub Actions` `Sentry` · [Site en ligne](https://oc-lettings-rmfb.onrender.com) · [Documentation](https://oc-lettings-rmfb.readthedocs.io/fr/latest/)

> Projet construit à partir d'un dépôt de départ fourni par OpenClassrooms : le découpage en
> applications, les migrations, les tests, le pipeline, Docker, Sentry et la documentation sont
> mon travail.

### 🔐 [Epic Events CRM](https://github.com/Hermes3x/epic_events_crm) — back-end sécurisé

CRM en ligne de commande pour une entreprise d'événementiel : clients, contrats, événements,
avec un **contrôle d'accès par département**.

- Authentification par **JWT**, mots de passe hachés en **Argon2**
- Base **PostgreSQL** accédée par un compte applicatif **non privilégié** (moindre privilège)
- Requêtes paramétrées via l'ORM **SQLAlchemy**, journalisation des incidents dans **Sentry**
- **54 tests** pytest ; schéma de base de données documenté

`Python` `SQLAlchemy` `PostgreSQL` `JWT` `Sentry`

### 🧪 [GÜDLFT](https://github.com/Hermes3x/Python_Testing) — tests et débogage d'une application Flask

Correction des bugs d'une plateforme de réservation, puis ajout d'une fonctionnalité, en
**développement piloté par les tests**.

- **56 tests** (unitaires, intégration, fonctionnels) · **100 % de couverture**
- Tests de performance avec **Locust**
- Migration vers Flask 3 sans modifier le code applicatif

`Flask` `pytest` `Locust` · *Fork du dépôt OpenClassrooms : corrections, tests et nouvelle
fonctionnalité sont mon travail.*

### 🛠️ [SoftDesk Support API](https://github.com/Hermes3x/SoftDesk) — API REST

API de suivi de tickets techniques pour des clients B2B : projets, contributeurs, issues,
commentaires.

- Authentification **JWT**, permissions par rôle (auteur / contributeur)
- Conformité **RGPD** : âge minimal, consentements, droit à l'oubli
- Pagination des listes (green code), règles **OWASP**

`Django REST Framework` `SimpleJWT`

---

## Autres projets

| Projet | Description | Stack |
|---|---|---|
| [LITReview](https://github.com/Hermes3x/LITReview) | Réseau social de critiques de livres : flux personnalisé, tickets, critiques, abonnements | Django · SQLite |
| [JustStreamIt](https://github.com/Hermes3x/JustStreamIt) | Interface web de catalogue de films alimentée par une API REST | HTML · CSS · JavaScript |
| [Chess Tournament Manager](https://github.com/Hermes3x/OC_P4_Chess) | Gestion de tournois d'échecs en ligne de commande, appariement suisse, architecture MVC | Python · JSON · flake8 |
| [Books to Scrape](https://github.com/Hermes3x/OC_P2_Scraper) | Pipeline ETL : extraction des livres d'un site, export CSV par catégorie et images | requests · BeautifulSoup |

---

## Comment je travaille

- **Les tests d'abord** : un test vu rouge avant d'être vert, `pytest` en local avant chaque push.
- **L'intégration continue comme filet** : rien n'atteint la production sans lint ni tests verts.
- **Les décisions écrites** : chaque choix d'architecture est consigné avec les options
  envisagées et la raison de l'arbitrage.
- **L'IA comme outil, pas comme pilote** : je m'en sers pour la configuration et pour comprendre
  de nouveaux concepts ; les décisions restent les miennes, et je documente ce que j'en retiens.
