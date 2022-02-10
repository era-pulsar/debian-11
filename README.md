# debian 11
```
echo 'deb https://mirrors.tencent.com/debian/ bullseye main'                    > /etc/apt/sources.list
echo 'deb https://mirrors.tencent.com/debian-security/ bullseye-security main' >> /etc/apt/sources.list
echo 'deb https://mirrors.tencent.com/debian/ bullseye-updates main'           >> /etc/apt/sources.list
apt update && apt install -y vim ifstat firefox openssh-server
```
