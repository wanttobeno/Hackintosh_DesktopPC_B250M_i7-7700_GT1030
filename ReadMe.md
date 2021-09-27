
#### System Info
![SystemInfo.jpg](SystemInfo.jpg)

##### 说明

测试，安装学习，未系统化测试。


##### Hackintosh macOS High Sierra 10.13.6 （17G66）

```
主板：ASUS B250M PLUS
CPU:  i7-7700 @3.60GHz （集显U630）
显卡：GT1030 
显示器：DELL U2515H
macOS版本：10.13.6（17G66）（dmg镜像大小4.8G左右）
内置声卡：Realtek ALC887

```

##### 正常使用

```
1、独立显卡输出，使用外接显示器HDMI显示。

2、主机前后音频插口正常。

3、显示器HDMI接口支持音频输出，不支持音量调节。

4、休眠，唤醒，关机正常。

5、流畅，不卡屏、闪屏
```



##### 使用说明

复制efi，独显HDMI插口，安装系统。

进入系统安装NVIDIA WebDriver，重启激活显卡。


##### GT1030

![GT1030.jpg](GT1030.jpg)


##### 主板集成声卡ALC887 + 显示器音频输出

![Audio.jpg](Audio.jpg)



##### 激活集显硬件加速

插主板HDMI接口，开始跑苹果进度条后。拔掉，插入到显卡HDMI接口。

![U630.jpg](U630.jpg)

VideoProc测试硬件加速，可以检测到支持。

![VideoProc.jpg](VideoProc.jpg)
 





