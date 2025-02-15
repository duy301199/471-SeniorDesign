# EGCP471 Senior design project.

![Poster for project expos](https://github.com/jge162/471-SeniorDesign/blob/main/Poster.png?raw=true)

### Demo, waste, recycle, compost using object detection. 
https://user-images.githubusercontent.com/31228460/218235257-5be39c9e-64e6-4411-84d5-363eaad962af.mov



## Coral commands 

- [x] use `mdt shell` to connect to coral via USB
- [x] use `ssh mendel@192.168.100.2` to connect via SSH, then use password to connect. 
- [x] connect board to wifi `nmtui`
- [x] check wifi connection `hostname -I` shows IP address of Coral
- [x] can also pin `ping google.com` verifies your are connected to WIFI
- [x] load file to board `mdt push PycharmProjects/InferenceCoral/main.py`
- [x] run Python script on Coral `python3 main.py`
- [x] `sudo apt-get update && sudo apt-get dist-upgrade`
- [x] `sudo reboot now`
- [x] `sudo shutdown now`
- [x] [Connect to dev board serially with mac](https://coral.ai/docs/dev-board/serial-console/#connect-with-macos)

## Git commands.

- [x] `git config --global user.name "Your username"` setup username for Repo
- [x] `git config --global user.email "Your email address"` setup account email
- [x] `git remote set-url origin https://token@github.com/jge162/Senior.git` use this to enable git on Coral
#### After above has been completed does not need to be done again. Unless your token expires (repeat part 3).
- [x] `git pull origin main` 
- [x] `git add .`
- [x] `git commit -m "message you want to describe commit"`
- [x] `git push origin main`

## Update index.html on Google Coral dev board.

- [x] `cd templates`
- [x] `nano index.html` makes changes then do the following commands
- [x] using `control k` will delete line by line code in index.html file
- [x] then use `control o` to save file, then press enter to make changes
- [x] lastly, use `control x` to exit nano editor (used with bin/bash normally)

<br> </br>


