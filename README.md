// to get the latest changes from the main
git fetch --all

// to create a new brach 
1. Click on the left bottom corner that shows the branch names (main)
2. That open a context menue
3. select create a new branch from...
4. enter Dev (name of the branch you would like to create)
5. Then it asks from with branch, enter main

// Apply your code modifications.

1. (on your Dev branch)$ git merge main 
(resolve if any merge conflicts)
2. git checkout main
3. git merge Dev (development branch)

1. git checkout main
2. git pull origin/main
3. git merge main
4. git push origin/main