本工具MZ/MV通用

## 使用方式：

#### 1.打开GreenWork文件夹，将你的Steam游戏编号写入steam_appid.txt

![image](.\pic\1.png)

（注：游戏需要上传steam之后代码返回的结果才是正常的，在游戏未被下载时，部分功能如检测DLC是否安装，可能会永远返回false）
（建议可以直接使用steam上任意一款你已经购买并且下载的游戏的编号来测试DLC购买的功能）

#### 2.将GreenWork文件夹下的所有内容拖进游戏目录下

![image](.\pic\2.png)

拖入后大致如上图

#### 3.打开工程，找到如下插件并开启

![image](.\pic\3.png)

#### 4.之后使用脚本获取信息，如
OrangeGreenworks.isDLCInstalled(2063380)
获取用户是否购买了编号2063380的DLC

其他调用方法可以在greenworks的docs查看
https://github.com/greenheartgames/greenworks/tree/master/docs
文档中的greenworks改为OrangeGreenworks.greenworks

**注意：这个功能在测试模式下是无法使用的！要在最后一步打包完才能正常使用**

#### 5.部署你的游戏

在MV/MZ中部署电脑端

之后将**nwjs-v0.32.4-win-x64**文件夹中的所有内容拖到你部署后的文件夹下

![image](.\pic\5.png)

正常情况下，会有两个exe文件，使用原本的就可以，多的可以删掉



完成！你现在可以在游戏中查看效果了