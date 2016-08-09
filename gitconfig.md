# Configure Git

First, we're going to configure Git using the command line.  

#### In your terminal...

Mac: press the space bar and the command key at the same time and type in "terminal."
Windows: launch the command prompt from the run window. 

####Type `git --version`
If you get a version number, you're good to go. If not, click [here](http://git-scm.com/downloads) and follow the directions to install Git as you would any program.

## Configuring Git 

Type the following into your command line, filling in the sections for your username and email. These must correspond to the name and email you used to sign up for GitHub.

`git config --global user.name "John Doe"`
`git config --global user.email johndoe@example.com`

To check that your setup is working, use:

`git config --list`

You'll get something that looks like this:

```
user.name=Superstar Git User  
user.email=gitsuperstar@gmail.com__
```
