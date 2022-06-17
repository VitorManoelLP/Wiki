# Wiki
Basic Path for Development

## GIT CONFIGURE 
<img src="https://git-scm.com/images/logos/downloads/Git-Icon-1788C.png" width="48">

### First step to configure git:

```
git config --global user.name "Nome Completo"
git config --global user.email "seu.email@gmail.com"
```

### Second step -> Configure SSH Key for the future pull requests authentication:

```
mkdir ~/.ssh
cd ~/.ssh
ssh-keygen -t rsa -C "seu.email@gmail.com"
cat ~/.ssh/id_rsa.pub
```

**Copy the content of this filename id_rsa.pub and paste in the configuration ssh key [screen of Github](https://github.com/settings/ssh/new).**

###### If your linux terminal don't show the informations about your current branch, take a look in this links of [possible fixes](https://askubuntu.com/questions/730754/how-do-i-show-the-git-branch-with-colours-in-bash-prompt). 

## Swap Memory for Linux: 

- Take this [link](https://linuxize.com/post/how-to-add-swap-space-on-ubuntu-20-04/) and follow step for configure memory swap.

> If the message "Área de texto ocupada" showed, build other file swap for partition.

