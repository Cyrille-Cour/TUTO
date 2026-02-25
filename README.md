# TUTORIEL LANCEMENT DIVERSE APP/FRAMEWORKS & BONNES PRATIQUES

# GITHUB
<h2> Dès que je démarre VSC pour travailler </h2>
-   git pull
<h2>Dès que j'ai fini et que je veux envoyer</h2>
- git add . (ne pas oublier le point) <br>
- git commit -m "votre message" <br>
- git push <br>

# LARAGON-LARAVEL
<h2> Lancer une app laravel depuis Laragon </h2>
- Une fois fais sur VSC : <br>
1. npm install <br>
2. npm run dev <br>
IMPORTANT!! Tout quitter (stop all laragon > quitter) <br>
- relancer laragon <br>

# FASTAPI
<h2> Lancer un programme Python sur VSC </h2>
- Une fois sur VSC: <br>
1. python -m venv venv <br>
2. .\venv\Scripts\activate <br>
3. pip install "fastapi[standard]" <br>
4. fastapi dev main.py // remplacer main.py par le nom du fichier. <br>
5. deactivate pour arrêter le serveur. <br>

# DJANGO
<h2> Dans mon dossier Django créer un répertoire pour le projet</h2>
- Une fois sur VSC: <br>
1. python -m venv venv <br>
2. .\venv\Scripts\activate <br>
3. pip install django <br>
4. django-admin startproject nomduprojet . <br>
