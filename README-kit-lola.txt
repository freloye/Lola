KIT GITHUB PAGES – LOLA

Dépose ces fichiers à la racine du dépôt GitHub :
- index.html
- chanson-lola.mp3
- tete-lola.jpg

Ensuite :
1. Repo public
2. Settings > Pages
3. Deploy from a branch
4. Branch: main / root
5. Attendre 1 à 2 minutes

Adresse finale probable :
https://freloye.github.io/NOM-DU-DEPOT/

Si tu renommes la photo ou le mp3, modifie dans index.html :
const AUDIO_FILE = "chanson-lola.mp3";
const COVER_FILE = "tete-lola.jpg";
