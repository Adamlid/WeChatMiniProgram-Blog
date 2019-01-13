# WeChatMiniProgram-Blog
#### 微信小程序初体验

微信小程序版的个人博客 & WordPress



##### 说明：

本项目为小程序入门项目，需要一定的前端基础及一点后端知识，项目可能不太好，欢迎大家吐槽，纯萌新小白勿入，最后祝大家Coded愉快。



##### 使用方法：

```
git clone https://github.com/CrazyNing98/WeChatMiniProgram-Blog.git
```

or

```
https://github.com/CrazyNing98/WeChatMiniProgram-Blog/archive/master.zip
```

##### 在微信开发者工具 -->选择你刚clone或解压的目录

打开  **project.config.json**  替换  **appid**  



##### 功能清单：

1.缩略图的方式显示文章列表（首页，分类文章），包括显示文章分类和发布时间，加载分页。

2.在首页用轮播方式显示置顶文章。

3.显示文章分类（专题），包括显示分类的封面图片。

4.显示文章内容页，包括文章站内链接跳转，站外链接复制到剪切板，显示猜你喜欢的相关文章。

5.显示文章评论，提交评论和回复评论，加载评论分页，显示微信用户评论者的头像。

6.显示文章排行

7.显示wordpress“页面”类文字（关于页面）。

8.对文章内容的全文搜索。

9.文章页面的分享、转发，复制。

10.WordPress 插件的配套功能。

11.文章浏览数显示及更新。

12.文章微信用户点赞及点赞的微信用户头像显示。

13.通过微信支付对文章赞赏。

14.赞赏后发送模版消息。

15.web-view内嵌网页跳转。

16.回复评论发送模板消息。

17.专题订阅。

18.文章海报（分享微信朋友圈的卡片）。



##### 快速搭建：

简历页面所需数据一览表

```javascript
  data: {
    time:'',  //时间数据  
    mHt:[],   //头部文字
    mLj:[],   //快速了解li
    mLjT:[],  //快速了解text
    mZp:[],   //我的作品li
    mYs:[],   //我的优势li
    mXy:[],   //自我修养li
    mXyO:[],  //自我修养 开源
    mTd:[],   //希望的团队
    mHf:[],   //底部文字
    f:[]      //脚部信息
  },
```

履历界面所需数据一览表

```javascript
  data: {
    time:'',    //时间数据
    mHt:[],     //头部文字
    f:[],       //脚部信息
    mHf:[],     //底部文字
    line:[		//履历信息
        //公司
		'company'=>'',
		//任职时间
		'time'=>'',
		//职位
		'position'=>'',
		//经验
		'experience'=>'',
		//项目
		'project'=>		//注意这是二维数组
        	//项目名称
        	'name'=>'',
        	//项目经验
        	'exp'=>''
        ,     
        ]     
  },
```



##### 目录结构：

```
MiniProgram  WEB部署目录（或者子目录）
├─pages						页面资源文件           	
│  ├─blog             		博客页面资源
│  │  ├─blog.js
│  │  ├─blog.json
│  │  ├─blog.wxss
│  │  └─blog.wxml
│  ├─index             		简历页面资源
│  │  ├─index.js
│  │  ├─index.json
│  │  ├─index.wxss
│  │  └─index.wxml
│  ├─git             		履历页面资源
│  │  ├─git.js
│  │  ├─git.json
│  │  ├─git.wxss
│  │  └─git.wxml
│  ├─logs             		系统日志目录
│  │  ├─logs.js
│  │  ├─logs.json
│  │  ├─logs.wxss
│  │  └─logs.wxml
├─resource					公共资源文件
├─CHANGELOG.md
├─README.md
├─app.js					项目全局js文件
├─app.json					项目全局json文件
├─app.wxss					项目全局wxss文件
├─app.wxml					项目全局wxml文件
├─project.config.json  		项目配置文件--接入小程序后台

```



##### 技术支持微信：NINGCZ19980501

![https://cdn.iacblog.com/iacblogimages/wexinQRcode.jpg](https://cdn.iacblog.com/iacblogimages/wexinQRcode.jpg)



##### 查看更新日志：

[CHANGELOG.md](https://github.com/CrazyNing98/WeChatMiniProgram-Blog/blob/master/CHANGELOG.md)



##### 项目截图：

![https://cdn.iacblog.com/wx/newmini1.jpg](https://cdn.iacblog.com/wx/newmini1.jpg)

![https://cdn.iacblog.com/wx/newmini2.jpg](https://cdn.iacblog.com/wx/newmini2.jpg)

![https://cdn.iacblog.com/wx/newmini3.jpg](https://cdn.iacblog.com/wx/newmini3.jpg)

##### 在线体验：

![https://cdn.iacblog.com/wx/QRLogo.jpg](https://cdn.iacblog.com/wx/QRLogo.jpg)

如果觉得项目不错，可以点个Star哦😉😉😉



##### 开源协议

本项目遵循开源协议为 [Apache License 2.0](https://github.com/CrazyNing98/WeChatMiniProgram-Blog/blob/master/LICENSE)













