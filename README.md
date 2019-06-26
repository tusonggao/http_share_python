## 局域网内文件夹快速分享的方法


在想对外分享的文件夹下运行bat文件`share.bat`


实际上该文件只是执行下面的语句：
`python -m http.server 9000`


运行后便可以通过ip地址和端口号访问分享的文件夹，效果如下图所示：![截图](https://github.com/tusonggao/http_share_python/blob/master/file_share.png)



运行环境：
- Windows 10
- python 3.6