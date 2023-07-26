# End to End

wip wip wip 

## Windows Only - WSL
Fire up a sudo/admin powershell.  
`wsl --install`.  
This will probably throw some random errors - just google them and resolve them. Same goes for most errors in this guide.   
`wsl --set-default-version 2`  
This should fire up your WSL and provide it with Ubuntu.   

## Ubuntu Setup  
Update everything:  
`sudo apt update && sudo apt upgrade`  

Install some basic stuff:  
`sudo apt install build-essential cmake git python3-pip python3-venv`  
`wget https://github.com/neovim/neovim/releases/download/stable/nvim-linux64.deb`    
`sudo dpkg -i nvim-linux64.deb`

Install Conan and Poetry:  
`pip3 install conan poetry`

Make some folders
`cd ~`
`mkdir CP`
`mkdir Projects`
`mkdir Work`

Set up GitHub SSH:  
`ssh-keygen`  
`cat ~/.ssh/id_rsa.pub`  
Now go to Github.com and add the key.
TODO: improve this lol

Pull CPLIB:
`cd ~/CP`
`git clone git@github.com:echavemann/cplib.git`

## Docker Install
Go to the docker website and download the appropriate installer.
Run that installer and restart your computer as prompted. 

## Other Apps
In the same vein, install the following online:  
- Slack
- GitHub Desktop
- Spotify

## Firefox Setup
Install Firefox from edge. Go to the plugins page. 
Install:
    - Adblocker  
    - Theme  
    - Tampermonkey  
    - Disconnect  
    - Bypass Paywalls  
    - DownThemAll!  
    - Tabbliss  
    - Enhancer for Youtube  
    - Refined GitHub  
    - Material Icons for GitHub  
    - Tree Style Tab  
    - Tranquility Reader  
    - uBlockOrigin  
    - Dark Reader  