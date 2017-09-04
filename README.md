<link rel="stylesheet" type="text/css" href="my.css">

### 自制音乐播放器
#### 基于vue-cli

* 开始日期: 2017.7.30
* 源代码: 个人简历music.vue模块
* 使用语言: JavaScript,CSS3
* 目前版本: beta1.2.4
* 结束日期: 待定...

### 进度
+ 2017.9.4
  - 正在进行基于此播放器某些代码进行音乐插件的制作
  - 具体更新见:<a href="http://lesses-xl.github.com/m-player">m-player</a>

+ 2017.8.23:
  - 添加音乐类型歌词判断
  - 歌词位置微调
  - 歌词颜色微调
  - 修复通过按钮添加音乐歌曲数量不刷新的问题
  - beta1.2.4
  - 更新于:14:00

***

+ 2017.8.22:
  - 按钮配色修改
  - 动画效果修改
  - 修复界面大小发生变化时歌词位置错误问题
  - beta1.2.3
  - 更新于:22:40

***

+ 2017.8.21:
  - 界面配色修改
  - 修复列表切换过后歌词无法滚动的bug
  - 增加背景图片切换按钮动画效果
  - beta1.2.2
  - 更新于:22:20

***

+ 2017.8.20:
  - 波形功能基本实现
  - 目前正在做最后的功能调整+样式美化
  - 更新于:3:30
  - 波形图样式美化完成
  - beta1.2.0
  - 更新于:13:35
  - 添加背景图片更换按钮
  - beta1.2.1
  - 更新于:22:50

***

+ 2017.8.19:
  - 波形按钮恢复
  - 波形功能正在实现中...
  - 更新于:23:10

***

+ 2017.8.18:
  - 增加添加歌曲按钮
  - 重复歌曲判断
  - 新增歌曲数目切换
  - 添加删除歌曲按钮
  - 添加localStorage本地缓存(暂时取消)
  - beta1.1.0
  - 修复添加歌曲按钮样式消失问题
  - beta1.1.1
  - 更新于:22:40

***

+ 2017.8.15:
  - 最近暂时不更新

***

+ 2017.8.14:
  - 代码基本重写优化完成(歌词进度还没完成)
  - 拖拽歌曲基本完成(可播放)
  - 近期将添加音频判断,防止将其他类型的文件拖入
+ beta1.0.0正式启动
  - 增加mp3后缀判断
  - 歌词滚动代码暂无更新优化
  - 更新于: 14:40

***

+ 2017.8.13:
  - 暂无更新内容
  - 由于之前的代码太过冗余,使得新增内容难以开发
  - 所以这两天会对源代码进行一次重写
  - 新的更新内容将会和代码改动一起完成,将会在这两天完成
  - 更新于: 20:15

***

+ 2017.8.12:
  - 新增列表切换按钮
  - 新增我的音乐列表,可以将自己喜欢的音乐拖入该列表中
  - 播放功能正在努力实现中,由于牵扯到json文件的索引问题,可能需要点时间来完成
  - 更新于: 20:00

***

+ 2017.8.11:
  - 增加歌曲拖入事件(可以把本地的歌曲拖入列表框内)
  - 但仅仅只是一个外壳,功能目前还在实现当中
  - 更新于: 23:50

***  

+ 2017.8.10:
  - 歌词滚动优化*2
    - 有歌曲存在歌词不同步问题,原因可能是歌词文件本身有问题
  - 修复字体换行(但理论上仍存在该问题)
  - 未来版本将会添加歌曲添加功能,你可以将自己喜欢的歌曲拖入到列表

***

+ 2017.8.9:
  - 修复时间进度显示错误问题
  - 优化歌词滚动同步率
  - 添加拖动进度条歌词同步(但仍然存在bug)
  - 修复第一首歌曲不能获得歌词问题
  - 下一版本修复歌词换行问题
  - 更新于: 17:35
  - 最后祝自己21岁生日快乐

***

+ 2017.8.8:
  - 更换配色
  - 添加空格事件
  - 歌词界面添加自适应(PC)
  - 目前已知bug:
    - 1.歌曲时间进度会显示错误,但或许是网速原因;
    - 2.歌词显示和歌曲波形切换会造成歌词显示错误，目前已把歌曲波形禁用
    - 3.进度条拖动不能获得歌词,导致第一首音乐直接拖动不能获得歌词
  - 需要优化:
    - 歌曲跳转,列表歌曲位置最好能够一并跳转,省去手动寻找的麻烦
    - 歌词滚动需要优化
  - 更新于: 0:13

***

+ 2017.8.7:
  - 歌词滚动大致完成
  - 拖动进度歌词同步还未实现
  - 更新于: 1:30

***

+ 2017.8.6:
  - 子页面取消,全部在一个页面完成
  - 歌词获取效果完成
  - 正在进行歌词滚动效果适配
  - 更新于: 23:15

***

+ 2017.8.5:
  - 修复页面切换后,改变浏览器页面大小报错问题
  - 子页面获取歌词存在bug，正在寻找解决方法
  - 更新于: 23:30

***

+ 2017.8.4:
  - 播放列表透明度修改
  - 右键菜单禁用,并添加事件函数
  - 子路由偶嵌套,新增两个子页面
  - 子页面自适应大致完成,但是存在页面改变时报错的bug
  - 更新于: 22:15

***

+ 2017.8.3:
  - 版本迭代完成,双播放列表页面保留
  - 删除原播放列表,原代码精简
  - 更新于: 23:28

***
