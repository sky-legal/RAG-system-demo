# 📌 RAG-demo

Ce projet met en place un **système de recherche et de génération augmentée par récupération (RAG)** basé sur **FAISS** et **OpenAI**. Il permet d’indexer un texte, de rechercher les passages les plus pertinents et de générer une réponse automatique.

## 🚀 Fonctionnalités
- **1️⃣ Génération d'Embeddings** : Extraction et vectorisation du texte (`texte-nettoye.txt`) avec `SentenceTransformer`.
- **2️⃣ Indexation FAISS** : Stockage des embeddings dans un index FAISS (`faiss_index.bin`) pour une recherche rapide.
- **3️⃣ Recherche de Similarité** : Identification des passages les plus proches d'une requête utilisateur.
- **4️⃣ Génération de Réponse** : Utilisation d'OpenAI (`gpt-3.5-turbo`) pour produire une réponse basée sur le contexte trouvé.

## 📂 Fichiers
- **`RAG-demo.ipynb`** : Notebook principal contenant l’ensemble des étapes du pipeline.
- **`texte-nettoye.txt`** : Fichier texte source utilisé pour l’indexation.
- **`embeddings.csv`** : Fichier contenant les embeddings générés.

## 🛠️ Installation et Utilisation
1. **Cloner le repo**  
   ```bash
   git clone https://github.com/ton-repo/RAG-demo.git
   cd RAG-demo
