# COS-upload
### 基于腾讯COS云对象存储SDK，使用Python编写的文件上传工具
#### 概念
##### COS云对象存储，听起来是一个很玄的概念，官方的概念是对象存储服务（Cloud Object Service）是面向企业和个人开发者提供的高可用，高稳定，强安全的云端存储服务。您可以将任意数量和形式的非结构化数据放入COS，并在其中实现数据的管理和处理。
#### 而我对COS的理解就是，我存如一份资源，COS给我返回一个url地址，这个地址在全球只要是有网络的地方都可以访问的到，这就给我们解决了一些在线Markdown或者其他文档素材的问题，例如我本地的一份md文档，里面的图片是以链接的方式存在，而不是像word文档中直接把图片放到文档中，还有HTML页面等都是用链接的形式去展现，如果此时我把MD复制到其他地方，链接就会失效。
#### 而COS的出现，我只需要使用已经上传的素材的url地址即可，不论在哪里，这个地址是永远有效的。当然，COS的作用还有很多，我只是使用的最简单的。
### 基于以上需求，获取url地址的前提是我需要上传文件，官网提供了控制台，但每次都需要打开游览器一个一个的上传太过低效，于是我使用了官方提供的SDK功能，使用python写了这样一个简单的上传文件功能，下面是使用方法：
1. 先将upload.py和compile.pyc下载，放到同一个文件夹中
2. 将你在官网的APPID，密钥，Bucket分别填入upload.py中，华北地区对应tj。
3. 打开compile.pyc文件，一定是pyc编译好的，直接双击运行，会将upload.py编译成为upload.pyc格式。
4. 然后把uploda.pyc放到要上传的文件目录下，打开，输入要上传的文件夹名称（随便的名称），然后把文件拉如即可，enter以后，会询问continue，是否继续上传
### 这是我发布的P1.0版，后续会根据需求继续更新

* 如图  
![www.rainweb.site](http://blog-1252406596.costj.myqcloud.com/photo/python.png "www.rainweb.site")
