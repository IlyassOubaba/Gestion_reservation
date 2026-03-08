# Gestion des Réservations

Application Java de gestion de réservations utilisant **Hibernate**, **JPA** et **Maven**.

---

##  Objectif du projet

Ce projet vise à implémenter un système complet de gestion de réservations (salles, ressources, rendez-vous, hôtels, événements, etc.) en utilisant les concepts avancés de persistance avec **Hibernate ORM** et **JPA**.

Il s'agit typiquement d'un exercice d'apprentissage / projet académique/professionnel pour maîtriser :
- Mapping objet-relationnel
- Relations complexes (OneToMany, ManyToMany, etc.)
- Gestion des transactions
- Requêtes JPQL / Criteria
- Validation et logique métier

---

##  Technologies utilisées

- **Java** (17.0.15)
- **Maven** (gestion des dépendances)
- **Hibernate** 
- **JPA** 
- **MySQL**

---

## Fonctionnalités principales

- Gestion des clients / utilisateurs
- Création, modification, annulation de réservations
- Vérification de disponibilité (conflits de dates)
- Consultation des réservations (par client, par période, par ressource)
- Gestion des ressources à réserver (salles de réunion, matériels, terrains, etc.)
- Historique et état des réservations (confirmée, en attente, annulée)


---

## Diagramme de classe

![Diagramme_de_Class_](https://github.com/user-attachments/assets/690517a4-482b-421b-b978-10dc8070f0c8)

---

## Video demo


https://github.com/user-attachments/assets/36f3caa1-bb67-4d0f-ac64-1c0b6945a9ee

---


## Conclusion

Ce projet de gestion de réservations est un excellent cas pratique pour consolider Hibernate/JPA dans un contexte métier concret et très demandé.
Même à l'état de base, il démontre une bonne maîtrise des entités, relations, transactions et requêtes — des compétences directement transférables dans le développement d'applications réelles (ERP, systèmes de booking, gestion d'événements...).
