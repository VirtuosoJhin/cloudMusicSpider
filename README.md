## [网易云音乐的爬虫](http://59.110.143.71/CMSpider4web/)

[![license](https://img.shields.io/github/license/mashape/apistatus.svg)]()<br/>
>Docker Pull Command:<br/>
>docker pull jhinwins/cmspider4web

可以根据用户名和评论内容进行评论的模糊搜索<br/>
注：
- 本项目依赖我的另一个项目 proxyIp 用以提供稳定可用的代理ip服务
- 如果您急需使用该服务却发现总是显示**网络错误**，原因是代理ip用完了（大概每20分钟加载一次代理ip），您可以运行proxyIp项目Application类中的main方法临时加载代理ip，**并且我们鼓励这么做**<br/>

#### 效果演示
<small color=gray>注：由于免费的代理ip很不稳定，且存由于在抓取频率过高导致ip被限制的情况，**所以有时候评论可能刷不出来**，如果您有什么好的建议欢迎告知 zouheng613@163.com</small><br/>
![image](https://github.com/Jhinwins/cloudMusicSpider/blob/master/imgs/index.png)<br/>
![image](https://github.com/Jhinwins/cloudMusicSpider/blob/master/imgs/comments_index.png)<br/>
![image](https://github.com/Jhinwins/cloudMusicSpider/blob/master/imgs/search_comments.png)<br/>
![image](https://github.com/Jhinwins/cloudMusicSpider/blob/master/imgs/comments.png)
