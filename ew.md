# tileMapTool

百度地图瓦片图下载，可以下载自定义地图
在mapData.js输入要下载的经纬度的范围和缩放等级，zoomList里的url不填时下载的是默认样式的街道图，要对不同等级应用不同的样式，先写好在线地图后浏览器F12
打开看一下对应的url,将url中的‘x=9&y=4&z=5’处改为‘x=xval&y=yval&z=zval’。
可以自行扩展写个客户端，从百度地图画框直接获取经纬度，或者研究下百度地图自定义样式地图参数的拼接格式，统一从客户端填写参数解析。
运行downloadImg.js下载瓦片图。默认下载至目录下的img文件夹。

1：老版个性化地图编辑地址：http://wiki.lbsyun.baidu.com/custom/

2：获取下载坐标范围：http://www.wmksj.com/map.html

3：修改URL

4：运行downloadImg.js下载瓦片图

