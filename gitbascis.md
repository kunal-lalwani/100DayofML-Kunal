## Adding the local email id and user name:

git config user.name "Your Name Here"
git config user.email your@email.com


## Creating a new ssh-key:
ssh-keygen -t rsa -b 4096 -C "your@email.com"
Follow more steps at [ssh-key generate] (https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent)

Note: To add key to your [git-agent](https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account) path use: ssh-add /path/to/key
To check if the [ssh key authentication] (https://help.github.com/en/github/authenticating-to-github/testing-your-ssh-connection)  is successful use: ssh -T git@github.com

## Creating your git repository:
* [Create] (https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository) the repository 
* [Add the repository] (https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)  that exists locally to your github

## Changing and updating the git repository:
* git add .
* git commit
	*Press insert and type in your commit message
* git remote add origin <git_repository_url>
* git push -u origin master
