# Linux-NetSpeed
wget "https://github.com/jackwen999/Linux-NetSpeed/raw/master/tcp.sh" && chmod +x tcp.sh && ./tcp.sh

1、先在[1 – 3]切换内核（第一次显示为bbr内核也要切换一遍），重启


出现Abort Kernal Removal 选择no


2、重启后不用再下载脚本，直接 ./tcp.sh ，在[4 – 8]中选你要开的加速

“1. 安装 BBR/BBR魔改版内核” 对应4,5,6（原版，魔改，暴力魔改）
“2. 安装 BBRplus版内核 ” 对应7（plus）
“3. 安装 Lotserver(锐速)内核” 对应8（锐速）

3、开启后再 ./tcp.sh ， 显示开启成功则启动成功，你也可以自己手动确认
