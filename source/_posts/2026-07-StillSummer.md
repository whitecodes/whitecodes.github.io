---
title: 依旧在夏天
date: 2026-08-02 23:05:30
tag:
- Life
- App
- LLM
---
写的时候天气还是很热，以为还是在夏天的鼎盛中间的位置。看了最近的节气，更接近秋天，但是气象上还是在夏天。

大概是流水账，记录下这个周末。

<!--more-->
## 白嫖的大模型

大模型上基本上没有花过钱。
更早的时候，用的是[云雾中转站](https://yunwu.ai/register?aff=gJNI)。有每日签到，每次签到送大概0.3的额度。每天签到，隔几天就可以用一阵。
小米推出了[MiMo Code](https://mimo.xiaomi.com/coder)，Auto模型是免费的，用了一阵，Siren 的初始代码是用它写的。但是经常性地没有响应。
后来用 mimo-proxy 把模型代理给 claude 使用，基本上完成了 Siren 的功能。
一段时间后，小米加强了检测，mimo-proxy 失效了。
尝试换用云雾中转站的DeepSeek-v4-flash,但是不支持 A\ 的接口形式，上[cli-proxy-api](https://github.com/router-for-me/CLIProxyAPI)转发解决了。
然后就发现了新问题，缓存率太低了，大概是固定的缓存大小。虽然中转站便宜，但是缓存率低，签到送的额度很快用完了。
换了[PackyCode](https://www.packyapi.com/register?aff=VyC7)中转站，不需要cli-proxy-api转发了，缓存率正常了，大致在99%。为了查看这个缓存率，还折腾了claude的statusline,在输入框下面显示缓存率。
PackyCode注册送的1元额度3天花完了，考虑充值。看到50起充，犹豫了。
对比了中转站和[DeepSeek官方](https://platform.deepseek.com/)的，先在官网充值了5块钱。这也是唯一花的钱。
继续改了statusline直接显示余额。
今天在[S1论坛](https://stage1st.com/2b/forum.php?mod=viewthread&tid=2286754)看到了[基元律动邀请注册](https://tokenrhythm.studio/i/rf_tr_CjXLWTKT4Xmn7xnuLJajTGtj)直接送68额度。注册下。由DeepSeek提供，白天看到的还只有预览版。晚上已经上了正式版。
正好想尝试一下其他code agent,用 grok-build 来接入。
中午的时候刚接入，下午的时候就用到了。

## Garmin 同步到 Pokemon Sleep

又是睡眠数据同步的问题。在凌晨更新Garmin Connect版本后就是没有往Health Connect中写入过。尝试了重启应用、清除数据、回退到上个版本、回退到上个月版本，都不行。
直接让grok-build跑诊断。跑之前切换了代理出口。grok-build在强制重启Garmin Connect后，发现Health Connect的选项又出现了。然后就可以同步了。
总结还是网络出口的问题。之后不升级Garmin Connect了。
用的过程中，因为显示了思考过程，就看到字符在刷新滚动，感觉很快。
不花钱的继续用着。

## 彩虹与香锅
傍晚临近落日的时候出门骑车，在返回的时候看到了彩虹。
记忆中是第一次看到彩虹。
而且之前还没有下雨。
回来之后久违地去吃了香锅。不算特别好吃，不香。价格也比记忆中的贵，31的一份香锅+饮料+米饭。
吃香锅的时候要了冰可乐，一口下去，胸口都凉了，差点以为自己要死了。
