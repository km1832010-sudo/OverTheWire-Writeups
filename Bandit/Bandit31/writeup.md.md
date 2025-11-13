# OVERTHEWIRE-BANDIT31->32:















Username: bandit31





password: <Redacted>(obtain it from previous level)







#### Prerequisites:

**git add command**: This command allows you to add files and file changes to the next commit. Usually, it is accompanied by ".", which means everything in this directory. Syntax- git add files/directories

**git commit command**: This command allows you to make a commit. It is usually followed by the -m flag, which allows you to add a message with your commit. Syntax- git commit -m "message"

**git push command**: This command allows you to push the changes in your commit to the next version of your branch. Syntax- git push



#### Solving the level: 


Let us clone the repository, navigate, and cat README.


![Image couldn't load](images/Screenshot-Bandit31-1.png)

This time, we are required to push a file with certain properties, so let us try to do that.

![Image couldn't load](images/Screenshot-Bandit31-2.png)

This part is what we can take from this error message:

![Image couldn't load](images/Screenshot-Bandit31-3.png)

Basically, our email and username don't fit what the repository is looking for. We don't know what email and username we should use, but maybe they will be in level 31, so let us log into the actual server and ls -la.

![Image couldn't load](images/Screenshot-Bandit31-4.png)
![Image couldn't load](images/Screenshot-Bandit31-5.png)

Now that we have the email and username, we can leave the server and set our email and password to the required email and password:

![Image couldn't load](images/Screenshot-Bandit31-6.png)

Ok, now let us try pushing again:

![Image couldn't load](images/Screenshot-Bandit31-7.png)

Strange, it is saying there is nothing to commit, let us ls -la to see what the problem could be. We can see there is a .gitignore file that ignores all text files, so let us get rid of it.


![Image couldn't load](images/Screenshot-Bandit31-8.png)

Ok, now let us try again.

![Image couldn't load](images/Screenshot-Bandit31-9.png)

An error? The content of the file is wrong because I included the parentheses with the 'May I come in?', so let us fix that. If you made this mistake, don't worry about it; it's just a simple misinterpretation of the task.

![Image couldn't load](images/Screenshot-Bandit31-10.png)
![Image couldn't load](images/Screenshot-Bandit31-11.png)
![Image couldn't load](images/Screenshot-Bandit31-12.png)

Previous level: [Bandit30->31](../Bandit30/writeup.md.md)







Next Level: [Bandit32->33](../Bandit32/writeup.md.md)





