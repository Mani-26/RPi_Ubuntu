# RPi_Ubuntu
## Commands for Raspberry Pi with Ubuntu OS

### 1. Configure Wi-Fi:
```
sudo nano /etc/netplan/50-cloud-init.yam
```

### 2. Change the Hostname:
To change the hostname, edit the   ` /etc/hostname ` file:
```
sudo nano /etc/hostname
```
Then edit the `/etc/hosts` file:
```
sudo nano /etc/hosts
```
Replace the old hostname with the new one and save the changes.

### 3. Enable/Disable SSH:
To `enable` or `disable` SSH, use the following commands:
```
sudo systemctl enable ssh     # To enable SSH
sudo systemctl disable ssh    # To disable SSH
```

### 4. Configure Locale and Timezone:
To configure the `locale` and `timezone`, you can use localectl and timedatectl commands:
```
sudo localectl set-locale LANG=en_US.UTF-8    # Replace en_US.UTF-8 with your desired locale
sudo timedatectl set-timezone Your_Time_Zone  # Replace Your_Time_Zone with your desired timezon
```


>[click here to contact me](https://www.linkedin.com/in/mani-s-26032002mani)
