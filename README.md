# 🎬 Gestionnaire d'Épisodes

Ce projet est une application web permettant de gérer les épisodes vus d'une ou plusieurs séries. Il fonctionne **directement dans le navigateur**, sans base de données, et **stocke les données de manière chiffrée**.

## 🔐 Fonctionnalités principales

- ✅ Créer une nouvelle série
- ➕ Ajouter des épisodes avec :
  - Numéro de saison
  - Numéro d'épisode
  - Date de visionnage
  - Note ou commentaire
- 🔍 Rechercher des épisodes par saison
- 🗑️ Supprimer un épisode ou une série complète
- 👁️ Afficher tous les épisodes d'une série
- 📥 Importer un fichier JSON chiffré
- 📤 Exporter les données de toutes les séries dans un fichier chiffré
- 🔑 Utilise **AES (CryptoJS)** pour le chiffrement/déchiffrement

## 🧠 Données sécurisées

Toutes les données sont chiffrées avec AES et protégées par une clé générée automatiquement à l’ouverture. Cette clé est sauvegardée avec les données lors de l’export et nécessaire pour la lecture après importation.

## 🚀 Mise en ligne sur GitHub Pages

### 1. Cloner ou créer un dépôt

```bash
git clone https://github.com/terencap789/gestionnaire-episodes.git
cd gestionnaire-episodes
