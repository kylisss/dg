---
dg-publish: true
dg-permalink: "/pages/cc-2022-09-20-110117/"
url: https://notes.oldwinter.top/obsidian-%E7%9B%AE%E5%89%8D%E6%9C%80%E5%AE%8C%E7%BE%8E%E7%9A%84%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E6%96%B9%E6%A1%88-%E6%B8%90%E8%BF%9B%E5%BC%8F%E6%95%99%E7%A8%8B
title: obsidian 目前最完美的免费发布方案 - 渐进式教程 — 🌱 oldwinter の数字花园
date: 2022-09-20
tag: 
- Obsidian技巧
summary: 可以访问此文的双链版本，获得完整阅读体验：obsidian 目前最完美的免费发布方案 - 渐进式教程 - 🌲 oldwinter の数字花园
---

> [!quote] 本文剪藏自[obsidian 目前最完美的免费发布方案 - 渐进式教程 — 🌱 oldwinterの数字花园](https://notes.oldwinter.top/obsidian-%E7%9B%AE%E5%89%8D%E6%9C%80%E5%AE%8C%E7%BE%8E%E7%9A%84%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E6%96%B9%E6%A1%88-%E6%B8%90%E8%BF%9B%E5%BC%8F%E6%95%99%E7%A8%8B)

可以访问此文的双链版本，获得完整阅读体验：[obsidian 目前最完美的免费发布方案 - 渐进式教程 - 🌲 oldwinter の数字花园](https://oldwinter.top/Calendar/%E5%B7%B2%E5%8F%91%E5%B8%83%E6%96%87%E7%AB%A0/obsidian+%E7%9B%AE%E5%89%8D%E6%9C%80%E5%AE%8C%E7%BE%8E%E7%9A%84%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E6%96%B9%E6%A1%88+-+%E6%B8%90%E8%BF%9B%E5%BC%8F%E6%95%99%E7%A8%8B)

## 几个发布方案对比

支持[双向链接](https://notes.oldwinter.top/%E5%8F%8C%E5%90%91%E9%93%BE%E6%8E%A5)是底线，否则随便用一个主流的静态 blog 方案就行了。

先看最终方案的发布页面效果： [🌱 oldwinter の数字花园](https://notes.oldwinter.top/)

![](https://img2.oldwinter.top/obsidian%20%E7%9B%AE%E5%89%8D%E6%9C%80%E5%AE%8C%E7%BE%8E%E7%9A%84%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E6%96%B9%E6%A1%88%20-%20%E6%B8%90%E8%BF%9B%E5%BC%8F%E6%95%99%E7%A8%8B_image_1.png)

和 obsidian 的官方发布方案做个对比：[🌲 oldwinter の数字花园](https://oldwinter.top/)

![](https://img2.oldwinter.top/obsidian%20%E7%9B%AE%E5%89%8D%E6%9C%80%E5%AE%8C%E7%BE%8E%E7%9A%84%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E6%96%B9%E6%A1%88%20-%20%E6%B8%90%E8%BF%9B%E5%BC%8F%E6%95%99%E7%A8%8B_image_2.png)

功能点详细比对：

<table><thead><tr><th>功能点和限制</th><th>jekyll 方案 1</th><th>官方收费发布方案</th><th>hugo 方案 (quartz)</th><th>logseq 方案</th></tr></thead><tbody><tr><td>反向链接面板</td><td>支持</td><td>支持</td><td>支持</td><td>支持</td></tr><tr><td>正向链接预览</td><td>支持</td><td>支持</td><td>支持</td><td>支持</td></tr><tr><td>支持搜索</td><td>不支持，但通过 google 间接实现</td><td>支持</td><td>支持，但中文不兼容</td><td>支持</td></tr><tr><td>链接稳定性</td><td>只要文件名不改，链接就稳定</td><td>受文件夹和文件名同时影响</td><td>只要文件名不改，链接就稳定</td><td>只要文件名不改，链接就稳定</td></tr><tr><td>文件夹层级显示</td><td>无</td><td>支持</td><td>无</td><td>无</td></tr><tr><td><span title="There is no note that matches this link."><span>[[</span> 首屏加载速度 <span>]]</span></span></td><td>极快，2s 内，下载资源 &lt; 1M</td><td>中等，5 秒内，下载资源 &lt; 5M</td><td>极快，2s 内，下载资源 &lt; 1M</td><td>超慢，10 秒，下载资源 &lt; 30M</td></tr><tr><td>图谱显示</td><td>支持全局图谱，但 1K + 笔记就很卡</td><td>完美支持</td><td>支持局部图谱，中文支持不友好</td><td>支持，稍卡</td></tr><tr><td><span title="There is no note that matches this link."><span>[[</span> 横向卷动布局 - andy mode <span>]]</span></span></td><td>不支持</td><td>支持</td><td>不支持</td><td>不支持</td></tr><tr><td>暗色模式支持</td><td>不支持</td><td>支持</td><td>支持</td><td>支持，但固定，不能切换</td></tr><tr><td><span title="There is no note that matches this link."><span>[[</span> SEO 优化 <span>]]</span></span></td><td>可被 google 自动收录</td><td>官方做了优化，收录优先级更高</td><td>可被 google 自动收录</td><td>google 好像不会收录单 html 的方案</td></tr><tr><td>移动端支持</td><td>支持</td><td>支持</td><td>支持</td><td>支持</td></tr><tr><td>markdown 扩展语法支持</td><td>支持基本 md 语法和<code>[[</code>语法及别名语法</td><td>支持 obsidian 的 callout 和别名语法</td><td>只支持基本 md 语法</td><td>只支持基本 md 语法和<code>[[</code>语法</td></tr><tr><td>评论留言系统</td><td>支持外挂第三方方案</td><td>目前第三方外挂方案都有问题</td><td>支持外挂第三方方案</td><td>支持外挂第三方方案</td></tr><tr><td>其他限制</td><td>必须要有 YAML 区</td><td>收费</td><td>必须要有 YAML 区；不支持<code>[[</code>wikilink 格式，需妥协</td><td>语法上需要一点克制</td></tr></tbody></table>

精力有限，就只对比这 4 种方案了。下面列上我目前体验对比过的全部第三方开源发布方案，供各位参考，也可以持续观察作者后续的开发进展，再择优选择。

*   jekyll 方案 1，即我选用的方案。[GitHub - maximevaillancourt/digital-garden-jekyll-template: Start your own digital garden using this Jekyll template 🌱](https://github.com/maximevaillancourt/digital-garden-jekyll-template)
*   jekyll 方案 2，[一位印度老哥写的](https://github.com/Jekyll-Garden/jekyll-garden.github.io)
*   hugo 方案 (quartz)，[jackyzha0 (Jacky Zhao) · GitHub](https://github.com/jackyzha0)
*   logseq 方案，[GitHub - pengx17/logseq-publish: Logseq Publish Action](https://github.com/pengx17/logseq-publish)
*   zola 方案，[GitHub - ppeetteerrs/obsidian-zola: A no-brainer solution to turning your Obsidian PKM into a Zola site.](https://github.com/ppeetteerrs/obsidian-zola)
*   perlite 方案，[GitHub - secure-77/Perlite: A webbased markdown viewer optimized for Obsidian](https://github.com/secure-77/Perlite)
*   gatsby 方案，支持 [[ 横向卷动布局 - andy mode ]]，但构建时长小时级别，[GitHub - aravindballa/gatsby-theme-andy: A Gatsby theme to build Andy style websites. 📑](https://github.com/aravindballa/gatsby-theme-andy/)
*   [2022-07-24](https://notes.oldwinter.top/2022-07-24) 新发现方案：[GitHub - mathieudutour/gatsby-digital-garden: 🌷 🌻 🌺 Create a digital garden with Gatsby](https://github.com/mathieudutour/gatsby-digital-garden/)

总之，有钱就选官方服务准没错。其次，综合对比后，我选择了 jekyll 方案 1，如何一步步实现，见下文。

[[2022-08-21 ]] 新增 [quartz](https://notes.oldwinter.top/quartz) 方案，已经成熟很多，比 jekyll 方案性能更好，还支持搜索。

## 渐进式教程

注：程序员朋友预估 10 分钟之内能搞定。纯小白也许需要花费 30 分钟以上。有能力的朋友，可以直接根据原作者的 readme 进行部署和发布，不需要看我的**汉化啰嗦版**😅

### 总的来说：

通过基于 [jekyll](https://notes.oldwinter.top/jekyll) 开源的静态 blog 模板，通过 [[ git push ]] 自动触发 [[ netlify ]] 进行构建操作，将 md 文件转换成静态服务器可以识别的 html 文件。

### 一步步来说：

*   1. 本地调试。
    *   fork 这个 jekyll 开源模板：[GitHub - oldwinter/dg](https://github.com/oldwinter/dg)
        *   有能力的朋友，建议 fork 原作者的，自己进行定制改动。
    *   `git clone`自己 fork 的仓库地址到你电脑本地：`git clone <YOUR_COPIED_URL_HERE> my-digital-garden`
    *   进入刚才 clone 的仓库的目录，`cd my-digital-garden`
    *   执行依赖库安装命令`bundle`
        *   bundle 是 [[ ruby ]] 的包管理器，所以可能还需要先安装 ruby 语言环境，请自行搜索教程。
        *   如果因为网络问题导致依赖库安装很慢，请自行搜索解决。
    *   执行本地调试命令`bundle exec jekyll serve`，接着浏览器打开`http://localhost:4000`看是否正常显示页面。
    *   将 obsidian 库全部要发布的文件用 linter 插件加上 YAML 格式的 [frontmatter](https://notes.oldwinter.top/frontmatter) 区，然后拷贝至`_notes_`目录。
        *   linter 插件支持一键对全库进行 markdown 格式美化，强烈推荐。⚠️执行前请先备份。
        *   有能力的朋友，可以直接将 obsidian 笔记库添加为 [git submodule](https://notes.oldwinter.top/git-submodule)。
    *   ctrl + c 停止`bundle exec jekyll serve`命令，并重新执行。接着浏览器打开`http://localhost:4000/笔记名`。例如我的 obsidian 笔记库里面有`数字花园`这条笔记，则访问`http://localhost:4000/数字花园`即可看到笔记。
*   2. [[ netlify ]] 配置自动构建。
    *   按照这个教程[手把手教你使用 Netlify 部署博客及部署自动化 - 知乎](https://zhuanlan.zhihu.com/p/55252024)，界面一步步点，都按默认配置来，从而将上一步 fork 的自己仓库，通过 netlify 构建和发布。
        *   主流的免费的还有 [github pages](https://notes.oldwinter.top/github-pages) 和 [[ vercel ]] 服务，前者缺少 [[ CDN ]] 导致国内访问很慢，后者存在非 html 后缀的链接报 404 错误的问题。
    *   完成上一步后，应该能得到一个`https://master--zippy-dango-d43c8d.netlify.app/`类似格式的网址，打开后正常显示原仓库的页面即可。
*   3. 将本地全部文件 push 至 github。
    *   本地仓库的根目录执行 git 三件套：`git add .` `git commit -m "first commit"` `git push`
        *   有能力的朋友，可以将这个步骤，用效率工具，包装成一个定时执行或一键执行的命令。
    *   回到 [[ netlify ]] 页面，应该能看到它开始被 push 操作触发了构建动作，等几分钟后，打开得到的新网址，看是否已经包含了 obsidian 笔记库内容，链接为`域名/笔记名`。例如我的 obsidian 笔记库里面有`数字花园`这条笔记，则访问`https://master--zippy-dango-d43c8d.netlify.app/数字花园`即可看到笔记。
*   4. 定制自己的首页、网站名和样式
    *   首页修改。修改`_pages`文件夹下的`index.md`即可，可直接参考 [dg/index.md at master · oldwinter/dg · GitHub](https://github.com/oldwinter/dg/blob/master/_pages/index.md)
    *   网站名修改。修改根目录的`_config.yaml`第一行 title 字段即可。
    *   有能力的同学，自己根据 jekyll 官方文档，定制自己的界面和样式即可。
    *   完整重复步骤 3，看更改是否生效。
*   5.⚠️重要注意事项
    *   图片推荐使用[图床](https://notes.oldwinter.top/%E5%9B%BE%E7%89%87%E4%BF%9D%E5%AD%98-%E5%9B%BE%E5%BA%8Aor%E6%9C%AC%E5%9C%B0)。若你未使用图床，而是使用本地图片。则需
        *   在 obsidian 库中，引用本地图片不使用`!<span title='There is no note that matches this link.' class='invalid-link'> <span class='invalid-link-brackets'>[[</span> xx.png <span class='invalid-link-brackets'>]]</span></span>`，而是使用`![](xx.png)`格式。
        *   在 [[ netlify ]] 的 Build Setting 的 Build command 设置中，将图片从 obsidian 的图片库移动至工程根目录，如`mv _notes/Extras . && jekyll build --trace`。
*   （可选）自定义自己的域名
    *   在 netlify 界面按提示一步步操作即可，需要有自己的域名且已经备案。
    *   [第一次购买并备案域名的经验](https://notes.oldwinter.top/%E7%AC%AC%E4%B8%80%E6%AC%A1%E8%B4%AD%E4%B9%B0%E5%B9%B6%E5%A4%87%E6%A1%88%E5%9F%9F%E5%90%8D%E7%9A%84%E7%BB%8F%E9%AA%8C)
    *   [DNS 解析](https://notes.oldwinter.top/dns%E8%A7%A3%E6%9E%90)
*   （可选）嵌入评论系统 [2022-08-17](https://notes.oldwinter.top/2022-08-17) 新增
    *   推荐用 giscus，不用自己折腾数据库这些烦人的东西。[博客的评论系统借用 github discussion 模块 - giscus](https://notes.oldwinter.top/%E5%8D%9A%E5%AE%A2%E7%9A%84%E8%AF%84%E8%AE%BA%E7%B3%BB%E7%BB%9F%E5%80%9F%E7%94%A8github-discussion%E6%A8%A1%E5%9D%97-giscus)

## 写在最后

我在践行 obsidian 笔记库全量开源的想法（代码能力不够，笔记来凑😂），欢迎捧场来赏赐 1 个 star⭐️：[GitHub - oldwinter/knowledge-garden: 真实袒露的第二大脑 second brain，未经美化的数字花园 digital garden](https://github.com/oldwinter/knowledge-garden)

### LINKS TO THIS PAGE

[本库如何免费发布至 web](https://notes.oldwinter.top/%E6%9C%AC%E5%BA%93%E5%A6%82%E4%BD%95%E5%85%8D%E8%B4%B9%E5%8F%91%E5%B8%83%E8%87%B3web)

将 obsidian 双链笔记公开发布到网上的实操方法：[[obsidian 目前最完美的免费发布方案 - 渐进式教程]]

[🏹 已发布长文](https://notes.oldwinter.top/%E5%B7%B2%E5%8F%91%E5%B8%83%E9%95%BF%E6%96%87)

up:: [[🍀 花园导览]] x:: [[Index for 已发布文章和草稿]]

[本库如何自动每日发布至 web](https://notes.oldwinter.top/%E6%9C%AC%E5%BA%93%E5%A6%82%E4%BD%95%E8%87%AA%E5%8A%A8%E6%AF%8F%E6%97%A5%E5%8F%91%E5%B8%83%E8%87%B3web)

将 obsidian 的笔记库以类似博客的方式发布至网络，目前本库采用了 2 个第三方免费方案，详见 [[obsidian 目前最完美的免费发布方案 - 渐进式教程]]。