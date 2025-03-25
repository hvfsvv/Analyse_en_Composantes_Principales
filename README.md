#  PCA Lab – Analyse en Composantes Principales

Ce dépôt contient un notebook Python (`Lab_PCA_Notebook.ipynb`) qui implémente **pas à pas** l'algorithme de l'Analyse en Composantes Principales (ACP ou PCA), sans utiliser de librairies de machine learning.

---

## Contenu

-`Lab_PCA_Notebook.ipynb` – Notebook principal
- `data_pca.txt` – Jeu de données utilisé dans le lab (à ajouter)
- Visualisations : projection des données, reconstruction, vecteurs propres

---

##  Objectif du Lab

- Centrer les données
- Calculer manuellement la matrice de covariance
- Extraire les vecteurs/vecteurs propres
- Réduire la dimension à 1D
- Reconstruire les données dans l’espace d’origine
- Visualiser la compression et la perte d'information

---

##  Utilisation

### 1. Cloner le dépôt

```bash
git clone https://github.com/votre-utilisateur/pca-lab.git
cd pca-lab
```

### 2. Ouvrir le notebook

Lancer Jupyter Notebook ou VSCode et ouvrir `Lab_PCA_Notebook.ipynb`.

### 3. Ajouter le fichier de données

Assurez-vous d’avoir un fichier `data_pca.txt` dans le même dossier (format : deux colonnes numériques).

---

## Résultats attendus

- Représentation graphique des données centrées et projetées
- Reconstruction visuelle des données originales
- Identification de la direction principale `u₁`


## Concepts clés

- `X̃` : données centrées  
- `Ỹ` : projection des données dans l’espace réduit  
- `X̂` : reconstruction des données  
- `U_P` : matrice des vecteurs propres

---

Projet réalisé dans le cadre d’un TP sur l’Analyse en Composantes Principales.
