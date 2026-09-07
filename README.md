# 个人工作台 Personal Workbench

单文件离线个人管理工作台，数据保存在浏览器 localStorage，不上传任何服务器。

## 访问入口

- **手机版（PWA，可添加到主屏幕）**：`https://<用户名>.github.io/personal-workbench/workbench-mobile.html`
- **桌面版**：`https://<用户名>.github.io/personal-workbench/workbench-desktop.html`

## 功能

- 日志记录、每日计划
- 习惯打卡
- 记账
- 长期目标管理

## 技术说明

- `workbench-mobile.html` — 手机版（PWA）
- `workbench-desktop.html` — 桌面版
- `manifest.json` — PWA 配置
- `sw.js` — Service Worker 离线缓存
- `assets/` — 图标、背景图、默认头像

所有数据仅存储在本地浏览器中，清除浏览器数据前请注意备份。
