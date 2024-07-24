# File Upload React FastAPI

## Description

Ce projet est une application web fullstack pour télécharger et gérer des fichiers. Le frontend est développé avec React et Tailwind CSS, tandis que le backend est développé avec FastAPI. Les utilisateurs peuvent s'inscrire, se connecter, télécharger des fichiers et voir leurs fichiers précédemment téléchargés.

## Installation

### Prérequis

- Python 3.7+
- Node.js 14+

### Backend

1. Cloner le dépôt.
2. Aller dans le dossier `backend`.
3. Créer un environnement virtuel et activer-le :
    ```sh
    python -m venv venv
    source venv/bin/activate  # Sur Windows utilisez `venv\Scripts\activate`
    ```
4. Installer les dépendances :
    ```sh
    pip install -r requirements.txt
    ```
5. Lancer le serveur :
    ```sh
    uvicorn app.main:app --reload
    ```

### Frontend

1. Aller dans le dossier `frontend`.
2. Installer les dépendances :
    ```sh
    npm install
    ```
3. Lancer l'application :
    ```sh
    npm start
    ```

### Utilisation

1. Ouvrez votre navigateur et allez à `http://localhost:3000`.
2. Inscrivez-vous ou connectez-vous pour accéder au tableau de bord.
3. Téléchargez vos fichiers et visualisez ceux déjà téléchargés.

## Auteur

Développé avec ❤️ par @*Walter KRIS*
