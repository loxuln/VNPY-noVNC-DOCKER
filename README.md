# VNPY-noVNC-DOCKER
全部在浏览器里工作  \
已编译好:CTP linux API vnpy1.7 noVNC 大小 total: 5.1G \
VNPY镜像主要有：\
DEBIAN/anaconda2.7 \
pyqt5 \ qt5 \
pymongo \
websocket-client \
msgpack-python \
qdarkstyle \
拼音输入 \
xfce-4,gedit ,firefox, gcc-4.9 g++-4.9  cmake \
sublime \
可以自行安装：pycharm,WingIDE \
端口：
EXPOSE 5900 8686 \

DOCKER启动：docker run -d -p 8686:8686 cn3c3p/vnpy1.7-pyqt5-anaconda2 \
浏览器打开：  http://localhost:8686/ \
输入密码PASSWORD：88888888 \

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(4).jpg">

<img src="https://github.com/cn3c3p/VNPY-noVNC-DOCKER/blob/master/34d5393b55dc%200%20%20%20noVNC(3).jpg">
