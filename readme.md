echo "# dop" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Anna-net28/dop.git
git push -u origin main
git add .
git commit -m "проект создан"
git diff --color-words
git push