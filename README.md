echo "# hello-github-actions" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/christsax/hello-github-actions.git
git push -u origin main
