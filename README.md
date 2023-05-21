# This is not a fancy system project #
After having my Mac crashed twice in the past three weeks, I am tired of searching and recalling all the commands I did to configure my machine so that it is fully functionally. Therefore, here comes this memo repo.

## Customized zshrc file ##
Create zshrc file
```
vim ~/.zshrc
```
Install sshpass
```
brew install hudochenkov/sshpass/sshpass
```
Add the following lines to the zshrc file
```
alias nerf="sshpass -p xxx ssh zixuan@128.237.99.117"

PROMPT='%B%F{208}vviki >>%f %F{116}%1~ $%f%b '
```

## Customized welcoming banner ##

```
sudo nano /etc/motd

,~~_
|/\ =_ _ ~
 _( )_( )\~~                      BUGS & EMO
 \,\  _|\ \~~~
    \`   \
    `    `
```