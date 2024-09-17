# Vito's Clip

这里会保存我平时阅读的文章的 Markdown 全文，如果是英文文章的话，会有中文的译文附在每个段落后面，只保存我觉得值得收藏的。

## 目录

<!-- Table of Content-->

## 我的大概收集流程

1. 浏览网页，比如 <https://www.owenyoung.com/inspires/>
2. 如果是英文文章，我使用 [Immersive Translate](https://github.com/immersive-translate/immersive-translate) 扩展将网页翻译为双语，然后再用这个 [markdownload](https://github.com/theowenyoung/markdownload) 扩展，把双语文章保存下来。
3. 使用 Git 把本地文件同步到远程仓库
4. 使用[Github Actions](https://github.com/theowenyoung/clip/blob/main/.github/workflows/build-site.yml) 自动发布网页到 [Cloudflare Pages](https://pages.cloudflare.com/)

## 复制该项目

如果你也想按照该项目的方式来收集和发布你的网页，我已经将这个项目抽出来一个模板，请参见模板项目的[说明文档](https://github.com/theowenyoung/clip-template)进行操作。

## RSS 订阅

可以通过 RSS 订阅最新的文章： <https://clip-vito.vercel.app/feed.xml>