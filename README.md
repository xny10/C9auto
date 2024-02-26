# C9auto
C9 Installer auto
Requirements

  - Ubuntu (14 > 20 LTS)
  - SSH Access
  - Port 8080 is not used


### Installation

Install cURL [IMPORTANT]

```sh
sudo apt-get install curl -y
```

Then run the installer command
```sh
sudo curl -sL https://raw.githubusercontent.com/xny10/C9auto/main/installer.sh -o c9installer.sh && sudo bash c9installer.sh
```

#### Running IDE

You can run sleepless (24x7) IDE using forever

```sh
sudo forever start ~/c9sdk/server.js -w /var/www --port 8080 --listen 0.0.0.0 --auth <username>:<password>
```


### Now open you browser and visit http://your.ip.address:8080
enter username and password when prompted. Yey! your personal cloud IDE is installed.


Don't follow your dreams, follow my GitHub
