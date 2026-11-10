<p align="center">
  <img src="images/logo.png" width="140" alt="IHECTHEQUE Logo">
</p>

<h1 align="center">IHECTHEQUE – Application de gestion de bibliothèque</h1>

<p align="center">
  <b>Projet universitaire en équipe • C# .NET (Windows Forms) • SQL Server • Figma</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white" alt="C#">
  <img src="https://img.shields.io/badge/.NET-512BD4" alt=".NET">
  <img src="https://img.shields.io/badge/SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
  <img src="https://img.shields.io/badge/Figma-F24E1E?logo=figma&logoColor=white" alt="Figma">
</p>

---

## Présentation du projet
IHECTHEQUE est une application de bureau de gestion de bibliothèque conçue pour l'IHEC Carthage. Elle permet aux étudiants, aux bibliothécaires et aux administrateurs de consulter, gérer et suivre les emprunts de livres.

Projet réalisé en 2025 par une équipe de quatre étudiantes (équipe **Sharp#Sisters**). Chaque membre a participé à toutes les étapes : maquettes, base de données et développement.

---

## Démarche
1. **Maquettes sur Figma** : conception de l'interface pour chaque profil (étudiant, bibliothécaire, administrateur).
2. **Base de données SQL Server** : tables principales (Livres, Utilisateurs, Emprunts) et import des données initiales depuis un fichier Excel.
3. **Développement en C# .NET** : application connectée à la base SQL Server.

---

## Fonctionnalités
L'application propose trois espaces, selon le rôle de l'utilisateur à la connexion :

- **Étudiant** : consultation et recherche des livres disponibles, suivi de ses emprunts, liste de favoris et statistiques personnelles de lecture
- **Bibliothécaire** : gestion des livres (ajout, modification, suppression), gestion des emprunts et des retours, gestion des utilisateurs et tableau de bord
- **Administrateur** : gestion des utilisateurs, des livres et des événements, tableau de bord global et paramètres

Toutes les données sont lues et enregistrées dans la base SQL Server, avec des requêtes paramétrées.

---

## Aperçu de l'interface

### Authentification et accueil
<p align="center">
  <img src="images/login.png" width="300" alt="Connexion">
  <img src="images/acceuil.png" width="300" alt="Accueil">
</p>

### Espaces utilisateurs
<p align="center">
  <img src="images/espace%20admin.png" width="260" alt="Espace administrateur">
  <img src="images/espace%20bibliothecaire.png" width="260" alt="Espace bibliothécaire">
  <img src="images/espace%20d%20etudiant.png" width="260" alt="Espace étudiant">
</p>

### Livres disponibles
<p align="center">
  <img src="images/livres%20disponibles.png" width="400" alt="Livres disponibles">
</p>

---

## Technologies utilisées
- C# / .NET Framework 4.7.2 – Windows Forms (Visual Studio)
- SQL Server
- Figma (maquettes)

---

## Structure du projet
- `IHECTHEQUE.sln` : solution Visual Studio
- `IHECTHEQUE/` : code source C# (Windows Forms : formulaires `Form*` et contrôles utilisateur `UC*` pour chaque espace)
- `IHECTHEQUE/Resources/` : images et icônes de l'interface
- `Présentation Projet IHECTHEQUE.pdf` : présentation du projet (maquettes, base de données, développement)

---

## Lancer le projet
Prérequis : Windows, Visual Studio, .NET Framework 4.7.2 et SQL Server Express avec une base `GestionBibliotheque`.

1. Ouvrir `IHECTHEQUE.sln` dans Visual Studio.
2. Vérifier la chaîne de connexion dans `Database.cs` et `DB.cs` (par défaut : `.\SQLEXPRESS`).
3. Lancer le projet avec **F5**.

---

<p align="center">
  <i>Dépôt destiné à la présentation du projet dans un cadre académique (portfolio).</i>
</p>
