hugo server --bind 0.0.0.0 --port 8080 --appendPort=false --liveReloadPort=443


echo "# audif-store" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/adschexp/audif-store.git
git push -u origin main