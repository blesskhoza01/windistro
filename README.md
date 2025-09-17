unzip windistro_project_ready.zip -d windistro
cd windistro
git init
git branch -M main
git remote add origin https://github.com/<yourusername>/windistro.git
git add .
git commit -m "Initial Windistro project"
git push -u origin main
