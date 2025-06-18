# 👗 Fashion-Insta - Cadrage Projet IA Mobile de Recommandation

**Projet 10 – Mastère Spécialisé Data Science – OpenClassrooms**  
**Client : Fashion-Insta (Entreprise du monde de la mode)**  
**Rôle : IA product manager**

---

## 🎯 Objectifs du Projet

En tant qu'IA Product Manager au sein de **Fashion-Insta**, entreprise spécialisée dans la commercialisation d'articles vestimentaires via ses magasins physiques et son site e-commerce, j'ai mené le cadrage complet d'une application mobile innovante de recommandation d'articles vestimentaires basée sur l'analyse d'images.

### Objectif Principal
Développer une **application mobile de recommandation d'articles vestimentaires** permettant aux utilisateurs de :
- Se prendre en photo avec leurs vêtements favoris
- Obtenir des recommandations d'articles du même style vestimentaire
- Bénéficier d'une approche de recommandation basée sur leurs préférences personnelles

### Objectifs Business
- **Augmentation des ventes** grâce à des recommandations précises et personnalisées
- **Fidélisation client** à long terme
- **Croissance du CA** : +82 000€ la première année, puis +45% supplémentaire chaque année (estimation)

---

## 💼 Missions Réalisées

1. **Formalisation du backlog** avec user stories priorisées
2. **Dimensionnement complet** de l'équipe, des coûts et des gains
3. **Planification des sprints** selon la méthologie Agile/Scrum
4. **Analyse des risques** et mise en place du plan d'action de mitigation
5. **Intégration des enjeux légaux et éthiques** (RGPD, biais IA, etc.)

---

## 🏗️ Architecture et Ressources

### Équipe Projet
- **Product Owner** : Définition et priorisation du backlog
- **Scrum Master** : Animation et facilitation de l'équipe
- **Data Scientist Junior** : Architecture ML et modèles de recommandation
- **Développeur** : Application iOS/Android; API et services backend
- **MLOps/DevOps Engineer** : Infrastructure et déploiement
- **Testeur** : Tests fonctionnels et non-fonctionnels
- **UX Designer** : Conception de l'expérience utilisateur pour l'app mobile
- **Database Admin** : Gestion et optimisation des bases de données

### Stack Technique - Solution Azure Cloud

#### Services Azure Utilisés

| **Catégorie** | **Service Azure** | **Nom Custom** | **Région** | **Description** |
|---------------|-------------------|----------------|------------|-----------------|
| **Calcul** | Virtual Machines | | France Central | 1 A0 (1 Core, 0.75 GB) |
| **Calcul** | Azure Kubernetes Service | | France Central | Standard - Gestion orchestration conteneurs |
| **DevOps** | Azure Monitor | | France Central | Log analytics - Monitoring application |
| **Stockage** | Storage Accounts | | France Central | Redondance - Stockage images et modèles |
| **Bases de données** | Azure SQL Database | | France Central | Base de données relationnelle |
| **Outils de développement** | Azure DevOps | | | 0 utilisateurs - CI/CD Pipeline |
| **IA/ML** | Azure Machine Learning | | France Central | Développement et déploiement modèles IA |
| **IA/ML** | Azure Cognitive Services | | France Central | Vision par ordinateur et analyse d'images |
| **Applications** | Azure App Service | | France Central | Hébergement API backend |
| **Support** | Support Azure | | | Support technique Azure |

### Coûts et Investissement

#### Développement Initial
- **Équipe projet** : Coûts journaliers par profil définis
- **Infrastructure Azure** : Estimation mensuelle des services cloud
- **Développement** : 3 mois de développement en sprints de 2 à 4 semaines

#### Modèle de Rentabilité
- **ROI première année** : +82 000€
- **Croissance annuelle** : +45% par an
- **Coûts de maintenance** : Budget annuel pour évolutions et support

---

## 🏃‍♂️ Méthodologie Agile - Framework Scrum

### Principes Agile Appliqués
- **Travail itératif** : Sprints de 2 à 4 semaines
- **Livraisons fréquentes** : Version fonctionnelle à chaque sprint
- **Réactivité au changement** : Adaptation continue selon les retours
- **Collaboration** : Forte implication des parties prenantes

### Rituels Scrum
- **Daily Scrum** : Point quotidien de synchronisation
- **Sprint Planning** : Planification des tâches du sprint
- **Sprint Review** : Démonstration des fonctionnalités développées
- **Sprint Retrospective** : Amélioration continue des processus
- **Burndown Chart** : Suivi visuel de l'avancement

### Livrables Sprint
- **Sprint Backlog** : Tâches sélectionnées pour le sprint
- **Objectif de sprint** clair et mesurable
- **Plan de travail** initial et adaptatif

---

## ⚖️ Enjeux Légaux et Éthiques

### Conformité RGPD
- **Finalité claire** : Collecte de données pour recommandation uniquement
- **Minimisation** : Collecte des données strictement nécessaires
- **Consentement éclairé** : Information et accord explicite des utilisateurs
- **Transparence** : Communication claire sur l'utilisation des données
- **Droits utilisateurs** : Accès, modification, suppression des données
- **Sécurité** : Protection contre les accès non autorisés
- **Limitation de durée** : Purge automatique après inactivité

### Registre des Traitements CNIL
- **Traitement IA** documenté selon les exigences réglementaires
- **Finalités** et **bases légales** clairement définies
- **Mesures de sécurité** techniques et organisationnelles

### Enjeux Éthiques IA
- **Biais des modèles** : Vérification diversité des données, analyse et correction des biais
- **Surveillance et vie privée** : Communication transparente + possibilité de désinscription
- **Manipulation comportementale** : Système transparent respectant le libre arbitre

---

## 🚨 Gestion des Risques

### Risques Techniques
1. **Compétences Data Scientist Junior**
   - *Risque* : Modèles de qualité inférieure
   - *Prévention* : Formation continue
   - *Correction* : Consultation d'experts externes

2. **Délais contraints**
   - *Risque* : Compromission sur la qualité
   - *Prévention* : Révision des délais, communication claire
   - *Correction* : Révision du planning, réévaluation des priorités

### Risques Organisationnels
3. **Développeurs multi-projets**
   - *Risque* : Ralentissement du développement
   - *Prévention* : Priorisation, recours aux freelances
   - *Correction* : Externalisation de certaines tâches

### Risques Légaux/Conformité
4. **Données personnelles sensibles**
   - *Risque* : Violation de sécurité des données
   - *Prévention* : Notification aux autorités, mesures de sécurité renforcées
   - *Correction* : Transparence et communication

5. **Non-conformité RGPD**
   - *Risque* : Sanctions réglementaires
   - *Prévention* : Mise en conformité continue
   - *Correction* : Correction immédiate des non-conformités

---

## 📊 Livrables du Projet

### 1. Product Backlog
- **User stories** complètes et priorisées
- **Critères d'acceptation** détaillés
- **Story points** pour l'estimation
- **Epic** et thématiques fonctionnelles

### 2. Dimensionnement Projet
- **Chiffrage détaillé** par profil et phase
- **Estimation de rentabilité** sur 3 ans
- **Coûts d'infrastructure** Azure
- **Planning de facturation** et investissement

### 3. Registre CNIL
- **Traitement IA** pour la recommandation
- **Finalités** et bases légales
- **Données collectées** et durée de conservation
- **Mesures de sécurité** techniques

### 4. Analyse des Risques
- **Identification** complète des risques
- **Évaluation** impact/probabilité
- **Plans d'action** préventifs et correctifs
- **Responsables** et échéances

---

## 🎯 Compétences Développées

- **Analyse des besoins métier** et formalisation en user stories
- **Dimensionnement projet** : ressources humaines, techniques, financières
- **Gestion des risques** inhérents aux projets IA et données personnelles
- **Intégration des contraintes légales** et éthiques (RGPD, biais IA)
- **Pilotage de projet** avec planification des sprints Agile

---

## 📈 Résultats Attendus

### Impact Business
- **Amélioration de l'expérience client** avec des recommandations personnalisées
- **Augmentation du panier moyen** grâce aux suggestions pertinentes
- **Fidélisation accrue** via une approche omnicanale innovante
- **Différenciation concurrentielle** par l'innovation IA

### Impact Technique
- **Architecture scalable** prête pour la croissance
- **Modèles IA performants** pour la recommandation vestimentaire
- **Infrastructure cloud** optimisée et sécurisée
- **Processus de développement** agile et efficient

## 📞 Contact

**Maodo FALL**  
*Data Scientist*

---

*Ce projet démontre une approche complète de cadrage d'un projet IA, intégrant les dimensions business, technique, légale et éthique nécessaires au succès d'une application mobile de recommandation dans l'industrie de la mode.*
