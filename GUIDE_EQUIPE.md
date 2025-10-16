## Guide de travail – Projet GitHub
🔹 Structure du projet

test → branche de développement (tous les membres travaillent ici)

prod → branche de production (stable, protégée, gérée par le chef de projet)

🔹 Règles principales

 Ne jamais pousser sur prod directement.

 Travaillez uniquement sur test ou sur vos propres branches feature/....

 Les merges se font via des Pull Requests (PR) → toujours demander une validation avant la fusion.

 Le chef de projet gère le passage de test → prod.

🔹 Étapes dans la collaboration
# 1. Récupérer le projet
git clone https://github.com/Brahimi-Talla01/projet-groupe.git 
cd <projet-groupe> 

# 2. Se placer sur test
git checkout test
git pull

# 3. Créer sa branche
git checkout -b feature/ma-fonctionnalite

# 4. Travailler, puis pousser
git add .
git commit -m "Ajout de la fonctionnalité X"
git push -u origin feature/ma-fonctionnalite


Ensuite, ouvrir une Pull Request sur GitHub :
feature/ma-fonctionnalite → test
