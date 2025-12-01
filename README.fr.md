## Kit à Planter (Stage chez Terrasse des Oliviers)

> **⚠️ Note :** Ce projet a été réalisé dans un cadre professionnel. Le code source est la propriété exclusive de l'entreprise et ne peut être divulgué. Ce document présente une étude de cas technique de ma contribution.

**Description**
Dans le cadre de la transformation numérique de la société *Terrasse des Oliviers*, j'ai participé au développement de "Kit à Planter" (KAP), un configurateur web 3D permettant aux utilisateurs d'aménager leur terrasse avec des modules végétalisés. L'application repose sur une architecture moderne séparant le Front-end (Next.js) du Back-end (Node.js).

**Stack Technique**
* **Back-end :** Node.js, Express.js
* **Base de données :** PostgreSQL (via l'ORM Prisma)
* **Tests & Qualité :** Jest, Supertest (**100% de couverture de tests**)
* **Outils :** JWT (Auth), Multer/Sharp (Gestion d'images), jsPDF (Génération de documents), GitHub Actions (CI/CD)

**Missions & Fonctionnalités Clés**
Mon rôle s'est concentré sur l'architecture et le développement de l'API REST :
* **Authentification & Sécurité :** Mise en place de routes sécurisées avec gestion des rôles via JWT.
* **Architecture Modulaire :** Structuration du code en contrôleurs, services et middlewares pour assurer la maintenabilité.
* **CRUD Complexe :** Gestion complète des entités (Plantes, Pots, Collections) et des sauvegardes de configurations utilisateurs.
* **Génération de Documents :** Création automatisée de devis et factures au format PDF via `jsPDF`.
* **Intégration Legacy :** Connexion et synchronisation de l'API avec le Back-office PHP existant de l'entreprise.


---

### Retour d'expérience technique

**Défis rencontrés**
* **Fiabilité du code :** L'un des enjeux majeurs était la stabilité de l'API avant la mise en production. J'ai relevé le défi d'écrire des tests unitaires et d'intégration complets avec Jest et Supertest, atteignant une couverture de code de 100 %.
* **Interopérabilité :** Faire communiquer la nouvelle stack Node.js avec l'ancien système en PHP a demandé une conception rigoureuse des échanges de données.

**Acquis**
* Maîtrise d'une architecture professionnelle en production.
* Collaboration en méthodologie Agile avec une équipe Front-end.
* Importance des tests automatisés dans un projet d'envergure.
