# ほげほげ


  git config --global user.email "magic.rinn@gmail.com"
  git config --global user.name "marinal-git"


echo "# ほげほげ" >> hoge.md
git init
git add hoge.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/marinal-git/dojo.git
git push -u origin main


echo "# ほげほげ" >> hoge.md
git add hoge.md

git commit -m "first commit"
git push -u origin main