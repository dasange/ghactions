# ghactions

gh auth login --with-token < .token  # for authentication ; 
git config -e  #  to verify the github configuration 

git remote show origin # to see the url set if it is https then change it with following command ; 
git remote set-url origin git+ssh://git@github.com/username/reponame.git # examples
git remote set-url origin git@github.com/dasange/ghactions.git # 
