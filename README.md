# taobao_taojinbi
本项目主要用于自动执行淘金币活动

**后续代码持续更新，力争完成淘金币全任务，你的☆就是我的动力**

# 测试环境
华为P30Pro + [autojs4.1.1](https://share.weiyun.com/owu3tBNr) + [淘宝v9.16.0](https://www.wandoujia.com/apps/32267/history)
(*华为P30Pro屏幕大小为1080x2340,此分辨率对特殊任务支持最佳*)

# 脚本功能列表
 - 自动执行淘金币所有浏览任务
 - 自动执行[逛好店领一大波金币]任务 (包含浏览10s+10金币任务/收藏店铺+10金币)
 - 自动执行[逛蚂蚁庄园喂小鸡]任务
 - 自动执行[签到领取话费充值金]任务
 - 自动执行[淘宝成就签到任务]
 - 自动执行[淘宝人生逛街领能量]掷色子任务 (需截图权限)
 - 自动执行[逛农场领免费水果]任务 (需截图权限)
 - 自动执行[蚂蚁森林]任务,收取好友能量 (需截图权限)
 - 浏览任务完成立即返回，**无需额外等待**
 
# 更新日志

**v1.2.2** 2020年12月16日19:36:39
1. 新增蚂蚁森林任务，支持自定义'找能量'收取好友能量的次数
2. 解决'天猫领红包任务'，取消了'继续逛逛'按钮问题

**v1.2.1** 2020年12月14日19:57:06
1. 新增消消乐任务，需截图权限，目前在测试P30Pro上测试通过
2. 考虑到不同的机型，某些需截图权限的特殊任务可能会不兼容，启动时添加了可选的额外执行的任务： ['淘宝人生掷色子任务', '逛农场领免费水果任务', '消消乐任务']
3. 添加了APK发布版，用户可直接运行

**v1.2.0** 2020年12月13日20:52:53
1. 简化代码删减了双12的部分
2. 对需要截图功能的[淘宝人生逛街领能量]和[逛农场领免费水果] 设置了是否执行的全局变量，用户可选择是否执行该任务
3. 任务执行等待时间设置为全局变量，默认为15秒

**v1.1.4** 2020年12月12日21:04:28
1. 修复淘金币看直播任务，有时不能返回问题

**v1.1.3** 2020年12月11日20:13:13
1. 修复天猫app没安装，等待过长问题
2. 修复特殊任务后，新出简单浏览任务遗漏问题
3. 无法修复'双12红包兑现红包太少问题'

**v1.1.2** 2020年12月10日20:38:12
1. 解决淘金币执行过程中会返回到主页面问题(本质是按钮单击没有生效)
2. 把淘宝人生、逛好店任务、喂小鸡任务、逛直播间任务添加到特殊任务中
3. 解决芭芭农场双12任务后，淘金币没有肥料问题

**v1.1.1** 2020年12月9日19:36:44
1. 修复逛新加任务不能获取问题 
3. 某些任务(拍照识图)只在最新版淘宝中才存在,当前淘宝已换成最新版v9.16.0,经测试金币还是同样的奖励

**v1.1.0** 2020年12月8日19:51:51
1. 代码基本重构，为适应不同机型，添加了截图查找功能(**需授予截图权限**)
2. 添加任务运行选择功能，可单独执行任务

# 使用说明
## Auto.js中运行
1. 下载 [autojs4.1.1](https://share.weiyun.com/owu3tBNr)
2. 在电脑端下载taojinbi.js文件，使用电脑端qq或微信发给手机端
3. 导入js文件到autojs(可直接在微信/QQ/文件浏览中选择使用其他方式打开)
4. 在autojs中开启无障碍服务并点击运行导入的js文件

auto.js视频运行教程:https://www.bilibili.com/video/BV1Cy4y1S7qE


## 淘金币app运行
1. 在release页面下载taojinbi.apk并安装
2. 为淘金币开启无障碍服务和悬浮框权限(悬浮框权限在华为手机：设置->应用->应用功能->淘金币->显示在其他应用的上层->允许)

淘金币app视频运行教程：https://www.bilibili.com/video/BV1kp4y1q7CD/


# 免责声明
为本人Auto.js学习交流的开源非营利项目，仅作为程序员之间相互学习交流之用，使用需严格遵守开源许可协议。严禁用于商业用途，禁止使用进行任何盈利活动。对一切非法使用所产生的后果，本人概不负责。
