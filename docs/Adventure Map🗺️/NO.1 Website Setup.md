### 网站搭建
第一节课，我们学习了网站的搭建
网站搭建原理可以参考notion网站
> notion是一款功能强大的笔记网站，其强大功能之一就是数据库和对应的呈现。如图，database以表格的形式储存，表格的不同维度代表不同的标签、分类，而数据呈现的view可以选择画廊形式、TODO形式、表格形式等等。
> 
<img src="https://raw.githubusercontent.com/HOY78778/picstore/main/img/202210081920298.png"/>
<img src="https://raw.githubusercontent.com/HOY78778/picstore/main/img/202210081920796.png"/>

对于本节课而言，我们将数据储存在github上（包括图片、文本等），经过html/markdown语言的翻译，成为网页架构。
在实际操作中，我们需要经历：
* github上建立数据库
* 利用github desktop进行本地下载
* 通过visual studio code进行本地编辑
* 上传和html编译。
具体的步骤请参考[本页面](https://www.nexmaker.com/doc/1projectmanage/github&docsify.html)

### 网站搭建遇到的问题
整个过程中，我们组很多学生都遇到了相同的问题：文档初始化（npm i docsify-cli -g）的部分在终端里报错了。
<img src="https://raw.githubusercontent.com/HOY78778/picstore/main/img/202210081936086.png"/>
经过网络查询，我们了解到可能是安装包和mac系统的不兼容（因为问题多发于mac系统），具体参见[网站](https://blog.csdn.net/Sunny_lxm/article/details/105642296)
网上给出的解决方案是在命令行之前加上sudo语句，并在之后输入个人密码。
在如此操作之后安装包下载成功了，我们又经过基本初始化，本地文件夹成功出现docs！
<img src="https://raw.githubusercontent.com/HOY78778/picstore/main/img/202210081935308.png"/>