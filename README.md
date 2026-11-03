# Voici-fonix-
cd voici-fonix
git init
git add .
git commit -m "Voici-Fonix production build"
git branch -M main
git remote add origin https://github.com/Matthew_Lovinpeace/voici-fonix.git
git push -u origin main
npm install && npm run build
