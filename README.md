PUBG MOUSE AIDE

一个鼠标压枪外挂，大概原理是用MAX3421芯片作为USB HOST控制器，获取鼠标的动作，、
然后经过单片机处理后（纵向位移），利用16u2芯片模拟成鼠标，输出HID协议。


# Overview
Please watch the following video giving a detailed overview of the mouseadd.

<p align="center">
    <a href="https://www.bilibili.com/video/av20190153/"><img src="https://i1.hdslb.com/bfs/archive/4fef97da1cd97943435c16577081aad6b705e973.jpg_320x200.jpg"></a>
</p>


# Arduino UNO R3
# Usb Host Shield