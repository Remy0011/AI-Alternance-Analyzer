# AI-Alternance-Analyzer

AI Alternance Analyzer

Application web permettant d’analyser un CV et une offre d’alternance afin d’évaluer leur compatibilité et de générer des recommandations personnalisées.

Fonctionnalités
Import d’un CV au format PDF
Analyse automatique du contenu du CV
Analyse d’une offre d’alternance
Calcul d’un score de compatibilité entre le CV et l’offre
Identification des compétences correspondantes
Identification des compétences manquantes
Génération de conseils d’amélioration
Génération d’un message LinkedIn prêt à envoyer
Stack technique

Backend :

Python
FastAPI
OpenAI API
PyPDF

Frontend :

React (Vite)
Axios

Outils :

Docker
Docker Compose

Architecture
Frontend (React) → Backend (FastAPI) → OpenAI API

Installation
Cloner le projet

git clone https://github.com/Remy0011/ai-alternance-analyzer.git
cd ai-alternance-analyzer

Backend

cd backend
python -m venv venv

Activer l’environnement virtuel :

Windows :
venv\Scripts\activate

Mac / Linux :
source venv/bin/activate

Installer les dépendances :

pip install -r requirements.txt

Créer un fichier .env :

OPENAI_API_KEY=your_key_here

Lancer le serveur :

uvicorn app:app --reload

Le backend est accessible sur :
http://localhost:8000/docs

Frontend

cd frontend
npm install
npm run dev

L’application est accessible sur :
http://localhost:5173

Docker

Lancer l’ensemble du projet :

docker compose up --build

Sécurité
Les clés API sont stockées dans des variables d’environnement
Aucun CV n’est stocké sur le serveur
Validation des fichiers PDF uniquement
Taille des fichiers limitée
Séparation frontend / backend

Objectif du projet
Ce projet a été réalisé dans un contexte de recherche d’alternance en développement Full Stack.

Nom : Rémy DEIBER
GitHub : https://github.com/Remy0011
