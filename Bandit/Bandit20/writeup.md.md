# OVERTHEWIRE-BANDIT20->21:















Username: bandit20





password: <Redacted>(obtain it from previous level)







#### Prerequisites:



**nc -l flag**: This flag allows you to listen to a port; you do not need to specify localhost for this, it will automatically connect to all local networks. All you need to do is specify which number for the ports. Optional: If you want to specify a port, you need to use the -s flag. Syntax- nc -l portnumber

** & operator**: this operator allows you to have a command run in the background



Optional:

**netcat command**: This is nc, but it uses a slightly different version. It allows for flag combining.


This level has complicated syntax and might be confusing.


#### Solving the level:

To start from the level description, it seems we need to have the password in the nc connection and have to listen to the ./suconnect when we do it, so we start off with this command. This has to be done on the same of any arbitrary numbered port. We can do this with an echo pipe.





![Image couldn't load](images/Screenshot-Bandit20-1.png)

netcat version:


![Image couldn't load](images/Screenshot-Bandit20-2.png)


then we can use the ./suconnect on the same port(for the netcat version enter 1678 port number:

![Image couldn't load](images/Screenshot-Bandit20-2.png)


Previous level: [Bandit19->20](../Bandit19/writeup.md.md)







Next Level: [Bandit21->22](../Bandit21/writeup.md.md)

