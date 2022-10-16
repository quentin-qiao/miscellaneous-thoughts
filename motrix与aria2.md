# 白嫖百度云

---

## 一、安装motrix，代替满是弹窗广告的迅雷！

1. 进入[Motrix](https://motrix.app/)，安装适合的版本

2. 调教motirx

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717171216120.png" alt="image-20220717171216120" style="zoom:25%;" />

   **首先**，在进阶设置里，==将Tracker服务器里的CDN全部选中==。也可以设置一下==默认安装路径==。

   **然后**，在UA这里，==选择Aria2==，==千万不要设置RPC密钥！这个会导致网盘文件的直链无法正常发送到Aria2==

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717171324583.png" alt="image-20220717171324583" style="zoom: 50%;" />

   **接下来**，搞一个热门的种子，==做个种==，否则没有下载速度。可以下载个电影[RARBG Torrents , films , download (rarbgunblocked.org)](https://rarbgunblocked.org/torrents.php?r=84217025)

   ![image-20220717171100822](https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717171100822.png)

## 二、下载安装浏览器插件

1. **Tampermonkey**

   不同浏览器安装插件的方式大同小异，就不演示了

2. **Aria2**

   **首先**，安装aria2的插件。如果是Edge，可以下载aria2 for edge；如果是Chrome，可以下载aria 2 for chrome；firefox自己摸索一下

   ![image-20220717170303055](https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717170303055.png)

   **然后**，配置aria2。在下面这个界面，上面的勾选根据自己喜好，不是很重要。主要是下面的==Aria2-RPC-Server==，中间栏默认是http://localhost:6800/jsonrpc，需要==把6800改为16800==。记得保存
   
   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717172634478.png" alt="image-20220717172634478" style="zoom:25%;" />
   
   **不出意外的话**，点击edge插件里的aria2 for edge，进入AriaNg，可以看到左侧的Aria2状态为==已连接==。~~必须已连接才能正常使用~~
   
   ![image-20220717173107535](https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717173107535.png)
   
   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717173205454.png" alt="image-20220717173205454" style="zoom: 20%;" />
   
   到此为止，在浏览器里点击下载链接，就会直接在motrix中下载了，不要复制下载链接到motrix中手动下载了。~~当然只有大小超过你设置的值的文件才会这样~~

## 三、下载Tampermonkey脚本

1. 点击插件tampermonkey

1. <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717135055640.png" alt="image-20220717135055640" style="zoom:33%;" />

   点击**获取新脚本**

   

1. 进入greasyfork

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717170409680.png" alt="image-20220717170409680" style="zoom: 33%;" />

   

1. 搜索百度网盘简易下载助手，然后安装

   <img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717170555128.png" alt="image-20220717170555128" style="zoom:33%;" />

   

1. 登录百度网盘，可以看到红色的简易下载助手。选择一个文件（只能是一个，不支持批量下载），点击红色按钮。

1. 点击获取直链地址

1. 点击配置Aria2，将6800改为16800，勾选我使用自己的Aria2。

<img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717174046307.png" alt="image-20220717174046307" style="zoom:33%;" />

​		然后发送至Aria2。正常情况下，应该就直接开始下载了。

<img src="https://raw.githubusercontent.com/quentin-qiao/images/main/img/image-20220717174340151.png" alt="image-20220717174340151" style="zoom:33%;" />
