# How to Use Git

### first step (no repository) 
1. git init (initialize project)
2. git add . (Add all files or folders in the project)
   git add file_name (add specific file_name) 
3. git status (check files or folders that will be committed) 
4. git commit -m "something..."
5. git remote add origin repository(create in GitHub)
6. git push -u origin main/master(default branch)

### already has a repository
1. git add . 
2. git commit -m "message" 
3. git push origin main/master

### clone project 
1. git clone https://github.com/sros-pheaktra/mini-project.git

### pull and checkout the branch (already created the  branch in GitHub)
1. git branch (check the current branch that you are on) 
   git branch -a (check all existing branches in that repo)

==> if you don't stay on the right branch 
   1. git checkout the_branch_that_you_want_to_stay
   2. git pull origin  the_branch_that_you_want_to_stay
