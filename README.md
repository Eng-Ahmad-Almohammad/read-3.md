# Remote Repositories
![image](https://cdn.educba.com/academy/wp-content/uploads/2019/03/Introduction-To-GIT.png)
### In order to collaborate on Git projects, you must interact with remote repositories, versions of a project residing online or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote repositories to push information to and pull data from.
## Soem of commands using in Remote Repositories:
### **1. Cloned Repositories:** 
#### As mentioned earlier, for cloned repositories, Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch.
### **2. Seeing Your Remotes:**
#### By running the git remote command, you can view the short names, such as “origin,” of all specified remote handles.
#### By using git remote -v, you can view all the remote URLs next to their corresponding short names.
### **3. Adding RemotesL:**
#### To create a new remote Git repository with a short name, use the following format:
#### git remote add shortname url
### **4. Fetching:**
#### Fetching entails pulling data that you don’t have from a remote project.
#### Here is the command format:
#### git fetch [remote-name]
### **5. Pushing:**
#### To push your changes “upstream” for sharing, you would use the following git push command format:
#### git push [remote-name][branch-name]
### **6. Renaming/Removing Remotes:**
#### To rename a remote’s short name, use the *git remote rename* command.
## For more information visit [Udemy Tutorial](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_2)
