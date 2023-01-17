<h2 align="center">
四象giscus服务
</h2><br>



## 👋 介绍
四象giscus服务基于💎<a href="https://giscus.app/zh-CN">giscus</a>，为<a href="https://sixiang.world">四象世界</a>提供评论服务

## ✨ giscus特点

- <a href="https://github.com/giscus/giscus">开源</a>。🌏
- 无跟踪，无广告，永久免费。📡 🚫
- 无需数据库。全部数据均储存在 GitHub Discussions 中。
- 支持**自定义主题**！🌗
- 支持**多种语言**。🌐
- **高度可配置**。🔧
- 自动从 GitHub 拉取新评论与编辑。🔃
- **可自建服务**！🤳


## 🖥️ 运作方式

giscus 加载时，会使用 [GitHub Discussions 搜索 API][search-api] 根据选定的映射方式（如 URL、`pathname`、`<title>` 等）来查找与当前页面关联的 discussion。如果找不到匹配的 discussion，giscus bot 就会在第一次有人留下评论或回应时自动创建一个 discussion。
