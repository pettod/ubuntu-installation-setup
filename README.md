# ubuntu-installation-setup

Commands to install all used softwares in Ubuntu

## install.sh

```bash
cd ~/Downloads/
sudo snap install --classic code
sudo apt install latexmk
sudo apt-get install texlive-full
sudo apt install firefox
sudo snap install gimp
sudo apt install vlc
sudo apt install htop
sudo apt install git
sudo add-apt-repository ppa:graphics-drivers/ppa
sudo apt install google-chrome-stable
sudo apt update
```

## Manual work

```bash
#sudo apt install flashplugin-installer
#sudo apt install adobe-flashplugin
#sudo apt install teams
#wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
#sudo apt install ./google-chrome-stable_current_amd64.deb
sudo ubuntu-drivers devices
sudo apt install nvidia-driver-xxx
https://www.anaconda.com/products/individual#Downloads
bash Anaconda3...sh
pip install kaggle
https://iriun.com/
```

## Ubuntu shortcuts

```bash
Home folder					        Super+E
Launch web browser 				    Super+W
Settings					        Super+S
Take a screenshot interactively     Ctrl+Alt+O
Take a screenshot of a window   	Ctrl+Alt+P
Take a screenshot                   Ctrl+Alt+Å
Show the notification list			Super+M
Launch VSCode					    Super+V ("Custom shortcuts", "code")
```

## VSCode setup

```bash
{
    "window.zoomLevel": 0.8,
    "editor.rulers": [79]
}

Workbench panel: Default Location
View: toggle terminal
```
