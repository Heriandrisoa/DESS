---
tags:
---
# contexte
l'objectif est de developer une application sur JEE pour gérer: 
- les emplois du temps de tous les jours : cours, enseignement, salle  etc.. par parcours et niveau
- les emplois du temps des examens: quand, ou, ...
- les résultats et notes qui résultent de chaque examen
- les inscriptions du prochain trimestre selon les notes

# analyse existant
- base de donnée des profs, étudiants et les donnée des UE de chaque parcours.

# analyse des besoins du projets
## user stories
**Entant qu'étudiants**:
- je veux pouvoir me connecter a la plateforme (OAuth a 2 facteurs)
- je veux pouvoir consulter les emplois du temps de mon parcours
- je veux pouvoir être notifiée par mail si il y a des changements dans mon emploie du temps et avoir la nouvelle version
- être alertée quand un examen approche a moins de 2 semaines
- je veux pouvoir être notifié quand les résultats d'un examen sont disponible
- je veux être le seul a pouvoir consulter mes résultats sur un examen donnée.

**Entant qu'Enseignant**:
- je veux pouvoir me connecter
- je veux pouvoir consulter les créneaux libres par rapport a un parcours donnée.
- je veux pouvoir réserver un créneaux sur l'emploie du temps d'un parcours donnée, ou résilier un créneaux.
- je veux pouvoir définir une période ou je serais absent.
- je veux pouvoir définir la date ou je ferais passer mon examen (?)
- je veux pouvoir recevoir par email le sheet pour mettre les résultats de mon examen
- je veux pouvoir importer les notes attribuée par rapport a un examen
- je veux pouvoir définir la date de rattrapage

**Entant qu'administrateur:**
- je veux pouvoir gérer les salles
- je veux pouvoir gérer les utilisateurs
- je veux pouvoir avoir un dashboard des activité globale
# technologie
- **BACKEND**: JEE, Maven
- **FRONTEND**: JSTL
- **SERVEUR D'APPLICATION**: TOMCAT ou JBOSS
- **DB**: Postgresql
# SI
# architecture
- [ ] use case diagram
- [ ] Sequence diagram
- [ ] class diagram
- [ ] activity diagram

# maquette
- [ ] design thinking
- [ ] wireframe
- [ ] maquette design (minimale)
- [ ] dev
