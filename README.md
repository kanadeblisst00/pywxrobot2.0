## 项目介绍

这个是之前pywxrobot的更新维护版(目前已有的插件都是免费使用，未来某些新增的插件可能会收费)，不再使用aardio，而是使用pyside6做界面，可以更好的加载python脚本。

#### 下载地址

国内网盘下载地址：[https://www.123912.com/s/ihEKVv-CW8x?](https://www.123912.com/s/ihEKVv-CW8x) 提取码:9ceo

#### 更新频率

因为很多功能我用不到，所以大概率只会添加一些常用功能和我会用到的功能，文章介绍的话请看：https://mp.weixin.qq.com/mp/appmsgalbum?__biz=MzU0OTkwODU2MA==&action=getalbum&album_id=3904319476392476689#wechat_redirect

![](image/1.png)

#### 功能列表

- [x] [监控公众号推送](https://mp.weixin.qq.com/s/S3nFVPHAhxn23MQb_Mct-Q)
- [x] [自动同意好友请求](https://mp.weixin.qq.com/s/Ky62rpaw-T72O6gL3M8Zrw)
- [x] [关键词自动邀请进群](https://mp.weixin.qq.com/s/Ky62rpaw-T72O6gL3M8Zrw)
- [x] [自动下载文件、图片和视频](https://mp.weixin.qq.com/s/mZvxw1rTzjPzgcRPETtS_w)
- [x] [关键词自动回复](https://mp.weixin.qq.com/s/oJ8COdZiKJSG0_hrVtOqqA)
- [x] [带撤回提示的防撤回](https://mp.weixin.qq.com/s/y8bV-AFSpVOYZC5N8ElpcA)
- [x] [公众号历史文章采集](https://mp.weixin.qq.com/s/JiaIxZ6yWGVraV_vYLkoDA)
- [ ] v免签监控端
- [ ] 进群提示
- [ ] 单向好友检测
- [ ] 对接知识库做智能客服
- [ ] 对接腾讯元宝AI
- [ ] 用AI总结最近的群聊天消息，告诉我有没有我关心的内容
- [ ] 群聊关键词监控
- [ ] v免签监控端
- [ ] 还没想到

## 使用介绍

#### 准备工作

- 3.9.12.37版本的绿色版微信，官方下载地址: `http://dldir1.qq.com/weixin/Windows/WeChat_3.9.12_update37.zip` ，解压后启动里面的WeChat.exe。
- 监听程序

#### 使用方法

1. 先启动并登录上面下载的`3.9.12.37`版本微信
2. 然后打开软件按提示操作

## 插件介绍

#### 监听公众号推送

![](image/2.png)

配置需要保存的方式，当公众号发文时就会推送到对应的配置。

具体介绍请看: https://mp.weixin.qq.com/s/S3nFVPHAhxn23MQb_Mct-Q

如果还需要采集公众号历史/搜一搜/视频号等数据可以看收费的接口: https://v2i7lj8pzi.apifox.cn

#### 公众号历史采集

![](image/7.png)

具体介绍请看：https://mp.weixin.qq.com/s/JiaIxZ6yWGVraV_vYLkoDA

#### 自动同意好友请求

![](image/3.png)

- 是否发送问候语：如果对方请求没有携带任何消息，会将下面的回复问候语发送给他
- 是否分类标签：根据他的好友申请携带的内容讲他归类到某个标签下，例如他发的视频号群就把他打上视频号群的标签
- 是否消息免打扰：同意好友请求后消息免打扰
- 是否仅同意关键词：只有命中下面的关键词规则才会自动同意好友的请求，不然会回复问候语(如果设置)
- 朋友圈权限: 不让他看 1 不看他 2 不让他看|不看他 3 仅聊天 8 

具体介绍请看：https://mp.weixin.qq.com/s/Ky62rpaw-T72O6gL3M8Zrw

#### 关键词自动邀请进群

![](image/4.png)

全匹配是指发送的文字要跟设置的规则一模一样，也就是==。不勾选则是半匹配，只需要发送的文章里包含设置的规则即可。

键是群名称，可以通过下拉框选择，值是要设置的规则，用英文逗号隔开

具体介绍请看：https://mp.weixin.qq.com/s/Ky62rpaw-T72O6gL3M8Zrw

#### 自动下载文件

![](image/5.png)

勾选就会全部下载，后面会弄个选项过滤掉一些群聊

具体介绍请看：https://mp.weixin.qq.com/s/mZvxw1rTzjPzgcRPETtS_w

#### 防撤回

具体请看：https://mp.weixin.qq.com/s/y8bV-AFSpVOYZC5N8ElpcA

#### 关键词自动回复

![](image/6.png)

具体介绍请看：https://mp.weixin.qq.com/s/oJ8COdZiKJSG0_hrVtOqqA