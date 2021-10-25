# model-react
model react from create-react-app
# Exemple : après avoir cloné un projet dans le dossier mon-projet/

# direction le dossier du challenge
cd mon-projet

# copie des fichiers cachés et non-cachés présents à la racine du modèle
# note : des alertes sont affichées à propos de dossiers ignorés, c'est normal
cp -n ../model-react/{.*,*} .

# copie (récursive) des dossiers src/, config/ et public/
# note : des alertes sont affichées à propos de dossiers ignorés, c'est normal
cp -rn ../model-react/{src,config,public} .

# installation des dépendances listées dans le package.json
npm i

# lancement du serveur de dev
mpm start
