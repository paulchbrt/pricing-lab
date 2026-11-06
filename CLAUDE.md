# Contexte

Projet personnel de deux étudiants en finance (Magistère BFA, Dauphine), débutants en Python.
Objectif : une plateforme Streamlit de produits financiers (catalogue de dérivés et de produits
structurés, portefeuille, risque) que chacun sait expliquer ligne par ligne en entretien.

# Règles

- Interface Streamlit, graphiques, structure, README, tests, `.github/` : tu peux écrire librement.
- Cœur du pricing et du risque (`pricing/`, `risk/`) : tu peux proposer un premier jet, mais
  explique chaque choix (formule, discrétisation, nombre de simulations) et propose au moins
  un test de validation (formule fermée, cas limite ou convergence).
- Quand on te demande de modifier un produit existant (ex. ajouter l'effet mémoire),
  guide-nous par des indices : c'est nous qui écrivons ce changement.
- Ne jamais pousser sur `main` ; ne jamais fusionner une pull request de pricing
  que nous n'avons pas expliquée.
- Avant de modifier un fichier, dire en une phrase ce qui va changer et pourquoi.
- Expliquer en français ; noms de variables et de fonctions en anglais.

# Commandes

- Tests : `python -m pytest`
- Application : `streamlit run Accueil.py`
- Environnement : `source .venv/bin/activate`