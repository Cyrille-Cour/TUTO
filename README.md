# TUTORIEL LANCEMENT DIVERSE APP/FRAMEWORKS & BONNES PRATIQUES

# GITHUB
<h2> Dès que je démarre VSC pour travailler </h2>
-   git pull
<h2>Dès que j'ai fini et que je veux envoyer</h2>
- git add . (ne pas oublier le point)
- git commit -m "votre message"
- git push

# LARAGON-LARAVEL
<h2> Lancer une app laravel depuis Laragon </h2>
- Une fois fais sur VSC :
1. npm install
2. npm run dev
IMPORTANT!! Tout quitter (stop all laragon > quitter)
- relancer laragon

# FASTAPI
<h2> Lancer un programme Python sur VSC </h2>
- Une fois sur VSC:
1. python -m venv venv
2. .\venv\Scripts\activate
3. pip install "fastapi[standard]"
4. fastapi dev main.py // remplacer main.py par le nom du fichier.
5. deactivate pour arrêter le serveur.
