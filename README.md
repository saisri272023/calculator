create a new repository on the command line
echo "calculator" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:saisri272023/calculator.git
git push -u origin main
