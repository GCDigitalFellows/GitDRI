#Making a copy of a GitHub repo to work on locally
## Cloning

A **clone** is a local copy of a repository.  

`git clone [URL of your GitHub repo]`

This clones a remote repo to your local Git so you can begin to edit it. 

**First, make sure you are out of GitPractice before you clone.** Let's navigate to the Desktop. 

Clone the [repo for this workshop](https://github.com/jentang/GitDRI) so you can have a copy for yourself!

`git clone https://github.com/jentang/GitDRI`

Also, see if you can use the GUI on GitHub (just the buttons on the web page) to do the same thing. There should be a little "clone or download" button near the top right of each repo. 

## Pulling

If you receive an error notification that you are unable to push changes to your GitHub repo from your local repo, it often means that changes have been made to your GitHub repo that have not yet been logged locally. You'll have to pull the repo, using `git pull [URL of your GitHub repo]` then merge the changes by using `git commit -u origin master` in order to return to smooth sailing with your `git push` commands. 

___
[<<< Git add, commit, and push](gitaction.md) - [Summary >>>](summary.md)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)
