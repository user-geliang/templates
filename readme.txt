git init
git lfs install
git add .gitattributes

git lfs track *
git add *
git commit -m "jenkins"
git pull --rebase origin main
git branch -m master main
git push origin main