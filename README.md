# gip
## 各文件说明：
* **G.ip.txt :** Google的ip库文件，用于Agent文件夹内的checkip和GoGo两个程序调用。
* **Gip.bat :** 用于本地端下载G.ip.txt的批处理，在这里备个份。ChromePlus的ip_Update文件夹内已经存在此批处理文件，运行它就可以从这里下载最新的G.ip.txt到Agent文件夹内。

## ip段写法说明：
* 173.194.119.0/24 = 173.194.119.0-255
* 173.194.0.0/16 = 173.194.0-255.0-255 （65536个，导入GoGo里面不包含173.194.0.0和173.194.0.255这样的，余64262个。）






