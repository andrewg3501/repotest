to make a repo
go to github.com
click new repository then name it repotest
open the ide
cd (switches you to the directory you specify) into github-learning
mkdir (makes a new folder named repotest) repotest
cd (switches you to that repository) repotest
git init (initializes it)
touch README.md (makes a file called README.md)
c9 README.md (opens the README.md file)
add some text in README.md like whatever you want
git add README.md (adds it to a list of changes you made)
git commit -m "added text in README.md" (tells github you made changes with a message given with it with the things you changed in quotation marks)
git remote add origin git@github.com:andrewg3501/repotest.git (makes ide link the github url with the ide to locally save it)
git push -u origin master (adds the changes made to it to the actual repository on the github)