#  Gestion Emprunt de Livres

Application mobile et serveur backend pour gérer les emprunts et la gestion de livres en bibliothèque.

##  Technologies utilisées

- **Frontend (Mobile App) :**
  - [React Native](https://reactnative.dev/)
  - [Expo Router](https://expo.github.io/router/)
  - [Axios](https://axios-http.com/)

- **Backend (API REST) :**
  - [Express.js](https://expressjs.com/)
  - [MySQL](https://www.mysql.com/)

- **Sécurité Mobile :**
  - [Expo SecureStore](https://docs.expo.dev/versions/latest/sdk/securestore/) (stockage sécurisé des tokens)

---

##  Fonctionnalités principales

- Authentification par email et mot de passe
- Connexion sécurisée avec token JWT
- Gestion des rôles : Admin / Utilisateur
- Tableau de bord admin :
  - Voir statistiques : livres, utilisateurs, emprunts
  - Ajouter, modifier et supprimer des livres
- Espace utilisateur :
  - Consulter la liste des livres
  - Emprunter et retourner un livre
- Déconnexion et gestion sécurisée des sessions

---

##  Installation rapide

### Backend (Express + MySQL)

```bash
cd server
npm install
npm run dev

## Configurez un fichier .env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=library_db
JWT_SECRET=your_jwt_secret

## Lancer Frontend (React Native)
cd gestion-emprunt-livres
npm install
npx expo start


