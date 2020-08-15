# Bilibili直播间挂机助手/Bilibili-LRHH/BLRHH-魔改-上舰监控大乱斗点亮挂心

本项目非纯开源项目！
本项目非纯开源项目！
本项目非纯开源项目！

# BiliPush推送服务于2020-08-13到期

脚本目前包含恶意功能
 1. 身份验证（上传使用者信息 uid uname roomid）
 2. 开播广播（刷新使用者观看直播间，音量调整）
 3. DD传送门（调整使用者观看直播，页面跳转）
 4. DD节奏风暴（发送弹幕）【本功能有一定隐患，具体取决于DD头子小学语文老师的水平】
 
如果介意还请不要使用，或自行在脚本功能设置中关闭 BiliPush推送。


PS： 本脚本 极具危害性 可能会清空您的背包 盗取你的金瓜子 还会偷偷花你钱给主播送礼物<br>
不仅如此 脚本可能帮你关注一堆辣眼睛的UP 也可能会把你的硬币全都偷偷花掉<br>
把你的B币 全部拿去 打赏新番 或者 充电<br>
还能在大半夜突然发出声音（这条是真的）<br>
所以 如果你没用过 还请不要使用 感谢 Thanks♪(･ω･)ﾉ <br>


本人无Q群
如有疑问，请加原版挂机助手作者Q群：704160936（满）,1046583474（新）
答案：!!!


![ECMAScript 5](https://img.shields.io/badge/ECMAScript_5-unsupport-red.svg?longCache=true) ![ECMAScript 6](https://img.shields.io/badge/ECMAScript_6-pass-green.svg?longCache=true) ![TamperMonkey 4.8](https://img.shields.io/badge/TamperMonkey_4.8-pass-green.svg?longCache=true) ![Chromium 74](https://img.shields.io/badge/Chromium_74-pass-green.svg?longCache=true) 
> 该脚本为TamperMonkey脚本，只在该环境下测试通过，使用其它脚本插件来加载此脚本的，不能保证正常运行  
> 当脚本无法正常运行时，请把广告拦截插件关闭后重试

-----------------
## GitHub中脚本如何安装魔改版
如果 Git 不能正常访问 还请自行设置一下 Hosts
```
151.101.76.133 raw.githubusercontent.com
```
1. 安装油猴插件
2. 点击 
2.1 [脚本安装-魔改助手1](https://raw.githubusercontent.com/pjy612/Bilibili-LRHH/master/Bilibili%E7%9B%B4%E6%92%AD%E9%97%B4%E6%8C%82%E6%9C%BA%E5%8A%A9%E6%89%8B-%E9%AD%94%E6%94%B9.user.js)
2.2 [脚本安装-魔改助手2](https://github.com/pjy612/Bilibili-LRHH/raw/master/Bilibili%E7%9B%B4%E6%92%AD%E9%97%B4%E6%8C%82%E6%9C%BA%E5%8A%A9%E6%89%8B-%E9%AD%94%E6%94%B9.user.js)
2.3 [脚本安装-魔改助手3-github国内镜像加速](https://github.com.cnpmjs.org/pjy612/Bilibili-LRHH/raw/master/Bilibili%E7%9B%B4%E6%92%AD%E9%97%B4%E6%8C%82%E6%9C%BA%E5%8A%A9%E6%89%8B-%E9%AD%94%E6%94%B9.user.js)

3. 如果github安装不稳定，请自行新建复制 同下方原版步骤

## 如何使用原版
1. 见[GreasyFork](https://greasyfork.org/zh-CN) 首页说明
2. 方式一：进入[Bilibili直播间挂机助手](https://greasyfork.org/zh-CN/scripts/37095-bilibili%E7%9B%B4%E6%92%AD%E9%97%B4%E6%8C%82%E6%9C%BA%E5%8A%A9%E6%89%8B)页面，点击"安装此脚本"即可从GreasyFork更新此脚本
3. 方式二：点击[Bilibili直播间挂机助手](https://raw.githubusercontent.com/SeaLoong/Bilibili-LRHH/master/Bilibili%E7%9B%B4%E6%92%AD%E9%97%B4%E6%8C%82%E6%9C%BA%E5%8A%A9%E6%89%8B.user.js)，脚本管理器会弹出安装脚本页面(如果没有，则需要将代码复制下来。然后从脚本管理器中新建一个脚本，将自动生成的内容删除，粘贴复制的代码)，即可从Github更新此脚本(优先更新Github)
4. 进入直播间页面，右下角多出个"挂机助手设置"，选择自己需要的功能，保存刷新即可

-----------------

## 已实现功能
+ 自动签到
+ 自动领取银瓜子
+ 自动应援团签到
+ 移动端心跳
+ 挂小心心的功能(new)(test)
+ 自动抽奖
  + 礼物抽奖
  + 舰队领奖
  + 实物抽奖
  + 大乱斗抽奖(new)
  + 节奏风暴抽奖(new)
  + 抽奖休眠(new)  
+ 自动完成任务
+ 自动送礼物
  + 自动拿小心心点亮勋章(new)
+ 自动每日奖励
+ 银瓜子换硬币
+ 礼物监控<核心功能>(new)
+ 当日礼物统计(new)
-----------------

## 说明
+ 自动抽奖功能大多是基于广播的，如果广播不会通知(比如其他房间的舰长)，则不会参加对应的抽奖
+ 在TamperMonkey脚本设置中需要将此脚本的设置“仅在顶层页面（框架）运行”设置为否(默认为否)才能正常运行此脚本的一些功能

-----------------

## 常见问题
1. OCRAD初始化失败/脚本需要加载很久/不能正常使用
    + 尝试替换脚本require源
    + 在代码中找到以下几段代码中的一段，替换为其他的一段，然后刷新页面试试

        ```js
        [greasyfork源]
        // @require      https://greasyfork.org/scripts/38140-bilibiliapi/code/BilibiliAPI.js
        [github源]
        // @require      https://raw.githubusercontent.com/SeaLoong/Bilibili-LRHH/master/BilibiliAPI.js
        // @require      https://raw.githubusercontent.com/SeaLoong/Bilibili-LRHH/master/OCRAD.min.js
        [gitee源]
        // @require      https://gitee.com/SeaLoong/Bilibili-LRHH/raw/master/BilibiliAPI.js
        // @require      https://gitee.com/SeaLoong/Bilibili-LRHH/raw/master/OCRAD.min.js
        [腾讯云源]
        // @require      https://js-1258131272.file.myqcloud.com/BilibiliAPI.js
        // @require      https://js-1258131272.file.myqcloud.com/OCRAD.min.js
        [jsDelivr源]
        // @require      https://cdn.jsdelivr.net/gh/SeaLoong/Bilibili-LRHH/BilibiliAPI.js
        // @require      https://cdn.jsdelivr.net/gh/SeaLoong/Bilibili-LRHH/OCRAD.min.js
        ```

2. 开启自动抽奖后，直播间页面经常崩溃
    + 在设置中找到"刷新间隔"，设置为一个合适的数值
    + 这个情况目前暂无更好的解决方法
3. 可以领取瓜子却显示"今日已领完"
    + 我也不知道啊QWQ，清理下缓存试试
4. 自动抽奖功能不能正常运行
    + 关闭广告拦截插件试试
5. 脚本显示完成了每日经验奖励，但个人中心显示未完成
    + 正常现象，过段时间就会正常显示了
6. 弹幕服务器频繁断开重连
    + B站限制了弹幕服务器连接数
    + 如果舰队倍数太高 会导致超过连接数 然后频繁的断开重连
    + 推荐设置 1-5
7. 直播间经常自动跳转
    + 正常情况 脚本绑定直播间 如果在其他直播间使用脚本则会被传送回指定直播间
    + 例外情况 DD传送门激活时 脚本暂时支持额外直播间（无需额外操作）
    + 如果你仍然想在使用脚本的同时观看其他直播 可以新开一个标签页
8. 双端观看 移动端无法完成
    + 由于APP端信息需要一个很重要的参数去校验 单靠脚本无法完成
    + 所以用脚本只包含心跳功能，具体观看还请用app随便打开一个直播间即可完成
    + 如果你一定想要自动的话 可以考虑使用另一个项目[bili2.0](https://github.com/pjy612/bili2.0)
-----------------

## 注意事项/关于反馈
    开启自动抽奖->礼物抽奖功能后，很容易在控制台看到许多Error，这些大多是B站的脚本错误，不用理会
    要检索此脚本的控制台输出只要过滤显示带有"[BLRHH]"字样的输出即可
    在脚本代码中找到有关"DEBUGMODE"的地方，将其设置为true可在控制台输出调试信息，反馈(包括bug、B站更新等)时请带上有关信息

-----------------

## 捐赠魔改作者

无

-----------------

## 捐赠原作者（原作者近期正在憋大招，应该会有新的框架和优化）

+ 支付宝 => ![支付宝二维码](https://raw.githubusercontent.com/SeaLoong/Bilibili-LRHH/master/AliPay2.png) 微信 => ![微信二维码](https://raw.githubusercontent.com/SeaLoong/Bilibili-LRHH/master/WeChat2.png)

-----------------

## 许可证
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg?longCache=true)](https://github.com/pjy612/Bilibili-LRHH/blob/master/LICENSE)

-----------------

## 更新日志
> ###  2020-08-10(Version 2.4.5.17)【批站 你没有妈妈 凸(艹皿艹 )】
>     小心心亲密度fix
>     风暴模式开关（非实名可选，但是大会员可能异常，自行取舍）
>
> ###  2020-08-10(Version 2.4.5.16)【Final】
>     挂心功能本地化，可离线用
>     进房检测等配置当然缓存（减少请求避免风控）
>     小时榜检测开关化（减少请求避免风控）
>
> ###  2020-07-30 (Version 2.4.5.15)
>     单纯换源 cdn.jsdelivr.net 都能挂 囧
>
> ###  2020-07-28 (Version 2.4.5.14)
>     应援团重试次数限制，瓜子依赖原作者好像删还是换位置了 囧 换个源
>
> ###  2020-07-24 (Version 2.4.5.13)
>     重新编写小心心模块（2.4.5.8-2.4.5.12）全部木大了
>
> ###  2020-07-24 (Version 2.4.5.12)
>     fix 自动送礼 异常
>     换回cdn.jsdelivr.net源，不及时就不及时了，总比连不上强
>
> ###  2020-07-23 (Version 2.4.5.11)
>     自动送礼查询勋章和背包逻辑调整，改用局部变量控制调用一致性
>     参考[andywang425]更换github国内镜像加速
>
> ###  2020-07-23 (Version 2.4.5.10)
>     调整小心心触发顺序和间隔 避免并发
>
> ###  2020-07-22 (Version 2.4.5.9)
>     移动端token本地缓存一下，感觉取多了会被定为频繁登陆
>
> ###  2020-07-21 (Version 2.4.5.8)
>     新增自动拿小心心点亮勋章的功能（默认开启）
>     新增自动挂小心心的功能（待测试，BP连接中生效）【每天24个】
>
> ###  2020-07-20 (Version 2.4.5.7)
>     修一下休眠（这功能有用？）最后几天还不莽起来嗨？
>
> ###  2020-07-18 (Version 2.4.5.6)
>     B站改了个Api...然后还没啥用...然后他喵的又改回去了 fuck
>
> ###  2020-07-18 (Version 2.4.5.5)
>     B站改了个Api...然后还没啥用...
>
> ###  2020-07-13 (Version 2.4.5.4)
>     双端细节优化，如果当日完成双端则不再请求移动心跳【可能会少移动端活动礼物(待测)】
>     双端稳定性调整，双端辅助接口只在双端未完成时调用，降低移动端接口调用频率【防止大会员被冻结(待测)】
>     
> ###  2020-07-07 (Version 2.4.5.3)
>     修复送满勋章送掉永久礼物的BUG
>     新增自动送礼排除房间列表
>
> ###  2020-07-01 (Version 2.4.5.2)
>     移除一只双端的API 尝试解决 大会员冻结 问题
> 
> ###  2020-07-01 (Version 2.4.5.1) 弃用 对大会员用户有大会员冻结风险 请及时更换
>     修复双端，这次我自测了
>     天选现在应该能正常开启不白屏了
>     实物抽奖API更新
>
> ###  2020-06-30 (Version 2.4.5.0)
>     尝试修复双端
>     新增风暴ex试运行-无需实名抢风暴（亿元更难抢了QAQ）
>     感谢[andywang425](https://github.com/andywang425)给予灵感
>     感谢[lzghzr](https://github.com/lzghzr)大佬的支持库
>
> ###  2020-06-04 (Version 2.4.4.32)
>     新增一个娱乐功能，DD人力节奏风暴，会发送弹幕，活跃直播间气氛，默认开启
>     （本功能有一定隐患，具体取决于DD头子小学语文老师的水平）
> ###  2020-06-03 (Version 2.4.4.31)
>     修复 2.4.4.29 更新后 导致 2.4.4.28 BUG 的 BUG
> ###  2020-06-02 (Version 2.4.4.30)
>     添加bilipush模块开关
> ###  2020-06-02 (Version 2.4.4.29)
>     更新对特殊房间的跳转支持逻辑
> ###  2020-06-01 (Version 2.4.4.28)
>     修复一个之前修复应援团BUG而产生的BUG（真有人自己当主播还用这玩意的吗？）
>     调整自动送礼功能逻辑
> ###  2020-05-30 (Version 2.4.4.26)
>     修复休眠功能逻辑问题
> ###  2020-05-27 (Version 2.4.4.25)
>     fix 自动送礼重复触发
>     连接数修改(避免总问弹幕服务器重连问题) (Version 2.4.4.24)
>     自动送礼显示更多亲密度相关信息 (Version 2.4.4.24)
>     修正v2.4.4.22调整API引用顺序导致应援+分享相关功能失效的问题(Version 2.4.4.23)
> ###  2020-05-25 (Version 2.4.4.22)
>     新增休眠功能，根据时间段进行休眠
> ###  2020-05-22 (Version 2.4.4.21)
>     修复2.4.4.20导致设置项失灵的问题
>     尝试兼容特殊活动房间 (Version 2.4.4.20)
>     自动送勋章亲密度优化 (Version 2.4.4.19)
>     礼物队列优化        (Version 2.4.4.18)
>     风控优化        (Version 2.4.4.16-17)
>     中间有一系列杂七杂八的东西（记不清了）
> ###  2020-03-20 (Version 2.4.4.2)
>     新增当日礼物统计
>     中间有一系列杂七杂八的东西
> ###  2019-09-25 (Version 2.4.3.4)
>     修复频繁重连的问题
> ###  2019-09-25 (Version 2.4.3.3)
>     新增大乱斗接口
>     新增抽奖监控
>     跨直播间领奖伪造来源
> ###  2019-08-22 (Version 2.4.3)
>     更新了抽奖接口
>     修改了抽奖方式
> ###  2019-08-16 (Version 2.4.2)
>     修复了不能正确识别小黑屋的问题
> ###  2019-07-29 (Version 2.4.1)
>     更新了抽奖接口
> ###  2019-07-02 (Version 2.4.0)
>     修复了在未启用舰队领奖时仍然会领取奖励的问题
>     增加了自动更换监听房间的功能
> ###  2019-05-25 (Version 2.3.18)
> ###  2019-05-25 (Version 2.3.17)
>     修复了主动断开弹幕服务器连接后仍自动重连的问题
> ###  2019-05-22 (Version 2.3.16)
>     修复了自动完成任务、自动送礼、自动实物抽奖计时不正确的问题
> ###  2019-05-03 (Version 2.3.15)
>     修复了移动端心跳失效的问题
> ###  2019-03-26 (Version 2.3.14)
>     增加了自动分流连接弹幕服务器的功能
>     修复了有时候会出现访问过快的问题
> ###  2019-03-23 (Version 2.3.13)
>     优化了访问API的方式
>     修复了自动抽奖出现漏抽、漏领的问题
> ###  2019-03-18 (Version 2.3.12)
> ###  2019-03-18 (Version 2.3.11)
>     修复了在网络环境差的情况下部分功能有时不能正常运行的问题
> ###  2019-03-15 (Version 2.3.10)
>     修复了舰队领奖、礼物抽奖在没有新的广播时不会参加已有抽奖的问题
>     增加了隐藏抽奖提示框的功能
> ###  2019-03-15 (Version 2.3.9)
>     修复了舰队领奖、礼物抽奖中错误识别为小黑屋状态的问题
> ###  2019-03-05 (Version 2.3.8)
>     优化了领瓜子代码逻辑
>     优化了脚本多开检测代码逻辑
>     增加了清除脚本缓存的功能
>     移除了重置为默认设置的功能
> ###  2019-02-28 (Version 2.3.7)
>     修复了一处实物抽奖中的逻辑问题
>     修复了由时差引起的脚本执行不正常的问题
> ###  2019-02-14 (Version 2.3.6)
>     修复了一处因Cookie过期导致无限重试的问题
>     优化了实物抽奖穷举算法
> ###  2019-02-13 (Version 2.3.5)
>     增加了新的分区支持
> ###  2018-12-15 (Version 2.3.4)
> ###  2018-12-04 (Version 2.3.3)
> ###  2018-12-01 (Version 2.3.2)
> ###  2018-11-27 (Version 2.3.1)
>     修复了一些逻辑问题
> ###  2018-11-26 (Version 2.3.0)
>     修复了应援团签到不能正常使用的问题
>     增加了自动完成每日奖励任务的功能
> ###  2018-11-10 (Version 2.2.6)
> ###  2018-11-10 (Version 2.2.5)
>     增加了自动抽奖的内置延迟
>     增加了对自动送礼功能的限制
> ###  2018-11-07 (Version 2.2.4)
> ###  2018-11-05 (Version 2.2.3)
>     修复了有时出现抽奖参数不正确的问题
> ###  2018-11-04 (Version 2.2.2)
>     优化了代码逻辑
>     修复了重复抽奖的问题
> ###  2018-11-03 (Version 2.2.1)
>     修复了舰队领奖不能正常工作的问题
>     增加了自定义监听房间数的功能
>     优化了代码逻辑
> ###  2018-11-03 (Version 2.2.0)
>     修改了自动抽奖->礼物抽奖的参与方式
>     修改了自动抽奖->舰队领奖的参与方式
>     移除了部分设置项及其功能
> ###  2018-11-01 (Version 2.1.3)
>     修复了不能礼物抽奖的问题
> ###  2018-11-01 (Version 2.1.2)
>     修复了舰队领奖有时候会疯狂重试的问题
> ###  2018-10-31 (Version 2.1.1)
>     修复了脚本可以在多个直播间页面运行的问题
>     修复了舰长奖励无法领取的问题
> ###  2018-10-30 (Version 2.1.0)
>     优化了重试机制
>     增加了对四大分区都监听的功能
>     (可能)修复了一些奇怪的bug
> ###  2018-09-28 (Version 2.0.12)
>     修改和移除了部分设置项
>     提高了使用稳定性
> ###  2018-08-26 (Version 2.0.11)
>     修复了在有实物抽奖的直播间不能运行脚本的问题
> ###  2018-08-21 (Version 2.0.10)
>     增加了对超时情况的处理
>     调整了部分代码逻辑以保证功能的持续运行
> ###  2018-08-17 (Version 2.0.9)
>     调整了实物抽奖代码逻辑
> ###  2018-08-13 (Version 2.0.8)
>     调整了一小部分代码
> ###  2018-08-09 (Version 2.0.7)
>     增加了自动刷新页面的功能
>     增加了只允许单个直播间页面的脚本运行的功能
> ###  2018-08-08 (Version 2.0.6)
>     修复了自动领取瓜子有时候会停止不领取的逻辑问题
>     修复了自动抽奖->实物抽奖有时候会疯狂访问接口的问题
>     移除了银瓜子换硬币的旧接口及其设置项
> ###  2018-08-05 (Version 2.0.5)
>     修复了"防止自动完成任务、自动送礼在同日/同时间段多次运行的功能"无效的问题
>     修复了在当日银瓜子领取完后，再次运行脚本后，自动领取银瓜子界面会显示"自动领取中"的问题
> ###  2018-08-05 (Version 2.0.4)
>     增加了防止自动签到、自动应援团签到、银瓜子换硬币、自动完成任务、自动送礼在同日/同时间段多次运行的功能
> ###  2018-08-04 (Version 2.0.3)
>     修复了自动抽奖部分设置项无效的问题
> ###  2018-08-03 (Version 2.0.2)
>     修复了自动抽奖->礼物抽奖在运行时会出现其他直播间声音的问题
>     优化了自动抽奖->礼物抽奖的参与方式
> ###  2018-08-03 (Version 2.0.1)
>     优化了自动抽奖->礼物抽奖的参与方式
>     增加了移动端心跳5分钟后自动进行一次完成任务的功能
>     修复了自动送礼不能持续运行的问题
>     增加了保存设置时会自动修正设置的功能
> ###  2018-08-02 (Version 2.0.0)
>     增加了自动应援团签到的功能
>     增加了移动端心跳的功能(可配合自动完成任务来完成双端观看)
>     增加了银瓜子换硬币的旧API兑换功能
>     增加了自动抽奖->总督领奖的功能
>     增加了自动抽奖->实物抽奖的功能
>     重新命名了自动抽奖功能，现为自动抽奖->礼物抽奖功能
>     增加了自动抽奖->礼物抽奖的自定义设置
>     修改了自动抽奖->礼物抽奖的检测方式
>     修改了自动抽奖->礼物抽奖的参与方式
>     降低了自动抽奖->礼物抽奖功能的内存占用
>     调整了浮动提示的位置
>     优化了设置界面的生成方式
>     移除了未实现的节奏风暴代码部分
>     在GreasyFork上恢复脚本
> ### 2018-05-19
>     更新API，优化代码，第二次尝试规避封号
> ### 2018-05-12
>     更新API相关，优化逻辑，尝试规避封号
> ### 2018-04-30
>     更新验证码识别算法，修复无法正常领取瓜子的问题
>     增加新的设置项
> ### 2018-03-31
>     更新总督API相关(缺少数据,功能未实装)
> ### 2018-03-10
>     在Github上创建脚本仓库
>     更新领取银瓜子的功能
> ### 2018-02-15
>     修正了节奏风暴有关功能的实现逻辑
>     在GreasyFork上删除脚本
> ### 2018-02-12
>     解决了不能在任意直播间参加抽奖的问题(实验性)(需在设置中勾选)
> ### 2018-02-10
>     修复了不能领取银瓜子的问题
> ### 2018-02-04
>     增加了银瓜子兑换硬币的功能
>     修改了默认设置
>     调整了设置界面的位置
> ### 2018-01-28
>     调整了设置界面
>     修改了送礼逻辑
> ### 2018-01-22
>     增加了可视设置界面和保存设置的功能
>     增加了新的设置项
>     移除了使用银瓜子送礼的功能
>     修复了会自动送出永久期限礼物的bug(未测试)
>     优化了领取瓜子信息的界面设计
>     优化了抽奖计时逻辑
> ### 2018-01-20
>     优化了抽奖功能，调整了浮动提示
> ### 2018-01-18
>     修复了不能正常参加新春抽奖的问题
> ### 2018-01-13
>     修复了领取宝箱的有关bug
> ### 2018-01-12
>     增加了自定义送礼等功能，优化了脚本逻辑
> ### 2018-01-09
>     修复了脚本不能运行的问题
> ### 2018-01-06
>     在GreasyFork上创建脚本

-----------------
