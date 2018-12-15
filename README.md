# Auto
无人值守 一键安装 Docker+Hassio 支持 3B+

首先，运行以下命令，将SD卡扩大到整个空间，然后重启树莓派

sudo raspi-config

选7 ---->　选1

设置时区到亚洲--上海 选4 ---->　选2  选 Asia ----Shanghai

设置中文语言  选4 ---->　选1  拉到最后选[*] zh_CN.UTF-8 UTF-8 Zh-cn的GBK UTF-8等

设置wifi地区 选4 ---->　选4 选CN china

sudo reboot

重启之后，依次运行以下命令

cd /tmp

sudo nano docker_hassio.sh

复制本文件内容，到ssh命令行中，保存，关闭，然后依次运行下面的命令

sudo chmod u+x docker_hassio.sh

sudo ./docker_hassio.sh 1>&2


作者

docker_hassio.sh

https://bbs.hassbian.com/thread-3501-1-1.html

【六神分享】20 分钟无人值守 一键安装 Docker+Hassio 支持 3B+
