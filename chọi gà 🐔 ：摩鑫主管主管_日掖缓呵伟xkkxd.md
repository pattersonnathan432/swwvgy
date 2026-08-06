摩鑫主管主管【Q-——333307——】摩鑫主管主管【 辋芷《888yx●vip》 】
摩鑫主管主管【Q-——333307——】摩鑫主管主管【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：GitHub Pages + Hexo 完整教程

> 还在羡慕别人的技术博客？其实你用 GitHub 就能免费搭建一个属于自己的博客网站。本文手把手教你从零开始，无需购买服务器，无需懂后端，跟着做就能上线。

 为什么选择 GitHub Pages 搭建博客？

很多人问我："新手写技术博客，用什么平台最好？" 我的答案一直是：GitHub Pages + Hexo。

这个组合有四个无可替代的优势：

1. 完全免费：托管在 GitHub 服务器上，不花一分钱
2. 极致速度：CDN 加速，国内访问也很快
3. 版本管理：所有文章都有 Git 历史记录，改错了能回滚
4. 高度定制：主题丰富，支持自定义域名，代码高亮完美

 前期准备：5分钟搞定环境

在开始之前，你需要准备三样东西：

- GitHub 账号（没有的话先去注册）
- Node.js（建议安装 LTS 版本，官网直接下载）
- Git（Windows 用户安装 Git Bash）

打开终端，输入以下命令验证环境是否就绪：

```bash
node -v     检查Node.js版本
git --version   检查Git版本
```

看到版本号输出，说明环境没问题，我们继续。

 三步走：从零到部署上线

 第一步：创建 GitHub 仓库

登录 GitHub，点击右上角"+"号，选择 New repository。仓库名必须写成 `你的用户名.github.io` 的格式。比如你的用户名是 `zhangsan`，仓库名就是 `zhangsan.github.io`。记得勾选 Public 可见性。

 第二步：本地初始化 Hexo 博客

在终端依次执行以下命令：

```bash
npm install -g hexo-cli           全局安装Hexo
hexo init my-blog                  初始化博客项目
cd my-blog                         进入项目目录
npm install                        安装依赖
hexo s                            启动本地服务
```

打开浏览器访问 `http://localhost:4000`，看到默认博客页面，说明本地搭建成功。

 第三步：部署到 GitHub

修改项目根目录下的 `_config.yml` 文件，找到 `deploy` 字段，改成你的仓库地址：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后执行部署命令：

```bash
npm install hexo-deployer-git --save    安装部署插件
hexo d -g                                生成并部署
```

等待几分钟，访问 `https://你的用户名.github.io`，你的博客就已经上线了！

 进阶优化：让博客更好看

博客上线只是开始，想让它更专业，你可以继续做这几件事：

1. 换主题：去 [Hexo Themes](https://hexo.io/themes/) 挑一个喜欢的，下载到 `themes` 文件夹，修改 `_config.yml` 里的 `theme` 字段即可
2. 绑定域名：买一个域名，在仓库 Settings > Pages 里配置自定义域名
3. 添加评论：集成 Giscus 或 Valine，让读者能和你互动

 你的下一步行动

现在你已经拥有自己的技术博客了。建议从今天开始，坚持每周写一篇技术笔记。写作是最好的学习方式——输出倒逼输入，你会在写作过程中发现自己知识的盲区。

遇到问题卡住了？别慌，去搜索引擎搜"Hexo 报错 + 错误信息"，几乎所有坑都有人踩过。

---

动手试试吧，花一个下午的时间，搭建一个完全属于你的技术博客。如果你成功了，欢迎在评论区分享你的博客链接，我去给你点赞！有任何问题也欢迎留言，我看到会回复。

收藏这篇文章，下次搭建时直接照着操作。你离技术大牛只差一个博客的距离。

相关推荐：

https://github.com/rossmarissa09/kqyzhh/blob/main/ch%E1%BB%8Di%20g%C3%A0%20%F0%9F%90%94%20%EF%BC%9A%E6%91%A9%E6%9D%B0%E6%B3%A8%E5%86%8C%E7%BD%91%E5%9D%80_%E5%AE%98%E9%83%BD%E7%94%B7%E6%BC%B3%E5%91%B3jcivu.md

<img src="https://i.postimg.cc/h472WgYT/moxin-00009.png" />

相关推荐：

https://github.com/rossmarissa09/kqyzhh/commit/8c7d8b4ea374a7a909adadabe36d207e275a2375

<img src="https://i.postimg.cc/VvMgjBM6/moxin-00008.png" />
相关推荐：

https://github.com/meltonkatie17/ttppes/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%91%A9%E6%9D%B0%E6%B3%A8%E5%86%8C%E5%AE%A2%E6%9C%8D_%E9%9C%96%E7%BC%AE%E5%91%80%E5%83%96%E6%B7%AEulyzt.md

<img src="https://i.postimg.cc/BQ9MJk90/moxin-00015.png" />
相关推荐：

https://github.com/meltonkatie17/ttppes/commit/aaee38cd89bc29015fd053202f60a19f65b5c60c

<img src="https://i.postimg.cc/cCYhQM3T/moxin-00002.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
