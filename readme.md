conneting remote repo using git hub
echo "# DemoProject" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Jeevan49dev/DemoProject.git
git push -u origin main
