# <img src="https://app.azendoo.com/favicon.ico" width="48" height="48"/> Azendoo Desktop Application

### Getting Started

#### Windows
Download Azendoo-Setup-\<version\>.exe program from [Releases](https://github.com/azendoo/desktop/releases/latest)

Install and ready to work !

#### MacOs
Download Azendoo-\<version\>.dmg program from [Releases](https://github.com/azendoo/desktop/releases/latest)

#### Linux (Debian)
Download Azendoo-\<version\>_\<arch\>.deb program from [Releases](https://github.com/azendoo/desktop/releases/latest)
##### Debian
```
sudo apt install libnotify-bin libappindicator1
wget $(wget -q -nv -O- https://api.github.com/repos/azendoo/desktop/releases/latest 2>/dev/null |  jq -r '.assets[] | select(.browser_download_url | contains("amd64")) | .browser_download_url') -O /tmp/Azendoo.deb
sudo dpkg -i /tmp/Azendoo.deb
```

### Enjoy
