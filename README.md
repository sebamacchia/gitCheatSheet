## SETUP
Configuring user information used across all local repositories
```terminal
git config --global user.name “[firstname lastname]”
set a name that is identifiable for credit when review version history
```
```shell
git config --global user.email “[valid-email]”
set an email address that will be associated with each history marker
```
``shell
git config --global color.ui auto
set automatic command line coloring for Git for easy reviewing
```


## …or create a new repository on the command line
```shell
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sebamacchia/gitCheatSheet.git
git push -u origin master
```

## …or push an existing repository from the command line
git remote add origin https://github.com/sebamacchia/gitCheatSheet.git
git push -u origin master

## …or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project..

