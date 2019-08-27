[Learning Journal](https://stanels42.github.io/learningjournal/)

# Git Repositories

The Git workflow is add, commit, push

| **Console Command** | _Usage_ |
|:---------------:|:------|
| `mkdir <\name>` | Make a new file in the console|
| `git clone <URL>` | Retreve a repository off of GitHub |
| `git commit -m "Description of change"` | This is committing a local change. Its often important to note what changes were made and why you made them. This *Does Not* update the file on github only localy. |
| `git commit -a` | This just means to commmit all |
| `git status` | This compare your current changes to the last 'fetch' of information from the server |
| `git add <\filename>` | This is to make an untracked file tracked. |
| `git add *` | makes all untracked files tracked |
| `git push origin master` | This pushes your last commit to the origin (In our case GitHub URL) on branch master |
| `git push <remote><branch>` | The prior command is an example of this in use |
| `git pull origin master` | pull the most recent version of the origin's master branch down to your computer. |
| `git pull <remote><branch>` | This allows you to pull different branches from different remotes connected to the system. |
| `git fetch origin` | This command collects information on the current state of the Git repository from the origin |
| `git fetch <\remote name>` | You can compare the respitory to other remotes connected to the project |
| `git remote` | Lets you see the short name of the remote repositories |
| `git remote -v` | A better version of the prior command that lets you see the URL of the remotes |

## Other Terms
#### commit
This is the act of saving changes on the Git timeline
#### Tracked
These are files that will be updated when you commit your files. Any coppied files will have the tracked status as default
#### Untracked
Much the oppsite of the tracked files, these will be ignored when you commit. Any new files will be untracked by default
#### origin
Used when copying Git repositories refers to the URL it was downloaded from. 
#### master
The master refers to the branch of the tree you are working in. At time of writing we are only working we only use the master branch. It is possible to have different branchs with different names
#### remote
This refers to any other repository that you can push to and pull from.