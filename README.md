# yak-app-
Application YAK (Yougou And Kehou) 
# 1) dézippe et place les dossiers /api et /site dans un dossier yak-repo-local
cd ~/Downloads
unzip yak-api-complete.zip -d yak-local
unzip yak-web-prototype.zip -d yak-local

# 2) initialiser git et pousser vers ton repo GitHub
cd yak-local
git init
git add .
git commit -m "Initial commit YAK (api + site)"
git branch -M main
git remote add origin https://github.com/ledoude369-afk/yak-app-.git
git push -u origin main
