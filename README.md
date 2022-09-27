## 👋 Welcome to logrotate 🚀  

Description  
  
  
### Requires scripts to be installed

```shell
sudo bash -c "$(curl -q -LSsf "https://github.com/systemmgr/installer/raw/main/install.sh")" && sudo systemmgr install installer
```

OR

### Automatic install/update  

```shell
systemmgr update logrotate
```
  
### requirements  
  
#### Debian based

```shell
apt install logrotate
```  

#### Fedora Based

```shell
yum install logrotate
```  

#### Arch Based

```shell
pacman -S logrotate
```  

#### MacOS  

```shell
brew install logrotate
```
  
#### Manual install  

  ```shell
APPDIR="/usr/local/etc/$APPNAME"
git clone https://github.com/systemmgr/logrotate "$APPDIR"
cp -Rfv "$APPDIR/etc/." "$HOME/.config/logrotate/"
[ -d "$APPDIR/bin" ] && cp -Rfv "$APPDIR/bin/." "$HOME/.local/bin/"
```

## Author  

🤖 casjay: [Github](https://github.com/casjay) 🤖  
⛵ systemmgr: [Github](https://github.com/systemmgr) ⛵  

## Links

<p align=center>
   <a href="https://travis-ci.com/github/systemmgr/logrotate" target="_blank" rel="noopener noreferrer">
     <img src="https://travis-ci.com/systemmgr/logrotate.svg?branch=master" alt="Build Status"></a><br />
  <a href="https://wiki.archlinux.org/index.php/logrotate" target="_blank" rel="noopener noreferrer">logrotate wiki</a>  |  
</p>  
