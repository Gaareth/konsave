# Konsave (Save Plasma Customization)
A CLI program that will let you save and apply your KDE Plasma customizations with just one command! Also, it has a "K" in the name :D  

---

![ezgif-7-e0c7257f0aef](https://user-images.githubusercontent.com/39525869/109611033-a6732c80-7b53-11eb-9ece-ffd9cef49047.gif)

---
## Dependencies
There are no dependencies! Just make sure your python version is above `3.8`.

## Installation
- Clone This repo  
`git clone https://github.com/Prayag2/konsave ~/Downloads/konsave`
- Make it executable  
`cd ~/Downloads/konsave`
`chmod +x ./install.sh`
- Install  
`./install.sh`

## Usage
### Get Help
`konsave -h` or `konsave --help`
### Save current configuration as a profile
`konsave -s <profile name>` or `konsave --save <profile name>`
### List all profiles
`konsave -l` or `konsave --list`
### Remove a profile
`konsave -r <profile id>` or `konsave --remove <profile id>`
### Apply a profile
`konsave -a <profile id>` or `konsave --apply <profile id>`
You may need to log out and log in to see all the changes.  
### Export a profile as a ".knsv" file to share it with your friends!
`konsave -e <profile id>` or `konsave --export-profile <profile id>`
### Import a ".knsv file
`konsave -i <path to the file>` or `konsave --import-profile <path to the file>`
## Contribution
You can contribute by reporting issues or fixing bugs!

## License
This project uses GNU General Public License 3.0
