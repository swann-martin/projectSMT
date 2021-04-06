
# Cahier des charges

1.  Contextualisation
2.  Problématique de communication
3.  Stratégie de communication
4.  Stratégies créatives
5.  La stratégie des moyens
6.  Budget
7.  Planning de réalisation
8.  Structure

# 1/ Contextualisation

## Concept

L'agence web MST spécialisée dans le développement de sites web a été mandatée par le client Webforce3 pour créer un site de générateur de CVs en ligne. Cette société est spécialisée dans la formation de développeurs. Les élèves sortant de cette formation ne disposent pas tous de CV numérique pour démontrer leurs compétences et postuler aux offres d'emploi. L'objectif est de mettre à la disposition des élèves, une plateforme où ils disposeront de templates de CVs personnalisables pour postuler facilement aux offres d'emploi.

Après s'être connecté sur la plateforme, l'utilisateur aura la possibilité de saisir ses informations personnelles (identité, hobbies, compétences, formations, savoir-être, savoir-faire...). Ces informations persisteront dans une base de donnée. Elles permettront de générer 3 propositions de CV qui seront accessibles via un short-url ou un QR-Code.

Au moyen d'une API de site de recherche d'emplois, le générateur de CV pourra, rechercher des postes sur le marché du travail, en adéquation avec le CV qui a été généré.

> Option :

- vérifier la corrélation via webScrapping
- service d'envoi par mail aux employeurs avec un template de lettre de motivation
- possibilité de récupperer le CV en pdf, de l'imprimer, de l'envoyer par email.

## Présentation de la concurrence

[Canva](https://www.canva.com/fr_fr/cv/modeles/) : création et design de CV, touche un public plutôt jeune CSP+. Propositions intéressantes pour la personnalisation du design. Plusieurs éléments gratuits, mais devient rapidement payant lorsqu'on souhaite plus de choix.

[cvTemplate](https://www.cv-template.com/fr) : création de CV en ligne : design moches, prix premium (cher!!!) pour hébergement

[doYouBuzz](https://www.doyoubuzz.com/fr/) : création et partage de CV sur le web directement en pdf.

[creeruncv](https://www.creeruncv.com/) : création de CV , bon prix (gratuit), variété des templates (assez beaux), pas d'hébergement.

Notre différenciation : Prix, design, fonctionnalités.

> Idées de nom de site : weResumeyouWork, MyBestCV, ResumeMe, HelloCV, HiCV, HiResume

## Mapping de la concurrence
![mapping-concurentiel](https://user-images.githubusercontent.com/71760899/113697062-03be4880-96d3-11eb-9c51-4f02fcef8a25.png)

<<<<<<< HEAD
=======

>>>>>>> a41dc28f648e4cfeaab787d7e03cc251935305e4
## Analyse SWOT

| Force / Strength              | Faiblesse / Weakness                 |
| ----------------------------- | ------------------------------------ |
| Design graphique contemporain | Hébergement limité                   |
| Approche UX                   | Templates limités                    |
| Simplicité d'utilisation      | Contrainte de temps                  |
| Hébérgement                   | Connexion moteur de recherche limité |
| Prix attractif (gratuit)      |                                      |

| Opportunités / Opportunities                          | Menaces / Threats                                        |
| ----------------------------------------------------- | -------------------------------------------------------- |
| Tendance à la dématérialisation des données           | Secteur concurrentiel                                    |
| Accès à distance aux données pour modification rapide | Plus de personnalisation chez concurrents                |
| Simplicité d'utilisation                              | Sécurisation des données                                 |
| Offre complète, prix, hébergement, clé en main        | Tarif des hébergeurs potentiellement dangereux pour nous |
|                                                       |                                                          |

# 2/ Problématique de communication

## Synthèse

Nos analyses ont permis de démontrer que les concurrents principaux ne proposent pas d'offres permettant à la fois un hébergement de CVs en ligne et des designs originaux à un prix attractif.

Comment faire connaître un site internet pour qu'il puisse permettre aux demandeurs d'emploi d'héberger en ligne, des CV qui soient attractifs pour les recruteurs ?

# 3/ Stratégie de communication

## Positionnement

Des mots importants : attractifs, accessible, simple, cloud.

## Objectifs

**Cognitifs:**
Développer la notoriété du site auprès des demandeurs d'emploi. En parler aux élèves de chaque session WF3 / conseillers pôle emploi

**Affectifs:**
Simple d'utilisation : design épuré
Sécurisé : choix du PHP et d'un framework au top de la sécurité
Fiable : choix du PHP et d'un framework au top de la sécurité

**Cognatif:**
Il y a 1 template par personne et spécialement pour les développeurs de la formation webforce3 il a 3 template.

## Cibles

**Cible principale :**
Toute personne cherchant un emploi désirant utiliser des solutions dématérialisées pour répondre aux offres. Solution facile et clé en main avec un design de CV fourni créé par un graphiste.

**Coeur de cible :**

Développeurs web qui doivent fournir lors de leur entretien d'embauche des solutions dématérialisées en rapport avec leur métier.

**Cible secondaire :**
Tous les recruteurs qui peuvent facilement consulter des viviers de CV en ligne.

# 4/ Stratégies créatives

## Promesses, preuves, tons et contraintes

**Notre promesse :** Postuler Made Great Again ! MST vous permet de postuler facilement aux offres d'emploi à l'aide de CV dématérialisés et personnalisables.

**Preuve :** La plateforme permettra en quelques clics d'accéder au moins à 1 templates de CV, de les personnaliser et de les poster aux recruteurs.

**Ton :** Le coeur de cible étant des développeurs web, nous avons déterminé qu'il était préférable d'adopter un ton smart-casual, dynamique, cordial, assez libre mais respectueux, un tutoiement poli.

**Contraintes :** La conservation des données, par l'utilisation de technologies sûres, se conformer aux contraintes de la législation (RGPD) et d'accessibilité (RGAA & SEO), choix du serveur pour la scallabilité et un nombre croissant d'utilisateurs.

# 5/ La stratégie des moyens

| Col1                               | Col2                                     | Col3                                                                                                                                                                                                                                                                                                                                                                                   |
| ---------------------------------- | ---------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **La structure web**               | **15 pages :**                           | page de connexion, page d'inscription, page de dashboard, page interface(modifications d'interfaces pour les CV partie édition : page hobbies, page fonction, page about, page expèrience pro, page formation, page image), page édition du profil de l'utilisateur (table user), page de visualisation d'exports (avec bouton download et envoyer), page rgpd, page FAQ, page CGV CGU |
| **La base de données**             | table user                               | id, email, lastName, firstName, avatar, streetAdress, postCode, city, phone, website, password.                                                                                                                                                                                                                                                                                        |
| **La base de données**             | table Xp                                 | id, jobDateFrom, jobDateTo, jobName, companyName, jobLocation, jobDescritpion, foreign key userId                                                                                                                                                                                                                                                                                      |
| **La base de données**             | table CV                                 | id, model, title, function, about, createdAt, updatedAt, shortUrl, foreign key userId                                                                                                                                                                                                                                                                                                  |
| **La base de données**             | table training                           | id, trainingDateFrom, trainingDateTo, diplomaName, schoolName, schoolLocation, diplomaDescritpion, foreign key userId                                                                                                                                                                                                                                                                  |
| **La base de données**             | table hobbies                            | id, icons, hobbiesName, foreign key userId                                                                                                                                                                                                                                                                                                                                             |
| **L'hébergement**                  | sécurisé                                 | serveur (Apache) Heroku, symfony Cloud, platform SH, php, mySQL / mariaDB                                                                                                                                                                                                                                                                                                              |
| **Référencement et accessibilité** | google friendly, normes d'accessibilités | Lightouse et respect des règles Opquast                                                                                                                                                                                                                                                                                                                                                |

# 6/ Budget

# 7/ Planning de réalisation

# 8/ Structure

## Identité visuelle

- Design
- Logo
- Charte graphique : typographie jost pour les titres en bold 800 italic, poppins pour les textes.

## Wireframe
