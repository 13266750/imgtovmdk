# imgtovmdk
img文件转vmdk
文件下载地址：https://qemu.weilnetz.de/w64/
![image](https://github.com/13266750/imgtovmdk/assets/51799228/df404adc-35cd-4949-853c-c8d405529e57)

2.安装qemu后，打开cmd检测是否安装成功，切换至安装目录下，输如以下命令

出现如下版本信息，则表示安装成功！
![image](https://github.com/13266750/imgtovmdk/assets/51799228/a5ba8c97-5518-4cc8-986b-b91b6d06353c)


三、将img文件转换为vmdk
![image](https://github.com/13266750/imgtovmdk/assets/51799228/883350a7-f670-4abd-adb3-7a67e7bb7159)

![image](https://github.com/13266750/imgtovmdk/assets/51799228/2aede1bf-5676-4c47-9bad-fa41f225e0ab)
![image](https://github.com/13266750/imgtovmdk/assets/51799228/f24755fe-b8d2-49d0-a1aa-4df22fbe6921)

输入如下命令
.\qemu-img.exe convert  -O vmdk D:\桌面\openwrt.img  D:\桌面\openwrt.vmdk
