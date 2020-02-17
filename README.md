Zorin Webdev Starter Kit
=========================

This fork of [Ubuntu Webdev like a Pro](https://github.com/iJackUA/ubuntu-web-dev-like-a-pro) is meant to get an Ubuntu-based distro started quickly with PHP and Python development. Also includes some of the productivity and theme tools I like most.

## Supported OS:

* Zorin 15.1 based x86_64 (64bit), but will likely work on other Ubuntu-based distros using apt package manager. Use at your own risk.

## Quick start

* `curl -s https://raw.githubusercontent.com/iJackUA/ubuntu-web-dev-like-a-pro/master/run.sh | bash /dev/stdin prepare`
* **Check the `main.yml` file to see what will be installed. Check/modify version numbers and included roles**
* `ansible-playbook ~/ubuntu-web-dev-like-a-pro/main.yml --ask-sudo-pass`

## Notice! Nothing is guaranteed! Use it on your own risk! 

Check and customize scripts before running installation. 

## What`s inside :

### IDE

- [x] JetBrains Toolbox (easy installation and version management)

### Browsers

- [x] Chrome
- [x] Chromium

### WebDev essentials

- [x] Composer
- [x] Xdebug
- [x] PHP@7.3
- [x] Python 3
- [x] Ruby (rbenv, rbenv-build, Ruby 2.0.*) 
- [x] Node (nvm)
- [x] Yarn
- [x] Grunt
- [x] Gulp
- [x] Webpack

### Deployment CLIs

- [x] Azure CLI
- [x] ElasticBeanstalk CLI

### WebDev Tools

- [x] Docker CE
- [x] Docker Compose
- [x] Kubernetes (kubectl, kubectx, kubens)
- [x] CA Certificates
- [ ] Postman
- [ ] Dock Station

### System essentials

- [x] ZSH
- [x] Oh-my-ZSH

### System general usage

- [x] LibreOffice
- [x] Mailspring
- [x] Minetime (Calendar)
- [x] Franz
- [x] Slack
- [x] InSync

#### Audio

- [x] Spotify

### Tweaks

- [x] gnome-tweak-tool
- [x] Numix Icons
- [x] Fonts - Powerline fonts
- [x] Auto-preset custom theme, font, icons
