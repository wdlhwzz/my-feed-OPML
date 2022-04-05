**<p align="center">[My Feedly OPML](https://github.com/wdlhwzz/my-feed-OPML)</p>**
====

## 前言

**分享我订阅的一些 Blog 和 Newsletter，每天自动同步我 Feedly 上的订阅源，✅ 代表能正常订阅，❌ 代表暂无法订阅（对于无法订阅的 feed，支持 Telegram Bot、Email、Server酱等推送工具提醒更新），**[opml 下载地址](https://github.com/wdlhwzz/my-feed-OPML/releases/download/latest/feed.opml)

**最新更新时间（北京时间）：2022-04-05 09:24:57**

## 如何使用

- fork 本仓库

- 在 `Settings --> Secrets --> Actions` 下新增如下的几个 secrets：
   - **FEEDLY_TOKEN**：**必须**，你的 Feedly token，访问 [https://feedly.com/v3/auth/dev](https://feedly.com/v3/auth/dev)，创建一个开发者 token
   - **G_TOKEN**：**必须**，你的 [Github Token](https://github.com/settings/tokens/new)，scope 不知道选啥，就全部勾上，然后拷贝生成的 token
   - **TG_CHAT_ID**：可选，你的 Telegram user id，关注机器人 [@getuseridbot](https://t.me/getuseridbot) 即可获取
   - **TG_TOKEN**：可选，你的用于接收通知的 telegram bot 的 token，如何创建 Telegram Bot，见搜索引擎
   - **EMAIL**：可选，你的用于接收通知的邮箱
   - **EMAIL_PASS**：可选，你的邮箱授权密码
   - **EMAIL_HOST**：可选，邮箱协议
   - **SC_KEY**：可选，Server酱的 secret key

- 修改 `feedly_opml_import.yml`，修改如下的配置项为你自己的 Github userName 和 Email：
   ```yml
   env:
    GITHUB_NAME: superleeyom
    GITHUB_EMAIL: 635709492@qq.com
   ```
  
- 然后 `Actions --> Workflows --> FeedlyOpmlImportApplication --> Run workflow`，手动触发任务


Newsletter
----------
- [✅ 增长黑客通讯周刊](https://us6.campaign-archive.com/feed?u=e4582460499f4aadae1a90e2b&id=d2c14f8a94)：[feed](https://us6.campaign-archive.com/feed?u=e4582460499f4aadae1a90e2b&id=d2c14f8a94)
- [✅ iOS摸鱼周报](https://zhangferry.com/)：[feed](https://zhangferry.com/atom.xml)
- [✅ 前端食堂技术周刊](https://github.com/Geekhyt/weekly/issues)：[feed](https://rsshub.app/github/issue/Geekhyt/weekly)
- [✅ 前端精读周刊](https://github.com/ascoders/weekly/releases)：[feed](https://github.com/ascoders/weekly/releases.atom)
- [✅ 混沌周刊](https://weekly.love)：[feed](https://weekly.love/feed/atom/)
- [✅ 13的Apple開發者週報](https://ethanhuang13.substack.com)：[feed](https://ethanhuang13.substack.com/feed/)
- [✅ HelloGitHub月刊](https://hellogithub.com)：[feed](https://hellogithub.com/rss)
- [✅ 编程狂人周刊](https://www.tuicool.com/mags)：[feed](http://www.tuicool.com/mags/rss_programming.rss)
- [✅ 阿里云前端技术周刊](https://github.com/aliyunfe/weekly/releases)：[feed](https://github.com/aliyunfe/weekly/releases.atom)
- [✅ 好工具周刊](https://discuss-cn.bestxtools.com/)：[feed](https://discuss-cn.bestxtools.com/atom/t/weekly/discussions)
- [✅ GeekPlux Lab](https://geekplux.com)：[feed](https://geekplux.com/feed.xml)
- [✅ Newlearnerの自留地](https://t.me/s/NewlearnerChannel)：[feed](https://rsshub.app/telegram/channel/NewlearnerChannel)
- [✅ 野生架构师周刊](http://weekly.codelc.com/)：[feed](http://weekly.codelc.com/?format=rss)
- [✅ 少数派](https://sspai.com)：[feed](https://sspai.com/feed)
- [✅ DecoHack周刊](https://www.decohack.com)：[feed](https://www.decohack.com/feed)
- [✅ 产品鸭](https://produck.zhubai.love/)：[feed](https://rsshub.app/zhubai/produck)
- [✅ 老司机iOS周报](https://github.com/SwiftOldDriver/iOS-Weekly/releases)：[feed](https://github.com/SwiftOldDriver/iOS-Weekly/releases.atom)
- [✅ Things About Design](https://design.zhubai.love/)：[feed](https://rsshub.app/zhubai/design)
- [✅ Go语言爱好者周刊](https://studygolang.com/go/weekly)：[feed](https://rsshub.app/go-weekly)
- [✅ 独立开发变现周刊](https://www.ezindie.com/weekly)：[feed](https://www.ezindie.com/feed/rss.xml)
- [✅ 奇舞周刊](https://weekly.75.team)：[feed](https://weekly.75.team/rss)

Blog
----
- [✅ iPotato](https://ipotato.me)：[feed](http://ipotato.me/feed)
- [✅ Eason Yang's Blog](https://easonyang.com/)：[feed](https://easonyang.com/atom.xml)
- [✅ 阮一峰的网络日志](http://www.ruanyifeng.com/blog/)：[feed](http://feeds.feedburner.com/ruanyifeng)
- [✅ 王登科的博客](https://greatdk.com)：[feed](https://greatdk.com/feed)
- [✅ forecho's Blog](https://blog.forecho.com/)：[feed](http://blog.forecho.com/atom.xml)
- [✅ Limboy](https://limboy.me)：[feed](https://limboy.me/index.xml)
- [✅ Leeyom's Blog](https://github.com/superleeyom/blog)：[feed](https://raw.githubusercontent.com/superleeyom/blog/master/feed.xml)
- [✅ 唐巧的博客](https://blog.devtang.com/)：[feed](http://blog.devtang.com/atom.xml)
- [✅ 马大伟](https://www.bmpi.dev/)：[feed](https://www.bmpi.dev/index.xml)
- [✅ Shyrism](https://shyrz.me/)：[feed](https://shyrz.me/rss/)
- [✅ crossoverJie's Blog](http://crossoverjie.top/)：[feed](https://crossoverjie.top/atom.xml)
- [✅ 程序员的喵](http://catcoding.me/)：[feed](https://catcoding.me/atom.xml)
- [✅ 美团技术团队](https://tech.meituan.com/feed/)：[feed](http://tech.meituan.com/atom.xml)
- [✅ 代码家](https://daimajia.com)：[feed](https://daimajia.com/feed)
- [✅ OneV's Den](https://onevcat.com)：[feed](http://www.onevcat.com/rss/)
- [✅ yihong0618](https://github.com/yihong0618/gitblog)：[feed](https://raw.githubusercontent.com/yihong0618/gitblog/master/feed.xml)
- [✅ codedump的网络日志](https://www.codedump.info/)：[feed](https://www.codedump.info/index.xml)
- [✅ bang’s blog](http://blog.cnbang.net)：[feed](http://feeds.feedburner.com/webbang)
- [✅ DIYgod](https://diygod.me/)：[feed](https://diygod.me/atom.xml)
- [✅ hayami's blog](https://hayami-blog.typlog.io/)：[feed](https://hayami-blog.typlog.io/feed.xml)
- [✅ 云风的BLOG](https://blog.codingnow.com/)：[feed](http://blog.codingnow.com/atom.xml)
- [✅ meditic的博客](https://meditic.com)：[feed](https://meditic.com/feed)
- [✅ 左耳朵耗子](https://coolshell.cn)：[feed](http://coolshell.cn/feed)
- [✅ 龙爪槐守望者](http://www.ftium4.com/)：[feed](http://www.ftium4.com/rss.xml)
- [✅ TualatriX](http://imtx.me/)：[feed](http://imtx.me/feed/latest/)
- [✅ Randy's Blog](https://lutaonan.com/)：[feed](https://lutaonan.com/rss.xml)

