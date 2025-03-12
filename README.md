## INSTALL SCRIPT 
Masukkan perintah dibawah untuk menginstall Autoscript Premium
```
apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt install -y wget && apt install -y curl && apt install haproxy -y && apt install build-essential -y && apt-get install -y jq && apt-get install shc && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/murahbanget0/script/main/setup.sh && chmod +x setup.sh && ./setup.sh
```
#
#
## JIKA GAGAL PAKAI YANG INI
```
sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt upgrade -y --fix-missing && update-grub && sleep 2 && apt install -y wget && apt install -y curl && apt install haproxy -y && apt install build-essential -y && apt-get install -y jq && apt-get install shc && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/murahbanget0/script/main/setup.sh && chmod +x setup.sh && ./setup.sh
```

## UPDATE
```
wget https://raw.githubusercontent.com/murahbanget0/script/main/update.sh && chmod +x update.sh && ./update.sh
```

## RESINTALL/REBUILD VPS DO Ubuntu 20 
```
curl -O https://raw.githubusercontent.com/bin456789/reinstall/main/reinstall.sh && bash reinstall.sh ubuntu 20.04 && reboot
```