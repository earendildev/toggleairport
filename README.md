*The credit for most of the code belongs to others including [albertbori/toggleairpot](https://gist.github.com/albertbori/1798d88a93175b9da00b)*
*forked from [Calvin-LL/toggleairport](https://github.com/Calvin-LL/toggleairport)*

# Overview #

Simply this Script turns off the WiFi Adapter when it detects a Wired Ethernet Connection and turns the WiFi back on when the Ethernet Adapter is unplugged.
**Only for MacOs**.

## For Catalina and later ##

**To Install**
```bash
mkdir -p $HOME/.config/scripts/ && cd $HOME/.config/scripts/
git clone https://github.com/earendildev/toggleairport.git
cd toggleairport
./install.sh
```

**To Uninstall**
```bash
cd $HOME/.config/scripts/toggleairport
./uninstall.sh
```

***Do not run either of the scripts with sudo, if you do, notifications will not display.***
