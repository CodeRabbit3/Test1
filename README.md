echo "# Test1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/CodeRabbit3/Test1.git
git push -u origin main
