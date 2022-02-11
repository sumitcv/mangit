## Documentation
[download git](https://linktodocumentation)  
[ Git Configuration](https://linktodocumentation)  
[Git Initialization](https://linktodocumentation)  
[.bash_profile](https://linktodocumentation)

## Download Git
Download got from below URL for windows- 
```bash
https://git-scm.com/download/win
```
## Git Configuration 
to setup and Configuration git
````bash
 git config --global user.name <user name>
 git config --global user.email <user email address> 
````
to check the configuration done - 
````bash
git config --global user.name 
git config --global user.email 

````
## git initialization
Create an empty Git repository or reinitialize an existing one 

This command creates an empty Git repository - basically a .git directory with subdirectories for objects, 
refs/heads, refs/tags, and template files. 
An initial branch without any commits will be created
````bash
$ git init
````

## .bash_profile
git bash-profile for using git shorthand 

Create file .bash_profile in user path and use below containt in the path 

```bash
# General Aliases
alias ls='ls -GFha '
alias cdg='cd ~/git '
alias st='open -a "Sublime Text" '
alias bp='st ~/.bash_profile '
alias trash='rm -rf ~/.Trash/* '

# Git Aliases
alias get='git '
alias gut='git '
alias got='git '
alias g='git '
alias gi='git init '
alias gs='git status -sb '
alias ga='git add '
alias gc='git commit -m '
alias gac='ga -A && gc '
alias gp='git push '
alias gpo='git push origin '
alias gpom='git push origin master'
alias gr='git rm -r '
alias gb='git checkout -b '
alias gc-='git checkout - '
alias gd='git diff '
```

