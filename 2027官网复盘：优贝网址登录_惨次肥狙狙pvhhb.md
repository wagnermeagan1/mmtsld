优贝网址登录【Q-——333307——】优贝网址登录【 辋芷《888yx●vip》 】
优贝网址登录【Q-——333307——】优贝网址登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：我用 GitHub Pages + Hexo 实现了自动化部署

你是不是也想过搭建一个属于自己的技术博客，却总是卡在“买服务器、配环境、折腾域名”这些步骤上？其实，用 GitHub Pages 免费托管 + Hexo 静态生成，30 分钟就能搞定一个清爽、高速、可自动部署的博客站。

 为什么选择 GitHub Pages？

- 完全免费：无需云服务器，直接使用 GitHub 提供的静态托管服务。
- Git 原生工作流：写文章就是提交代码，天然支持版本管理。
- CDN 加速：全球节点分发，国内访问速度也还不错。
- 绑定自定义域名：支持在仓库设置里一键配置 CNAME。

 Hexo 是什么？

Hexo 是一个基于 Node.js 的静态博客框架。你只需要写 Markdown 文件，它就能帮你生成一套完整的 HTML 网页。配合 Git 钩子，可以实现 `git push` 后自动发布。

 自动化部署三步走

1. 本地初始化：安装 Node.js 后，执行 `npm install hexo-cli -g`，然后 `hexo init blog` 初始化项目。
2. 连接仓库：在 GitHub 新建一个 `<你的用户名>.github.io` 的仓库，并在 `_config.yml` 中配置仓库地址。
3. 配置 GitHub Actions：在项目根目录创建 `.github/workflows/deploy.yml`，写入部署脚本。每次你推送代码到主分支，Actions 会自动执行构建和发布。

 常见问题排查指南

- 部署失败：检查 Actions 日志中是否缺少 `package-lock.json`，或者 Node 版本是否过旧。
- 图片不显示：建议用相对路径引用图片，并确保资源存放在 `source/images` 下。
- 百度收录慢：在 `source` 目录下新建 `baidusitemap.xml`，并主动到百度站长平台提交链接。

 互动引导

你在搭建博客时遇到过最头疼的问题是什么？是主题配置、评论系统接入，还是 SEO 优化？欢迎在评论区留言，我会针对高频问题出详细的实战教程。如果你觉得这篇文章对你有帮助，可以点个赞让更多同学看到，也可以先收藏起来，动手搭建时就能直接对照操作了。

> 想获取完整版 `deploy.yml` 脚本？关注我后私信“博客”即可领取。

相关推荐：

https://github.com/roybrooke50/psvpjz/blob/main/2027%E6%9D%83%E5%A8%81%E7%A7%91%E6%99%AE%EF%BC%9A%E4%BC%98%E8%B4%9D%E5%9C%B0%E5%9D%80%E5%B9%B3%E5%8F%B0_%E6%9D%96%E8%86%9B%E6%8E%A8%E9%92%A2%E9%97%ADuhboc.md

<img src="https://i.postimg.cc/g2g50LWJ/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(89).png" />

相关推荐：

https://github.com/roybrooke50/psvpjz/commit/736427c9e4dc16612907ce72280f7800bc4f9fc1

<img src="https://i.postimg.cc/ncZwYGVR/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(94).png" />
相关推荐：

https://github.com/jeffersonteresa2/jbemnb/blob/main/2027%E6%9D%83%E5%A8%81%E8%AE%B2%E8%A7%A3%EF%BC%9A%E4%BC%98%E8%B4%9D%E5%9C%B0%E5%9D%80%E6%B3%A8%E5%86%8C_%E6%89%98%E4%BB%B2%E9%A5%B2%E6%9D%8F%E9%92%A0qphaa.md

<img src="https://i.postimg.cc/JhMytj62/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(1).png" />
相关推荐：

https://github.com/jeffersonteresa2/jbemnb/commit/05c5626c38f8d1bdb9f5cc97b4a75fb032ba888f

<img src="https://i.postimg.cc/HkYRH4fm/mei-nu-bei-jing-zhao-shang-tu-zhi-zuo-(88).png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
