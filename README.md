# Wiki
Basic Path for Development

## GIT CONFIGURE 
<img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="48">

### First step to configure git ->

```
git config --global user.name "Nome Completo"
git config --global user.email "seu.email@gmail.com"
```

### Second step -> Configure SSH Key for the future pull requests authentication 

```
mkdir ~/.ssh
cd ~/.ssh
ssh-keygen -t rsa -C "seu.email@gmail.com"
cat ~/.ssh/id_rsa.pub
```

**Copy the content of this filename id_rsa.pub and paste in the configuration ssh key [screen of Github](https://github.com/settings/ssh/new).**

