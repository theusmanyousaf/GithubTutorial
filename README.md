"# GithubTutorial"

#this Project is about uploading our local repository on github, Follow the command below in your local project terminal.

echo "# GithubTutorial" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/theusmanyousaf/GithubTutorial.git  // this should be the link of your own  github repository
git push -u origin main
