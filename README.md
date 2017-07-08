welcome to git repository


…or create a new repository on the command line

echo "# LoginWebApp" >> README.md
git init       //to init the git, also ".git" file gets created.
git add README.md    //adding new file to the repository
git commit -m "first commit"    //commiting the changes to the local repository
git remote add origin https://github.com/Sidhurugi/LoginWebApp.git      //connecting to remote repository
git push -u origin master     //push the modified changes/new files to the repository.

…or push an existing repository from the command line

git remote add origin https://github.com/Sidhurugi/LoginWebApp.git
git push -u origin master

git pull /*to pull the modified files from the master repository, should be used before pushing to the reporsitory.
           also can be used to download the files from the master repository.*/
