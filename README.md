# Auto Script Installer Premium

Step 1 : <br>

```shell
apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
```

Step 2 : <br><br>
```shell
rm -rf setup.sh && sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils wget screen curl && wget https://raw.githubusercontent.com/aziziangah92/scrp3/main/kepo/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
```

# Created
My Name  : jievpn•TPX <br>
whatsapp : wa.me/0109676481 <br>
telegram   : t.me/jievpn
# private
