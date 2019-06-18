# banano-developer-training

find . -exec touch {} \;
rm -rf .git;
git init;
git add .;
git commit -m "Initial commit";
git remote add origin https://github.com/coranos/banano-developer-training.git;
git push -u --force origin master;
git pull;git push;
