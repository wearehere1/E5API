* 视频教程：（我操作很慢，自行倍速/快进）
   * B站：https://www.bilibili.com/video/av95688306/

  
  CONFIG_ID
  ```shell
  id=r'你的应用id'
  ```
  CONFIG_KEY
  ```shell
  secret=r'你的应用机密'
  ```
  
  **然后第二天回来确认下是否自动运行了（action里是否多出来几个）**,是的话就不用管了，完结。
  
  我设定的每6小时自动运行一次，每次调用3轮（点击右上角星星/star也可以立马调用一次），你们自行斟酌修改（我也不知道保持活跃要调用多少次、多久）：

  * 定时自动启动修改地方：（在.github/workflow/AutoApiSecret.yml文件里，自行百度cron定时任务格式，最短每5分钟一次）
   
  ![image](https://github.com/wangziyingwen/ImageHosting/blob/master/AutoApi/定时.png)
   
  * 每次轮数修改地方：（在1.py最后面）
   
  ![image](https://github.com/wangziyingwen/ImageHosting/blob/master/AutoApi/次数.png)
  
------------------------------------------------------------
### 题外话 ###
> Api调用
  你们可以自己去graph浏览器看一下，学着自己修改要调用什么api(最重要的是调用outlook、onedrive)
  https://developer.microsoft.com/zh-CN/graph/graph-explorer/preview

酷安id-卷腿毛菌
