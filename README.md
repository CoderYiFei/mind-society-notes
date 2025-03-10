# 马文·明斯基的心智社会理论读书笔记

> 这是一个关于马文·明斯基（Marvin Minsky）的心智社会理论的读书笔记，使用 docsify 构建并部署在 GitHub Pages 上。

## 关于本笔记

本笔记详细记录了马文·明斯基的心智社会理论，包括：

- 明斯基其人：生平、贡献与思维风格
- SNARC与神经网络研究
- 心智社会理论的核心概念
- 情绪机器与认知架构
- 思维的多元化与层次性

## 如何访问

本笔记已部署在 GitHub Pages 上，可通过以下链接访问：

[https://coderyifei.github.io/mind-society-notes/](https://coderyifei.github.io/mind-society-notes/)

## 维护指南

### 本地预览

```bash
# 安装 docsify-cli（如果尚未安装）
npm i docsify-cli -g

# 本地预览
docsify serve .
```

### 更新笔记

```bash
# 修改文件后（如 mind.md）
git add .
git commit -m "更新笔记内容"
git push
```

推送后，GitHub Actions 会自动重新部署网站。

### 检查部署状态

```bash
# 检查 GitHub Pages 状态
gh api /repos/CoderYiFei/mind-society-notes/pages
```

## 技术栈

- [docsify](https://docsify.js.org/) - 文档网站生成器
- GitHub Pages - 静态网站托管
- GitHub Actions - 自动部署
