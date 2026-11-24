# Suivi des étudiants

Site web qui permet de consulter les notes, les absences et le taux de présence des étudiants, avec un espace pour l'étudiant, un pour l'enseignant et un pour l'administration.

Projet réalisé dans le cadre du module **Digital** (Git, Bash, GitHub).

**Auteur :** laith hamrouni rayen bouzidi iyed bouzidi

## Fonctionnalités

- **Espace étudiant** : en saisissant son matricule, l'étudiant voit sa moyenne, ses notes par module, ses absences, le nombre d'absences restantes et son taux de présence.
- **Espace enseignant** : ajout ou retrait d'absences et modification des notes par module.
- **Espace administration** : statistiques générales (moyenne de la classe, étudiants en difficulté), recherche par nom ou matricule et indication de la situation de chaque étudiant.

## Structure du projet

```
├── index.html        Page d'accueil
├── etudiant.html     Espace étudiant
├── enseignant.html   Espace enseignant
├── admin.html        Espace administration
├── css/style.css     Feuille de style commune
├── js/data.js        Données de démonstration et sauvegarde
└── README.md
```

## Utilisation

1. Cloner le dépôt :
   ```bash
   git clone https://github.com/VOTRE-COMPTE/premier-projet.git
   ```
2. Ouvrir `index.html` dans un navigateur (aucun serveur nécessaire).
3. Matricules de test : `2026001` et `2026002`.

## Limites

Les données sont des exemples (`js/data.js`). Les modifications faites par l'enseignant sont enregistrées dans le navigateur (`localStorage`), sans base de données ni authentification. Une version réelle nécessiterait un serveur et une base de données.

## Organisation avec Git

Le développement a été fait par branches, fusionnées dans `main` avec des pull requests :

- `page-etudiant` : structure du site et espace étudiant
- `page-enseignant` : espace enseignant
- `pages-admin-accueil` : accueil et administration
- `readme` : documentation# Suivi des étudiants
