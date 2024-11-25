# Historique des commandes git bash

mkdir tp_mjito_archiweb
cd tp_mjito_archiweb
notepad recette_mojito.md

git init
git add recette_mojito.md
git commit -m "Premier ajout de la recette pour le mojito"
git push -u origin main

Notepad recette_mojito.md
git add recette_mojito.md
git commit -m "Ajout du reste de la recette"
git push -u origin main

Notepad recette_mojito.md
git add recette_mojito.md
git commit -m "La recette est maintenant pour 2 personnes"
git push -u origin main

Notepad recette_mojito.md
git add recette_mojito.md
git commit -m "Maintenant, c'est carrément une recette pour 10 personnes parce qu'ici on aime s'amuser !"
git push -u origin main

git checkout -b malade
Notepad recette_mojito.md
git add recette_mojito.md
git commit -m "Ajout d'une recette de mojito sans alcool pour les gens pas cool (en vrai faut pas tomber dans l'excès)"
git push origin malade

Notepad recette_mojito.md
git add recette_mojito.md
git commit -m "Cette fois-ci, c'est la recette du mojito sans alcool avec de l'eau plate"
git push origin malade

git checkout main
git checkout origin/main recette_mojito.md
git add recette_mojito.md
git commit -m "Finalement, on remets la recette pour 2 personnes"
git push origin main

git log
git status
