<h1 align="center">XSecret</h1>
<h3 align="center">XSecret 是一款 Text | Markdown 加密笔记工具，帮助用户安全地存储和管理笔记</h3>
<p align="center">
  <img src="https://img.shields.io/badge/Version-V1.0.0 Beta-green?style=flat">
  <img src="https://img.shields.io/github/stars/chasingboy/XSecret?style=flat&labelColor=rgb(41%2C52%2C52)&color=green">
  <img src="https://img.shields.io/github/issues/chasingboy/XSecret">
  <img src="https://img.shields.io/github/downloads/chasingboy/XSecret/total?style=flat&labelColor=rgb(41%2C52%2C52)&color=green">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=chasingboy.XSecret&left_color=green&right_color=#66ccff">
</p>

## 前言

> XSecret 是一款轻量级的 Text ｜Markdown 加密笔记工具。

开发原因很简单，经常需要在电脑上保存账号密码、服务器信息和各种敏感数据，但始终找不到一款既支持 Markdown、又足够轻量且完全本地化的加密工具。

因此，XSecret 诞生了。它专注于本地加密存储，让你能够像编写普通 Markdown 一样记录内容，同时确保重要信息不会以明文形式暴露。无论是密码、API Key、配置文件还是私人笔记，都能得到安全保护。

## 功能
✅ 支持 Sqlite 存储文件</br>
✅ 支持文本｜图片加密</br>
✅ 支持文件删除回收站</br>
✅ 支持暗黑｜亮色两种主题</br>
✅ 支持更改密码｜调节字体大小</br>

## 截图
<img width="1316" alt="image" src="https://github.com/chasingboy/XSecret/blob/main/assets/login.png">

<img width="1316" alt="image" src="https://github.com/chasingboy/XSecret/blob/main/assets/light.png">

<img width="1316" alt="image" src="https://github.com/chasingboy/XSecret/blob/main/assets/dark.png">

## Mac 打开报错
mac 打开时提示“系统初始化错误”，执行命令可解决该问题
```
xattr -dr com.apple.quarantine XSecret.app
```
