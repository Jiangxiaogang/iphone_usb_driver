# 是什么？
  这是从windows版iTunes提取出来的iphone设备驱动。有了这个驱动就能使用iphone的usb热点功能。不用安装完整的iTunes软件。
  
# 为什么？
  在电脑没有WiFi、没有网络、没有安装iTunes、有一台iphone、有一条usb数据线的情况下，想通过iphone上网，或者把iphone上的文件拷贝到电脑。
 
# 怎么做？
  1. 把usbaapl.jpg下载到手机相册；
  2. 用usb数据线连接iphone到电脑；
  3. 电脑上会出现"Apple iPhone 便捷式设备"，在这个设备里找到刚才下载的照片，并把它拷贝到电脑；
  4. 将刚才拷贝到电脑的照片文件后缀名改为.zip；
  5. 使用7-zip或者WinRAR软件打开这个zip文件，就能看到usb设备驱动了，把它们解压出来，手动安装就可以了；
  6. 安装完成后，就可以使用USB热点功能了。
  
#  附：在windows 7上面手动安装驱动的方法：
  打开windows设备管理器，在“便捷设备”下面找到"Apple iPhone"，
  点鼠标右键，依次选择：
    “更新驱动程序软件”，
    “浏览计算机以查找驱动程序软件”，
    “从计算机的设备驱动程序列表中选择”，
    “从磁盘安装”，
    “浏览”,然后找到刚才解压的usbaapl.inf，选中它进行安装。
    
    
# 使用USB热点传文件？
需要在iphone安装一个APP，推荐使用MFiles，这个APP可以在手机上建立HTTP服务器，然后通过电脑浏览器访问手机的文件，十分方便！
下载地址：https://apps.apple.com/cn/app/mfiles-lite-%E6%9B%B4%E8%BD%BB%E6%9B%B4%E7%AE%80%E6%9B%B4%E6%98%93%E7%94%A8/id1480197468

