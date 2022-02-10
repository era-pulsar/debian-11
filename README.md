# debian 11

- sudo -i
```
echo 'deb https://mirrors.tencent.com/debian/ bullseye main' \
  > /etc/apt/sources.list &&\
echo 'deb https://mirrors.tencent.com/debian-security/ bullseye-security main' \
  >> /etc/apt/sources.list &&\
echo 'deb https://mirrors.tencent.com/debian/ bullseye-updates main' \
  >> /etc/apt/sources.list &&\
apt update && apt install -y vim ifstat openssh-server
```
```
# 安装sublime-text
curl -O \
  https://download.sublimetext.com/Sublime%20Text%202.0.2%20x64.tar.bz2 \
  && mkdir -p /etc/devoops && tar -xjf Sublime*.tar.bz2 && mv 'Sublime Text 2' /etc/devoops \
  && ln -s /etc/devoops/Sublime\ Text\ 2/sublime_text   /usr/bin/subl
```
