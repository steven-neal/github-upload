echo "# github-upload" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/steven-neal/github-upload.git
git push -u origin master
