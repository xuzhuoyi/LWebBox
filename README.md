# LWebBox #
LWebBox 是一个在嵌入式设备运行的 Web 控制界面,使用 Python and Django 编写.<br>
使用 LWebBox，你可以实现以下的功能:
![image](http://www.iotwrt.com/jpg/pb1.png)
## 使用方法 
下面是构建步骤(请先执行 cd Pibox).<br>
首先安装依赖:

    sudo apt-get install python-pip python-dev build-essential  libjsoncpp-dev libjpeg-dev zlib1g-dev
    sudo apt-get install python-setuptools
    sudo pip install pillow
    sudo pip install Django==1.6.6
    sudo apt-get install scons

然后运行构建脚本:

    sudo sh ./install_source.sh
    sudo sh ./install_env.sh
启动和停止的脚本:

    sudo sh ./start.sh 
    sudo sh ./stop.sh

在运行启动脚本后,打开你的浏览器然后访问以下 URL:

    http://192.168.10.105(你设备的 IP):8000
(文件浏览器使用 /home/shares）

删除或重新安装：
    删除文件夹然后重复以上步骤。

## 特点
* native iot platform(connect your hardwares to web, like yeelink).
* 文件浏览器.
* Web ssh.
* 主机状态监视.
* webcam snapshot.
* GPIO 控制.
* [more here](https://github.com/wzyy2/PiBox/wiki/Feature)

## 开源许可证 
LWenBox 是一个自由软件；you can redistribute it and/or modify it under terms of the GNU General Public License version 2 as published by the Free Software Foundation.

## FAQ 
* [FAQ](https://github.com/wzyy2/PiBox/wiki/FAQ)



## Image 
![image](http://www.iotwrt.com/jpg/pb2.jpg)
![image](http://www.iotwrt.com/jpg/pb3.jpg)


## App 
如果要扩展应用,可以参考optional-app的写一个程序放到APP文件夹.
如果要使用已有的app，请参考optional-app的readme.
