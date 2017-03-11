#How to use git

##Creating a Repository

###Creating Repository from Github

1. Create a new repository on github and include a readme file
2. Click on "Clone or download" and copy the url
3. In terminal, in the desired working directory, type "git clone " then paste in the url

###Creating Repository from computer and pushing to git hub

1. Create new repository on Github and do NOT include a readme file
2. Change directory to the directory that you want to put on Github
3. Type git init : this initializes a git repository on your machine so git can track changes.
4. Add all files to staging by typing "git add ."
5. Commit all changes by typing "git commit -m"
6. Create a remote origin by typing "git remote add origin <url goes here>"
7. Push changes by typing "push origin master"

##Commands

###Adding and committing 
1. Change directory into the repository.		
2. Change or add files.		
3. Type "git add ." : this adds untracked files to staging directory.		
4. Type "git commit -m "<message here>" " : this commits the changes and leaves a message.  		
  (Or to do 4 and 5 in the same step, do commit -a -m"")		
5. Type "git push" : this will publish the changes on Github		

###Forking
This can just be done by clicking fork on a repository then it will end up as a repository on your repository.

###Branches
####Making a new branch
