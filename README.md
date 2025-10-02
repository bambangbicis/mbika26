Update

```
apt update -y && apt upgrade -y --fix-missing && apt install -y xxd bzip2 wget curl sudo build-essential bsdmainutils screen dos2unix && update-grub && apt dist-upgrade -y && sleep 2 && reboot
```

Install
```
screen -S setup-session bash -c "wget -q https://raw.githubusercontent.com/bambangbicis/mbika26/main/install.sh && chmod +x install.sh && ./install.sh; read -p"
```
Perintah Untuk Update Script
```
wget -q https://raw.githubusercontent.com/sehuadri/project/main/update.sh && chmod +x update.sh && ./update.sh && rm -f update.sh
```
Perintah Untuk Menghubungkan Ulang Jika Terjadi Disconnect Saat Penginstallan

```
screen -r -d setup
```
