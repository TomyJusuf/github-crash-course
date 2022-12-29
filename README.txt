git init
git add <file(s)> /or/ git add . /or/ git add /subsection
git commit -m "...."
git status
git log /or/ git log --oneline
git checkout < ID >
git reverse < ID >
git reset --hard < ID >
git branch <name>
git branch -D <name of branch> (what we want delete localy)
git checkout -b <feature-section /or/ anyname> (<--create and auto-switch the new branch)
git merge <name of branch> (push out second subsection branch to out main/master branch)
git remote add "anyname" /or/ origin (and link like:https://github.com/TomyJusuf/github-crash-course.git)==connection with GihHub repository.

git push origin <name of branch> (for push on out GitHub repository ,and be live.)

git pull /or/ git push + 'the repo link from GitHug if that not work automaticly'