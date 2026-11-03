# Veille professionnelle et technique — Jonathan Zvara

> Développeur d'application Python · veille **hebdomadaire automatisée** · dernière mise à jour : **03/11/2026**

## Sommaire

1. [Comment je réalise ma veille](#1-comment-je-réalise-ma-veille)
2. [Mon projet professionnel](#2-mon-projet-professionnel)
3. [Opportunités professionnelles](#3-opportunités-professionnelles)
4. [Sources de veille technique](#4-sources-de-veille-technique)
5. [Journal de progression](#5-journal-de-progression)

---

## 1. Comment je réalise ma veille

Ma veille des offres est **automatisée** : j'ai créé une *skill* pour Claude que je lance chaque
semaine. Elle interroge les job boards ci-dessous avec mes critères, puis met à jour la
[section 3](#3-opportunités-professionnelles).

### Comment je trouve une offre adaptée — ce que fait la skill

1. **Filtrer** : mot-clé `python` ou `django`, « télétravail complet », niveau junior ou
   « 0 à 2 ans ».
2. **Lire l'offre à l'envers** : la stack et les missions avant le titre. Un « développeur
   full-stack » qui fait 80 % de Django m'intéresse ; un « développeur Python » qui fait de la
   data science, non.
3. **Vérifier le télétravail** : « full remote » doit être écrit dans l'offre, pas seulement
   dans le filtre du site. Sinon, l'offre est notée « hybride ».
4. **Croiser trois signaux** : l'offre, la page de l'entreprise (taille, produit, équipe tech) et
   les avis (Glassdoor, Welcome to the Jungle).
5. **Rapprocher de mon portfolio** : pour chaque offre retenue, le projet le plus proche de sa
   stack (OC Lettings pour Django et CI/CD, Epic Events pour la sécurité et PostgreSQL, SoftDesk
   pour une API REST).

### Job boards interrogés

| Source | Recherche enregistrée | Pourquoi |
|---|---|---|
| **LinkedIn Jobs** | [« développeur python », France, remote, débutant](https://www.linkedin.com/jobs/search/?keywords=d%C3%A9veloppeur%20python&location=France&f_WT=2&f_E=1%2C2&f_TPR=r604800) | La source la plus riche ; les filtres s'appliquent une fois connecté |
| **HelloWork** | [python, télétravail complet](https://www.hellowork.com/fr-fr/emploi/recherche.html?k=python&l=France&t=Complet) | Filtre full remote fiable ; peu de volume |
| **Free-Work** | [CDI](https://www.free-work.com/fr/tech-it/jobs?query=python&contracts=permanent&remote=full) · [freelance](https://www.free-work.com/fr/tech-it/jobs?query=python&contracts=contractor&remote=full) en full remote | Affiche le taux de télétravail, le salaire ou le TJM, la date exacte |
| **Welcome to the Jungle** | [emplois full remote](https://www.welcometothejungle.com/fr/pages/emploi-full-remote) · [développeur Python](https://www.welcometothejungle.com/fr/pages/emploi-developpeur-python) | Fiches détaillées : télétravail, expérience demandée, culture d'entreprise |
| **RemoteFR** | [compétence Python](https://remotefr.com/competences/python) | Job board 100 % télétravail, centré sur la France |
| **Jobgether** | [Python, remote, France](https://jobgether.com/remote-jobs/france/python-developer) | Offres remote internationales, avec l'éligibilité par pays |
| **AFPy** | [forum emploi](https://discuss.afpy.org/c/emplois/14) | Peu d'offres, mais 100 % Python, souvent avec télétravail |
| **France Travail** | [« développeur python »](https://candidat.francetravail.fr/offres/recherche?motsCles=d%C3%A9veloppeur+python&offresPartenaires=true&tri=1) | Gros volume, CDD et postes junior en région |

### Le marché caché

Une partie des postes ne sont jamais publiés. Je m'y prépare par :

- mon profil **LinkedIn**, tenu à jour avec le lien de ce portfolio ;
- les **candidatures spontanées** auprès des entreprises qui recrutent souvent des profils Django ;
- la communauté **AFPy** (Association francophone Python), son forum et ses offres d'emploi.

### Comment je la tiens à jour facilement

| Quand | Quoi |
|---|---|
| **Chaque semaine** | Je lance la skill : elle relève les nouvelles offres et met à jour la section 3 |
| **Au fil de l'eau** | La newsletter arrive dans un dossier dédié de ma messagerie ; les chaînes YouTube sont dans mes abonnements |
| **Après chaque projet** | J'ajoute le projet au [portfolio](https://github.com/Hermes3x) et au journal de progression |
| **Chaque mois** | Je retire les sources que je ne lis plus et les offres de plus d'un mois |

**Pourquoi c'est facile à tenir** : la collecte est automatisée, et tout tient dans **un seul
fichier Markdown** versionné sur GitHub. Je le modifie depuis VS Code ou directement dans le
navigateur, et l'historique Git garde une trace datée de chaque mise à jour.

---

## 2. Mon projet professionnel

| Critère | Mon choix |
|---|---|
| **Objectif** | Premier poste de **développeur Python back-end junior** |
| **Contrat** | CDI ou CDD |
| **Lieu** | **Télétravail complet**, entreprise basée en France |
| **Stack visée** | Python · Django / Django REST Framework · PostgreSQL |
| **Outils souvent demandés en plus** | Docker et intégration continue (CI/CD) : cités dans 5 des 10 offres d'emploi relevées le 03/11/2026 |
| **Plan B** | Missions freelance courtes en Python (scripts, API, automatisation) pour accumuler de l'expérience |
| **Portfolio** | [github.com/Hermes3x](https://github.com/Hermes3x) |

**Ce qui me distingue** : une reconversion menée de bout en bout sur 14 projets, une pratique
réelle des tests (100 % de couverture sur un projet Flask), de la sécurité (OWASP, Argon2,
moindre privilège) et du déploiement continu (Docker, GitHub Actions, Sentry).

---

## 3. Opportunités professionnelles

### Offres d'emploi — télétravail complet (relevé du 03/11/2026)

| Entreprise | Poste | Contrat · salaire | Niveau demandé | Statut | Lien |
|---|---|---|---|---|---|
| **AVELSEN** (ESN) | Ingénieur·e Full Stack — développeur junior | Temps plein · non indiqué | **0 à 2 ans**, bac+3 à bac+5 | **À candidater** | [Offre](https://www.linkedin.com/jobs/view/4478457609) |
| **YEVO** | Développeur Python / Django | Temps plein · non indiqué | Expérience Python/Django, durée non précisée | **À candidater** — full remote « selon l'autonomie », à confirmer | [Offre](https://www.linkedin.com/jobs/view/4480259912) |
| Startup SaaS cybersécurité (via Opus Recruitment) | Développeur fullstack Django | CDI · jusqu'à 65 k€ | Expérience confirmée | À étudier — au-dessus de mon niveau | [Offre](https://www.linkedin.com/jobs/view/4485465903) |
| Entreprise non nommée (via Jobgether) | Python Developer | Temps plein · non indiqué | 2 ans minimum | À étudier — au-dessus de mon niveau | [Offre](https://www.linkedin.com/jobs/view/4482592681) |
| **Dashdoc** (SaaS transport) | Software Engineer — Shippers Team | CDI · 50 à 80 k€ | Plus de 3 ans | Repère marché — stack identique à la mienne (Django, DRF, GitHub Actions) | [Offre](https://www.welcometothejungle.com/fr/companies/dashdoc/jobs/software-engineer) |
| **Canonical** (Ubuntu) | Graduate Software Engineer, Open Source and Linux | Non précisé | Diplômés 2025 ou 2026 | À étudier — vérifier mon éligibilité | [Offre](https://canonical.com/careers/8249005) |

### Offres junior en hybride — hors de ma cible, gardées comme repères

| Entreprise | Poste | Contrat · salaire | Télétravail | Lien |
|---|---|---|---|---|
| **AXA Climate** (Paris) | Junior Python Developer | CDI · non indiqué | Fréquent | [Offre](https://www.welcometothejungle.com/fr/companies/axa-climate/jobs/junior-python-developer_paris) |
| **Scalian** (Vitrolles) | Développeur Python | CDI · 36 à 42 k€ | Accord télétravail | [Offre](https://www.linkedin.com/jobs/view/4481541960) |
| **Sigma** (Tarn) | Développeur IA & Support | CDI · 36 à 40 k€ | À étudier | [Offre](https://www.linkedin.com/jobs/view/4480123350) |
| **Sia** (Paris) | Junior Software Engineer | Temps plein · non indiqué | Non mentionné | [Offre](https://www.linkedin.com/jobs/view/4484040721) |

### Missions freelance — plan B

| Client | Mission | Tarif · durée | Niveau demandé | Lien |
|---|---|---|---|---|
| **BELENDER** (fintech) | Python Scraping Engineer, 100 % remote | Jusqu'à 4 500 €/mois · 40 h/semaine | 2 ans d'expérience en France | [Mission](https://www.linkedin.com/jobs/view/4478590722) |
| **Galadrim** | Ingénieur·e IA freelance, télétravail total | Moins de 300 €/jour · 4 mois en moyenne | Plus d'un an | [Mission](https://www.welcometothejungle.com/fr/companies/galadrim/jobs/ingenieur-ia-freelance) |
| **Synertup** | Fullstack Python / React — IA et CAO, 100 % télétravail | TJM à proposer · ponctuelle | Expérimenté | [Mission](https://www.linkedin.com/jobs/view/4484474669) |
| Client non nommé (via ISUPPLIER) | Python Django en remote | 200 à 400 €/jour · 1 mois | 5 à 10 ans | [Mission](https://www.free-work.com/fr/tech-it/job-mission/developpeur-python/lfr-developpeur-python-django-en-remote-2029) |

### Ce que dit le marché (03/11/2026)

- **Le télétravail complet pour un junior Python est rare** : sur HelloWork, le filtre
  « télétravail complet » + « python » ne donne que 4 offres en France, aucune junior ; France
  Travail n'en donne aucune. Sur environ 75 offres examinées, 2 seulement étaient à la fois
  junior et en full remote.
- **Salaires d'un développeur Python junior (0 à 2 ans), brut annuel** : 38 à 43 k€ à Paris,
  32 à 38 k€ dans les grandes villes, 30 à 35 k€ ailleurs
  ([baromètre Silkhom 2026](https://www.silkhom.com/les-salaires-informatique-et-electronique/)).
  Médiane des prétentions des juniors toutes technologies : 35 k€
  ([WeLoveDevs](https://welovedevs.com/fr/salaires/junior)).
- **Ce que j'en tire** : candidater tout de suite aux deux offres qui me correspondent, garder
  des alertes actives sur le full remote, et considérer l'hybride si le full remote ne donne
  rien d'ici trois mois.

---

## 4. Sources de veille technique

### Comment je choisis une source

Je garde une source si elle remplit **au moins quatre** de ces critères :

1. **Fiable** : documentation officielle, mainteneur du projet, organisme reconnu, ou auteur
   identifiable avec une expertise vérifiable.
2. **À jour** : date de publication visible et récente ; la version de Python ou de Django est
   précisée (un tutoriel Django 1.x m'induit en erreur).
3. **Pertinente** pour ma stack et mon objectif : Python back-end, web, API, tests, déploiement.
4. **Vérifiable** : le code fonctionne, les affirmations renvoient à des sources.
5. **Régulière** : publication suivie, ce qui justifie de s'y abonner.
6. **Reconnue par la communauté** : citée, partagée, discutée (AFPy, newsletters, GitHub).

**Je me méfie** des articles sans date, des contenus sponsorisés présentés comme neutres, et des
réponses de forum sans explication.

### Documentation officielle — la référence avant tout le reste

| Source | Pourquoi |
|---|---|
| [Documentation Python (FR)](https://docs.python.org/fr/3/) | Le langage, la bibliothèque standard, les nouveautés de chaque version |
| [PEP 8](https://peps.python.org/pep-0008/) | La convention de style que je vérifie avec flake8 |
| [Documentation Django (FR)](https://docs.djangoproject.com/fr/5.2/) | Version LTS que j'utilise sur OC Lettings |
| [Django REST Framework](https://www.django-rest-framework.org/) | Sérialiseurs, permissions, pagination |
| [Flask](https://flask.palletsprojects.com/) | Micro-framework de GÜDLFT |
| [SQLAlchemy](https://docs.sqlalchemy.org/) | ORM d'Epic Events |
| [pytest](https://docs.pytest.org/) | Fixtures, paramétrage, plugins |
| [Docker](https://docs.docker.com/) | Images, conteneurs, bonnes pratiques de Dockerfile |
| [GitHub Actions (FR)](https://docs.github.com/fr/actions) | Pipelines CI/CD |

### Actualité et tutoriels

| Source | Format | Pourquoi |
|---|---|---|
| [PyCoder's Weekly](https://pycoders.com/) | Newsletter hebdomadaire | La sélection de la semaine en Python : articles, projets, Django inclus |
| [Real Python](https://realpython.com/) | Tutoriels | Tutoriels approfondis, de débutant à avancé |
| [Docstring](https://www.youtube.com/@Docstring) | Chaîne YouTube | Python et Django en français : tutoriels et bonnes pratiques |
| [Vision IA](https://www.youtube.com/@visionia-fr) | Chaîne YouTube | Veille sur l'intelligence artificielle, en français |

### Sécurité

| Source | Pourquoi |
|---|---|
| [OWASP Top 10](https://owasp.org/www-project-top-ten/) | Les 10 risques majeurs des applications web, appliqués sur SoftDesk et Epic Events |

### Portfolio

| Source | Pourquoi |
|---|---|
| [Developer portfolios](https://github.com/emmabostian/developer-portfolios) | Exemples de portfolios de développeurs |

---

## 5. Journal de progression

| Période | Projet | Ce que j'ai appris |
|---|---|---|
| Nov.–déc. 2025 | **Books to Scrape** | Scraping avec `requests` et BeautifulSoup, pipeline ETL, export CSV |
| Déc. 2025–janv. 2026 | **Cahier des charges** | Analyse d'un besoin client, user stories, backlog produit |
| Janv.–mars 2026 | **Chess Tournament Manager** | Programmation orientée objet, architecture MVC, persistance JSON, PEP 8 et flake8 |
| Mars–avril 2026 | **JustStreamIt** | JavaScript, appels d'API REST avec `fetch`, HTML/CSS responsive, validation W3C |
| Avril–mai 2026 | **AlgoInvest** | Force brute contre programmation dynamique (problème du sac à dos), complexité algorithmique |
| Mai–juin 2026 | **LITReview** | Django : modèles, vues, templates, authentification, modèle utilisateur personnalisé |
| Juin–juil. 2026 | **SoftDesk** | API REST avec DRF, JWT, permissions, OWASP, RGPD, pagination |
| Août 2026 | **GÜDLFT** | Tests unitaires, d'intégration et fonctionnels, couverture à 100 %, tests de charge Locust, débogage |
| Sept.–oct. 2026 | **Epic Events CRM** | SQLAlchemy et PostgreSQL, hachage Argon2, JWT, moindre privilège, journalisation Sentry |
| Oct.–nov. 2026 | **OC Lettings** | Django modulaire, migrations sans perte de données, Docker, GitHub Actions, Render, Sphinx |
