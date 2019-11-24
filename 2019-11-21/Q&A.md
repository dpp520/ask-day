##安卓手机支持多图上传
```
Q：由于安卓低版本不支持input的mutiple，如何做到多图选择？
A：Android web对于input-file的支持不太好，到了android 4.4连选择文件的窗口都打不开
```

##用户点击隐藏的input=file不灵光
```
Q：input =file，hidden后，不能实现非用户操作的点击，如何处理？
A：
	1.可用label标签改进
	2.可明确指定accept，减少通配符的运用，减少系统对文件搜索筛选
	3.在chrome浏览器下反应慢的原因是因为chrome浏览器为了保障用户的安全，会将用户选择的文件信息发送到google验证，所以只要在设置中关闭改验证（保证您的电脑不受危险网站的侵害）就ok
	4.通常的解决办法是，把input:file透明化，实际上点击的还是input:file
	5.试试return  document. querySelector("#id").click();
```
##将图片翻转
```
Q：ios、andriod的一些机型拍照后，会翻转照片，我们需要转正照片怎么做？
A：利用 exif.js 获取图片的方向信息，解决 ios 上竖直照片翻转
```
##本地压缩图片文件了流大小
```
Q：上传接口时比较慢，前端如何处理图片压缩？
A：用canvas作为媒介上传图片（https://blog.csdn.net/huangpb123/article/details/80560980）
```
##canvas引起系统崩溃
```
Q：canvas在绘制时引起系统奔溃，如何解决？
A：
```
##上传tiff32bit
```
Q：上传tiff格式时用了tiff.min.js,显示不只是32进制的tiff图片，如何解决？
A：
```

##原生js实现左右滚动
```

```


