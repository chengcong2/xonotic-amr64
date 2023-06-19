源码来源：https://ppa.launchpadcontent.net/xtradeb/play/ubuntu/pool/main/x/xonotic/ 这里编译Arm64版本 系统：docker ubuntu22.04 arm64

先编译并安装：https://ppa.launchpadcontent.net/xtradeb/play/ubuntu/pool/main/d/d0-blind-id/ 然后编译：https://ppa.launchpadcontent.net/xtradeb/play/ubuntu/pool/main/x/xonotic/

下载 .debian.tar.xz .dsc .orig.tar.xz 文件 解压.debian.tar.xz与.orig.tar.xz到当前目录 执行 dpkg-buildpackage -uc -b 并等待
