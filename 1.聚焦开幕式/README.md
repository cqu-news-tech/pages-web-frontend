-html主体：
	*img head:聚焦开幕式banner图片
	*div list:原准备放轮播图的地方，因主页已有取消掉。
				在images文件夹中存放图片，span中写图片介绍
	*div container:滚动条图片展示，同样通过替换images文件夹中图片。
	
-css：
	1、pc.css:屏幕width>500时使用，如果主要图片宽度超过600px,则修改#list中width
				下方小图通过#images img修改尺寸，并根据图片数目和宽度修改#images中的width
	
	2、phone.css:width<500时使用，修改项目同上（靠感觉算百分比）。