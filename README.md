# How to Use Git

### first step (no repository) 
1. git init (initialize project)
2. git add . (add all files or folders in project)
   git add file_name (add specific file_name) 
3. git status (check files or folders which will be commit) 
4. git commit -m "something..."
5. git remote add origin repository(create in GitHub)
6. git push -u origin main/master(default branch)

### already has repository
1. git add . 
2. git commit -m "message" 
3. git push origin main/master

### clone project 
1. git clone repo (https://github.com/4nayru/coffee-shop.git)

### pull and checkout branch (already create branch in GitHub)
1. git branch (check the current branch that you have stayed) 
   git branch -a (check all existing branches in that repo)

==> if you doesn't stay at the right branch 
   1. git checkout the_branch_that_you_want_to_stayed
   2. git pull origin  the_branch_that_you_want_to_stayed
