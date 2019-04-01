# ResPool
🙄🤯🥺Some useful resource backups

### Sublime Text 3无法安装package control问题
Sublime Text3之前的版本如何安装Package Control，网上有很多教程，一般有问题的是Sublime Text3。在线安装可能会失败，下面提供解决办法。

* 手动下载Package Control</br>

1，从[https://github.com/wbond/package_control](https://github.com/wbond/package_control)下载项目压缩包，解压后重命名为`Package Control`，如果该资源无法获取，可以从本项目中sublimetext3文件夹中获取。</br>
2，进入Preferences > Browse Packages菜单，将`Package Control`文件夹复制过去，重启`Sublime`。

* 如果仍然无法使用，提示`There are no packages available for installation`</br>

1，从本项目目录sublimetext3中获取channel_v3.json文件。</br>
2，打开Preference > Package Setting > Package Control > Setting User，添加类似如下的代码
```
"channel":[
	“D:/Program Files/Sublime Text 3/Packages/channel_v3.json/channel_v3.json”
]
```
你可以找个地方放置channel_v3.json文件，然后指定完整路径即可。

参考自[这里](https://blog.csdn.net/luo1596320/article/details/87868611)