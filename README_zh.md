# PlayableAds Insight GUI

> 免责声明：本仓库仅供学习与交流，不允许用于任何商业用途。

Language / 语言: [English](./README.md) | [中文](./README_zh.md)

一个本地离线的 playable HTML 素材与跳转链接替换工具。

## 给小白用户（ZIP 使用）

1. 下载 `PlayableAds-Insight-GUI.zip`
2. 右键压缩包，选择“解压到当前文件夹”
3. 打开解压后的文件夹，双击 `index.html`
4. 如果浏览器弹出安全提示，选择继续打开
5. 进入页面后按提示上传你的 playable HTML 开始使用

## 功能特性

- 支持解析常见 playable 资源模式：`ZIP`、`adapterZip`、`inline data:image`
- 支持单张图片替换
- 支持按文件名批量替换图片
- 支持重写常见商店链接（`apps.apple.com`、`itunes.apple.com`、`play.google.com/store/apps`）
- 替换后可重新生成可交付 HTML
- 内置本地预览面板，方便快速验收

## 适用场景

- 高频替换 playable 图片素材
- 快速调整 App Store / Google Play 跳转链接
- 交付前进行本地快速验证

## 快速开始

1. 打开 [index.html](./index.html)
2. 上传 playable HTML 文件
3. 替换图片（单张或批量）
4. 填写商店链接
5. 点击预览并检查效果
6. 下载生成后的 HTML

## 使用说明

- 批量替换主要适用于带文件名的资源
- `inline` 模式暂不支持按文件名批量替换
- 投放前建议完成最终页面与点击跳转检查

## 文件结构

- [index.html](./index.html)：界面页面
- [main.js](./main.js)：核心处理逻辑
- [CHANGELOG.md](./CHANGELOG.md)：版本记录
- [UPDATE_NOTE.md](./UPDATE_NOTE.md)：更新说明
