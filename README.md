# Spotimax - le streamer musical

## Introduction

Projet de clone d'un lecteur de musique en ligne avec RapidAPI pour Shazam et la Géolocalisation.

[Spotimax](https://machina-project-spotimax.vercel.app/)

## Installation

- Télécharger le projet : 
	```bash
	git clone git@github.com:MachinaDev/machina-project-spotimax.git && cd machina-project-spotimax
	```
### Lancer le site

1. Utiliser la version de NodeJS <=16
2. Créer un fichier `.env` à la racine du dossier et récupérer vos clés API dans votre compte RapidAPI.

	```
	// https://rapidapi.com/tipsters/api/shazam-core
	VITE_SHAZAM_CORE_RAPID_API_KEY=22a0280bc1msh82caec7c56ea4d8p1a5933jsn6cb53af677ef

	// https://geo.ipify.org/docs
	VITE_GEO_API_KEY=at_Q04ILcVX7MHYzTztRZDvl4HLyoBEE
	```

3. Lancer le site avec la commande suivante
	```bash
	npm i && npm run dev
	```