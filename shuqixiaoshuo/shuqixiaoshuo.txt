🔔脚本说明

获取cookie会有很多的问题,目前会碰到的一些问题...说明以及细节部分都在说明和食用方法里面了,请自行先尝试看看...

1.目前适配最新版本：一般版本是4.3.6，极速版本：1.0.3

2.三月九号,一般版本更新至4.3.6,移除了福利转转转的【看视频抽奖】选项,因此每次抽奖需要耗费100金币,Cookie直接获取【一般-转盘抽奖】即可

2.1如果你的版本有看视频抽奖,可以免费抽奖不用耗费100金币,用转盘重写引用获取，或者自行抓包填入BOXJS-luckylotterybody部分。

3.一般版本阅读挑战赛需要手动报名，脚本内置刷180分钟停止或者”自行到BOXJS设定360分钟”，如果刷时长的bug没有失效，三个等级的任务都一定可以完成，但是建议不玩,性价比低。

3.1报名需要花费不等的金币,如果不满足挑战条件，金币会直接被扣除，如果有天刷时长的bug失效，会直接损失报名的金币。

3.2报名最高等级的场次(阅读180min)，收益也才550-650金币左右,但是报名费要10000金币

3.3有时会出现已满足条件（挑战成功），但是隔天领取不到奖励被扣除报名费的状况，这时候需要继续报名相同场次...才可以获取奖励到账。

4.刷阅读时长在极速版本,由于cookie每日失效必须重新获取,可以考虑不关重写引用,每天记得小说看三圈,重新去获取阅读时长。脚本执行可以看目前抓阅读时长的秒数。

5.脚本任务有判定机制，因此只执行一次，没有循环执行;定时每“4分钟”循环执行一次（24hr*(60/4)=360)，这样可以自定义自己每次任务的间隔时间,如果想快点就设置cron短一些。

6.第一次下载APP,书旗有个奇怪的机制,一般都要先手动玩一天或者两天才会正常...

6.1 如果一般版本阅读小说右上角没有圈圈，删除APP重新下载也许就会有了,如果还是没有,那就是官方的问题,明天也许就可以出来...或者考虑爱思下载4.3.0版本(感谢群友建议)

6.2 极速版也许没有视频看,如果关了代理软件还是没有,那就是官方的问题,明天也许就可以加载视频出来...




🔔信息

【BOXJS】: https://raw.githubusercontent.com/CenBoMin/GithubSync/main/cenbomin.box.json
【脚本定时cron】: */4 * * * *
【刷时长定时cron】: 根据获取时长自定义,一般为 */6 * * * *
【脚本JS】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/shuqi.js
【刷时长JS】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/shuqireadtime.js
【1.一般版-重写引用】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/cookie.conf
【2.极速版-重写引用】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/spcookie.conf
【3.一般版-福利转转转-重写引用】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/lottery.conf
【4.极速版-刷时长-重写引用】:https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/everday.conf

//食用方法：

📌温馨提示1:启动重写引用获取cookie时务必要确认重写引用是不是生效(圈x左上角有红色数字圈圈)，通常会因为raw连接需要代理而出错，所以启用更新的时候不要用直连模式！

📌温馨提示2:视频加载出错,采用全部直连模式,圈x右下角圈圈,改成黄色的就是直连模式了！

📌请先添加以上四个重写引用，在依照以下说明依序获取cookie。。。

📌非常重要！非常重要！非常重要！:
每次只可以启用一个重写引用conf,获取完cookie,务必关闭当前重写引用conf!在启用下一个重写引用conf。否则cookie抓取会出错,导致脚本执行错误，4个重写引用,绝对不可以同时开启两个，只可以一个！！！！！！！⭐️是也许获取会发生问题的,特别注意说明！！获取不到或者出错的,参照最底下的BOXJS对照表重新获取

1.一般版本,请添加重写获取cookie：https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/cookie.conf

✅【一键收取】:登录App-点击下方中间【福利】- 有气泡可以收取，点击招财猫中间图标【做任务赚金币】,即可获取成功
✅【一般-签到打卡】:登录App-点击下方中间【福利】- 点击【每日签到】 - 立即签到,即可获取成功
⭐️【一般-阅读金币】:登录App-点击下方中间【福利】- 点击【30秒计时奖励】 - 找一本书点进去 -往右滑动看书 - 右上角会出现一个圈圈 -持续看书到获取金币,即可获取成功
✅【一般-看视频金币】:登录App-点击下方中间【福利】- 点击【看视频领金币】- 看完一篇视频广告,即可获取成功
⭐️【一般-邀请书友】:登录App-点击下方中间【福利】- 点击【邀请书友】,分享到微信朋友圈 - 分享完成返回app,如果提示网路错误或者没有获取到，就继续分享朋友圈返回，大约三次奖励成功就可以获取到了

2.极速版本,请添加重写获取cookie：https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/spcookie.conf

✅【极速-签到打卡】:登录App-点击下方中间【福利】-点击右侧图标【每日签到】- 立即签到,即可获取成功
✅【极速-阅读小说金币】:登录App-点击下方中间【福利】-点击左侧图标【赚金币】- 点击【30秒计时奖励】 - 找一本书点进去 -往右滑动看书 - 右上角会出现一个圈圈 -持续看书到获取金币,即可获取成功
⭐️【极速-看视频金币】:登录App-点击下方中间【福利】-点击左侧图标【赚金币】-点击【看视频领金币】- 看完一篇视频广告,即可获取成功
✅【极速-邀请书友】:登录App-点击下方中间【福利】-点击左侧图标【赚金币】-点击【邀请书友】,分享到微信朋友圈 - 分享完成返回app,即可获取成功

3.一般版本-福利转转转，极速版本-浏览书城，极速版本-签到页面看视频,请添加重写获取cookie：https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/lottery.conf
✅【一般-转盘机会】:登录App-点击下方中间【福利】-点击左侧图标【福利转转转】-点击下方【看视频抽奖】- 看完一篇视频广告,即可获取成功
⭐️【一般-转盘抽奖】:登录App-点击下方中间【福利】-点击左侧图标【福利转转转】-点击下方【金币抽奖】- 即可获取成功,如果，没有获取到，多试几次就可以
✅【极速-浏览书城15秒】:登录App-点击下方中间【福利】-点击左侧【赚金币】-点击【浏览书城】-右下角有计时-滑动或者停止会倒数计时,直到归零获取奖励,即可获取成功

4.极速版-刷时长，请添加重写获取cookie：https://raw.githubusercontent.com/CenBoMin/GithubSync/main/SHUQI/everday.conf
✅【极速-获取阅读时长】:登录App - 找一本书点进去 -往右滑动看书 - 右上角会出现一个圈圈 -持续看书至少6圈，保证看书三分钟，点击中间，左上角退出,即可获取成功
⭐️【极速-签到页面看视频】:登录App-点击下方中间【福利】-点击右侧图标【每日签到】，如果签到完成会弹出看【视频拿金币】，看完一篇视频广告,即可获取成功


🔔BOXJS cookie对照表

"readuploadbody":everday.conf✅【极速-获取阅读时长】
"readuploadkey":everday.conf✅【极速-获取阅读时长】
"boxtaskbody":cookie.conf,阅读时长判定Key，隐藏(一般福利页面)
"boxtaskkey":cookie.conf,阅读时长判定Key，隐藏(一般福利页面)
"loadresourcebody":cookie.conf,一般任务判定Key，隐藏(一般福利页面)
"loadresourcekey":cookie.conf,一般任务判定Key，隐藏(一般福利页面)
"sploadresourcebody":spcookie.conf,极速任务判定Key，隐藏(极速福利页面)
"sploadresourcekey":spcookie.conf,极速任务判定Key，隐藏(极速福利页面)
"withdrawbody":cookie.conf,钱包信息，隐藏(福利页面)
"bubblebody":cookie.conf,气泡信息，隐藏(福利页面)
"receivebody":cookie.conf✅【一键收取】
"signinactionbody":cookie.conf✅【一般-签到打卡】
"readlotterybody":cookie.conf✅【一般-阅读金币】
"videolotterybody":cookie.conf✅【一般-看视频金币】
"luckylotterybody":lottery.conf❎【一般-转盘机会】
"luckyredurl":lottery.conf❎【一般-转盘抽奖】
"luckyredbody":lottery.conf❎【一般-转盘抽奖】
"sharebody":cookie.conf❎【一般-邀请书友】
"booktaskurl"lottery.conf✅【极速-浏览书城15秒】
"booktaskbody"lottery.conf✅【极速-浏览书城15秒】
"spsigninactionbody":spcookie.conf❎【极速-签到打卡】
"spreadcoinurl":spcookie.conf✅【极速-阅读小说金币】
"spreadcoinbody":spcookie.conf✅【极速-阅读小说金币】
"sp1videocoinbody":spcookie.conf✅【极速-看视频金币】
"sp2videocoinbody":everday.conf✅【极速-签到页面看视频】
"spsharebody":spcookie.conf✅【极速-邀请书友】
"lotteryinfourl":lottery.conf,一般转盘任务判定Key，隐藏(一般转盘页面)
"videoinfourl":cookie.conf,一般视频任务判定Key，隐藏(一般福利页面)
"spvideoinfourl":spcookie.conf,极速视频任务判定Key，隐藏(极速福利页面)

🔔Q&A 问题与解答
❓有自动提现吗？
等大佬们pr。。。目前没有,只能查看提现任务资格是否满足

❓出现TypeError: undefined is not an object (evaluating 'data.data.ShuqiBsDailyTask.list')错误？
一般为四个cookie有问题,根据对照表重新获取...脚本执行有检查cookie，也可以看是那个cookie检查报错来重新获取
"loadresourcebody":cookie.conf,一般任务判定Key，隐藏(一般福利页面)
"loadresourcekey":cookie.conf,一般任务判定Key，隐藏(一般福利页面)
"sploadresourcebody":spcookie.conf,极速任务判定Key，隐藏(极速福利页面)
"sploadresourcekey":spcookie.conf,极速任务判定Key，隐藏(极速福利页面)

❓阅读挑战赛在哪？
在一般版本福利页面的左侧，有个黄金🏆写着阅读挑战赛，自己考虑要不要报名参加

❓为什么我获取了福利转转转的看视频抽奖,但执行还是被扣了100金币？
由于扣100金币和免费抽奖的请求不同需要重新获取以下两个cookie
"luckyredurl":lottery.conf❎【一般-转盘抽奖】
"luckyredbody":lottery.conf❎【一般-转盘抽奖】

❓为什么一般版本阅读小说没有圈圈？
应该是官方安全机制，考虑爱思下载4.3.0版本(感谢群友建议)，或者过几天就有

❓为什么极速版本签到页面或者视频页面加载视频失败看不了？
应该是官方安全机制，先尝试关掉代理软件尝试,如果还是没有,那就是官方的问题,明天也许就可以加载视频出来。。。等等

❓有没有支持多账号？
目前五个，没考虑在加...
