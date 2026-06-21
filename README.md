# 日程管理应用

基于原生 HTML/CSS/JS 的日程管理工具，数据通过 GitHub API 同步到私有仓库。

## 功能

- 日历视图（月/周/年三视图）
- 日程管理（事件/约定）
- 待办管理（完成/未完成，7组分类）
- 便签（Markdown + 标签自动补全）
- 保险箱（AES-GCM 加密）
- 垃圾箱（恢复/彻底删除）
- 深色/亮色双主题
- GitHub 云端同步

## 技术

- 纯原生 HTML/CSS/JS，无框架依赖
- localStorage 本地存储
- GitHub API 云端同步（PBKDF2 + AES-GCM 加密）
- 响应式布局

## 使用

直接用浏览器打开 `index.html`，或在设置页配置 GitHub 同步实现多端数据同步。
