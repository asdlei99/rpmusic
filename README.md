##HTML5 网页音乐播放器

基于 Flask 框架搭建的一个播放器，音乐源来自虾米、网易云音乐。  基于musicbox.coding.io修改。

程序运行环境需要自行修改配置。

###演示
虾米播放器（推荐）：  
http://rpmusic.coding.io/xiamiplayer/377412

网易云音乐播放器（备用）：  
http://rpmusic.coding.io/m163player/5046367
（演示地址最后数字为网易或者虾米歌曲id，，你可以在其网站找到   例如：http://music.163.com/#/song?id=28793502  对应外链地址为http://rpmusic.coding.io/m163player/28793502 ）
###使用
**推荐使用虾米源，没有防盗链。如果歌曲在虾米找不到，再使用网易云音乐。**

虾米播放器（推荐）：  
`<iframe src="http://rpmusic.coding.io/xiamiplayer/394307" frameborder="0" scrolling="0" width="100%" height="200" allowtransparency></iframe>`
<iframe src="http://rpmusic.coding.io/xiamiplayer/394307" frameborder="0" scrolling="0" width="100%" height="200" allowtransparency></iframe>
网易云音乐播放器（备用）：  
`<iframe src="http://rpmusic.coding.io/m163player/5046367" frameborder="0" scrolling="0" width="100%" height="200" allowtransparency></iframe>`

###搭建方法

1. 所依赖的模块在 requirements.txt 里。可以直接使用 `pip -r install requirements.txt`;
2. 运行`python wsgi.py`即可。

