## Adding the local email id and user name:

git config user.name "Your Name Here"
git config user.email your@email.com


## Creating a new ssh-key:
ssh-keygen -t rsa -b 4096 -C "your@email.com"
Follow more steps at [https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent] (ssh-key generate)

Note: To add key to your [https://help.github.com/en/github/authenticating-to-github/adding-a-new-ssh-key-to-your-github-account] (git-agent) path use: ssh-add /path/to/key
To check if the [https://help.github.com/en/github/authenticating-to-github/testing-your-ssh-connection] (ssh key authentication) is successful use: ssh -T git@github.com

## Creating your git repository:
* [https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-new-repository] (Create) the repository 
* [https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line] Add the repository that exists locally to your github

## Changing and updating the git repository:
* git add .
* git commit
	*Press insert and type in your commit message
* git remote add origin <git_repository_url>
* git push -u origin master
