#  电影小程序

功能包括 云函数通过request-promise获取豆瓣API电影信息，显示到页面。
下拉到底会自动concat上10条数据。


电影详情页： 通过点击跳转传movieid参数，再Comment里通过onLoad自带参数options获取movieid, 再通过云函数用书该movieid去获取API详情内容展示。

详情页还使用了vant-weapp框架搭建了评论内容。

评论功能可以发表内容，打星以及上传图片功能。 数据都将上传到云数据库中。

个人页使用自带的data-type属性获取头像，姓名恩等信息，获取按钮能征求用户是否同意获取用户相关信息。

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

