<figure>
<img src="img/lostark.png"></img>
<figcaption align="center"><small>logo credits from <a href="https://www.playlostark.com/en-us">lostark</a></small>
</figure>

<h1 align="center">LostArk Forum | 失落方舟中文论坛</h1>

<h5 align="center"><blockquote><b>🎐 <a href="https://lost-ark.top/">LostArk</a>非官方中文论坛开发，项目维护，计划/进程看板仓库</b></blockquote></h5>

<p algin="center">
<a href="https://jq.qq.com/?_wv=1027&k=2TwskxJr">
    <img src="https://img.shields.io/badge/chat-875785029-red?style=plastic&logo=tencent-qq" alt="qq"></img>
</a>
<a href="https://t.me/awesomeLostArk">
    <img src="https://img.shields.io/badge/chat-telegram-blue?style=plastic&logo=telegram" alt="telegram"></img>
</a>
<img alt="GitHub code size in bytes" src="https://img.shields.io/github/languages/code-size/white-windmills/lostark-forum?logo=github&style=plastic">
<a href="https://wakatime.com/badge/user/0fcd442a-865e-46f3-a0dd-ed1aa418da6b/project/98308af8-a89f-4d65-a7aa-7d9382818316">
    <img src="https://wakatime.com/badge/user/0fcd442a-865e-46f3-a0dd-ed1aa418da6b/project/98308af8-a89f-4d65-a7aa-7d9382818316.svg" alt="wakatime"></img>
</a>
<img alt="GitHub Repo stars" src="https://img.shields.io/github/stars/white-windmills/lostark-forum?label=gitub&style=social" alt="github star">
</p>

## 🛒 1 关于

### 🔆 1-1 原因
创建这个论坛的初衷是因为刚开始玩这个游戏的时候找不到攻略，上了[🍄踩蘑菇](https://www.caimogu.cc/)论坛，由于踩蘑菇是多合一论坛找不到有价值的攻略内容；又上了[EMRPG](http://emrpg.com/)失落方舟中文论坛，然而论坛很多内容需要付费才可以查看(**无恶意**)，所以踩决定自己搭建论坛，给大家一个免费，内容开源，**失落方舟中心化**的论坛交流平台，虽然现在浏览访问量不多，但是我们会更加努力为大家提供一个亲民的小社区，致力于为大家提供一个和谐友爱，功能全面，交流顺畅，快乐游戏的交流平台。

### 🍱 1-2 板块

论坛板块分割如下，

| 🧩 板块/Boards               | 🗃 内容/Content                                               |
| --------------------------- | ------------------------------------------------------------ |
| 🧶 **陆地百科**/Encyclopedia | 失落方舟百科 [直达链接](https://lost-ark.top/t/land)             |
| 🛤 **岛屿**/Island           | 游戏岛屿    [直达链接](https://lost-ark.top/t/island)        |
| 👨‍🎓 **职业**/Role            | 游戏职业交流 [直达链接](https://lost-ark.top/t/job)          |
| 🪁 **成就**/Achievement      | 游戏成就    [直达链接](https://lost-ark.top/t/achi)          |
| 📖 **攻略**/Tutorials        | All-in-one攻略，有求必应！ [直达链接](https://lost-ark.top/t/strategy) |
| 💬 **闲聊**/Chat             | 闲聊，~~水帖~~  [直达链接](https://lost-ark.top/t/chat)      |
| 📊 **反馈**/Feedback         | 反馈问题      [直达链接](https://lost-ark.top/t/feedback)    |

...(未完待续)

### 🥽 1-3 功能

论坛提供了如下功能，

| 🎟 功能/Features     | 🗃 内容/Content                                               |
| ------------------- | ------------------------------------------------------------ |
| 🌍 **地图**/map      | 方便的国内地图镜像查看系统(汉化为完善) [直达链接](https://lost-ark.top/map/) |
| ❤ **好感**/Affinity | 板块好感看板       [直达链接](https://lost-ark.top/affinity/)    |
| 🕕 **事件**/Events   | 游戏活动面板，实时更新      [直达链接](https://timer.lost-ark.top/zh/alarms) |

...(未完待续)

## 🧵 2 内容

> **⚠ 本仓库不包含论坛数据库/源码等文件，仅用来存放部分美化/功能源码。**

仓库项目看板请移步至[projects](https://github.com/white-windmills/lostark-forum/projects)看板页面，里面包含了全面的开发计划和项目进程看板，看板一共分为三个阶段`To-do`, `In progress` & `Done`, 分别对应*未开始*，*进程中*，*已完成*。同时通过GitHub Workflow将新的issues自动归档到project*未开始*一栏中。如果您有好的想法或者问题欢迎通过issues提交给我们 ✪ ω ✪！

仓库将会由`update`文件夹里的的**时间戳**来区分当天的任务计划，比如`2022-4-18`则为4/18/2022当日的更新开发内容。

仓库的结构树如下，

```bash
lost-ark:.
│  CHANGELOG.MD
│  README.md
│
├─.github
│  └─workflows
│       ...
│
├─doc
│  └─...
│
├─img
│  └─...
│
└─update
    └─...
```

- `.github`文件夹用于存放GitHub相关的文件，例如`ISSUE_TEMPLATE`(Issue模板)，以及一些`workflows`工作流文件。
- `doc`文件夹用于存放一些为翻译/已翻译的攻略文档，以及开发文档。
- `img`文件夹用于存放图片，logo，以及其他在文档中必要的文档。
- `update`文件夹用于存放当天的任务计划，比如`2022-4-18`则为4/18/2022当日的更新开发内容。(*见上文*)
- `README.md`文件是本仓库自述文件，也就是你现在看到的。
- `CHANGELOG.md`用于存放简明的更新文件。
- ...(未完待续)

## 3 🧸 贡献

如果您觉得本仓库内容不够好/不满意的地方，欢迎提出[Issues](https://github.com/white-windmills/lostark-forum/issues)，[PR](https://github.com/white-windmills/lostark-forum/pulls)将会在仓库管理员审核之后授权，相关的[PR文档/如何PR](https://docs.github.com/en/pull-requests)可以在这里找到。也欢迎到论坛的[反馈板块](https://lost-ark.top/t/feedback)进行反馈哦 (●'◡'●)，~~老登站长随时在线~~(bushi)，同时欢迎加入[QQ](https://img.shields.io/badge/chat-telegram-blue?style=plastic&logo=telegram)群聊or[Telegram](https://t.me/awesomeLostArk)。

**论坛的地图汉化还为完善，欢迎有能力的同学加入汉化组帮助一起汉化！**

如果你觉得我们计划好的话欢迎给我们一个⭐或者~~多水帖~~，以及宣传我们！这是对我们最好的鼓励！

## 4 💌 鸣谢

以下列表为**感谢清单**，在建站的时候使用到的框架/插件/主题/人(?)，**排名不分先后！**

- 本论坛基于[flarum/flarum](https://github.com/flarum/flarum)精心打磨的论坛程序，免费，易安装，轻量，是打造个人轻社区的好帮手，支持大量的插件，论坛使用的插件如下，
  - `composer require yannisme/oxotheme`  oxo主题
  - `composer require flarum-lang/chinese-simplified` 简体中文 
  - `composer require "fof/byobu:*”` 私密讨论 • 创建仅指定用户或用户组可见的私人讨论。
  - `composer require fof/follow-tags` 关注主题
  - `composer require ianm/follow-users:"*”` 关注用户
  - `composer require fof/upload` 图片上传
  - `composer require v17development/flarum-seo` SEO
  - `composer require littlecxm/flarum-reply-to-see:*` 回复可见
  - `composer require oe800/flarum-ext-bbcode-alerts` **BBCode 警示条 & 通知**
  - `composer require darkle/fancybox` 图片弹出
  - `composer require fof/nightmode` 夜间模式
  - `composer require fof/links` ****FoF 导航栏直达链接****
  - `composer require fof/pretty-mail` ****FoF 邮件美化****
  - `composer require itnt/flarum-uitab` 移动端底部导航栏
  - `composer require fof/gamification` ****FoF 游戏化****
  - `composer require askvortsov/flarum-categories` ****标签传统版块****
  - `composer require fof/user-bio` 个性签名
  - `composer require fof/formatting` **FoF 多媒体格式化**
  - `composer require clarkwinkelmann/flarum-ext-circle-groups` 用户组彩色头框
  - `composer require antoinefr/flarum-ext-bbcode-fa` ****BBCode 字体图标扩展****
  - `composer require fof/default-group` 默认用户组
  - `composer require fof/best-answer` 最佳回复
  - `composer require fof/filter` 过滤器
  - `composer require fof/moderator-notes` 留言板
  - `composer require askvortsov/flarum-moderator-warning`s 站务警告
  - `composer require fof/linguist` 全局翻译替换
  - `composer require fof/frontpage` 头版头条
  - `composer require fof/sitemap` 站点地图 须在`.nginx.conf加location = /sitemap.xml { try_files $uri $uri/ /index.php?$query_string; }`
  - `composer require v17development/flarum-seo` 网站SEO
  - `composer require justoverclock/hot-discussions:"*"` 热帖
  - `composer require ganuonglachanh/sonic` 中文搜索
  - `composer require antoinefr/flarum-ext-money` money
  - `composer require michaelbelgium/flarum-profile-views` 最近访客
  - `composer require clarkwinkelmann/flarum-ext-group-list` 群组一览
  - `composer require fof/user-directory` 会员名录
  - `composer require sycho/flarum-github-milestone` 里程碑
  - ...(未完待续)
- 由[Docker](https://github.com/docker)提供的Linux容器的容器化技术，及其包含的组件。
- 由[华为云](https://www.huaweicloud.com/)提供的云服务器。
- 由[godaddy](https://www.godaddy.com/zh-sg/zh)提供的域名。
- 由[Termius](https://termius.com/)提供的SSH登陆工具。
- 由[Vercel](https://vercel.com/)提供的静态文件部署服务。
- 由[docsify](https://docsify.js.org)提供的文档/知识库生成器。
- ...(未完待续)

## 5 📝 许可
**论坛以及本仓库和其附属文件皆遵循[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.zh)开源！**，如果您要转载论坛/仓库文件，请务必加上转载出处！请注意，开源不代表可以滥用，转载或使用这些源代码时，请务必保留原始的版权信息！ 这是一个程序员最基本的修养，也是对原作者最起码的尊重。

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

## 6 💰 捐助

~~我很可爱，请给我钱~~，欢迎通过[爱发电]()捐助我们，所有的费用将会用来维护服务器以及域名购买！