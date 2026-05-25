<h4 align="right"> 
<span href="README_cn.md">简体中文</span> 
<a href="README.md" style="margin: 0 10px;" >English</a> 
<a href="README_tw.md">繁体</a>
</h4>  
<p align="center">
    <img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Logo_animat.svg" width=400/>
</p>
<h1 align="center">StageX</h1>  
<p align="center"><strong>向 Watchout 致敬，入门级多媒体播控软件 StageX</strong>
</p>

<p align="center">
    <a href="https://github.com/Paulsxb/StageX/releases">
        <img src="https://img.shields.io/github/v/release/Paulsxb/StageX?style=flat-square&logo=github&color=blue" alt="Release">
    </a>
    <a href="https://github.com/Paulsxb/StageX/releases">
        <img src="https://img.shields.io/github/downloads/Paulsxb/StageX/total?style=flat-square&logo=github" alt="Downloads">
    </a>
    <a href="https://github.com/Paulsxb/StageX/stargazers">
        <img src="https://img.shields.io/github/stars/Paulsxb/StageX?style=flat-square&logo=github" alt="Stars">
    </a>
    <a href="https://github.com/Paulsxb/StageX/network/members">
        <img src="https://img.shields.io/github/forks/Paulsxb/StageX?style=flat-square&logo=github" alt="Forks">
    </a>
    <img src="https://img.shields.io/badge/Qt-6.x-41CD52?style=flat-square&logo=qt" alt="Qt Version">
    <img src="https://img.shields.io/badge/Platform-Windows-0078D4?style=flat-square&logo=windows" alt="Platform">
    <a href="https://github.com/Paulsxb/StageX/blob/main/LICENSE">
        <img src="https://img.shields.io/github/license/Paulsxb/StageX?style=flat-square" alt="License">
    </a>
</p>

<div align="left">StageX 是一款轻量化的舞台播控工具，面向小型发布会、培训会、教学场景，支持视频、图像、PDF、网页及 PPT 五种媒体格式
     的外接屏播出控制。 </div>  
<br>

> 痛点😅：一次偶然的机会，朋友要开一个小型的个人演唱会，让我负责播控。一共20首4K的高清视频，连续播放。我想把视频嵌入PowerPoint，但是20个4K的视频文件啊，PPT只能内嵌视频，最终的PPT文件会有多大？还能跑的起来吗？我又尝试一些视频播放软件，但是歌曲和歌曲之间的中场还需要切换演唱会背景、开场前还有循环播放的暖场视频（歌曲视频是单次播放），同时考虑到视频与视频之间的无缝切换，突然，我就萌生了要开发一款入门级的简单播控软件……

## 软件亮点

-   💎 5种多媒体源支持：视频、图片、PDF、网页、PowerPoint
-   🎬️ 通过ACT幕的概念，将各种媒体文件串联并播放
-   🎥 视频支持：MP4 / MKV / AVI / M4V / TS / MOV
-   🖼️ 图片支持：PNG / JPG / JPEG / BMP / GIF / SVG / WebP / 静态SVG
-   💻️ PowerPoint 支持：PPTX / PPT。不是截图渲染，而是完美支持PPT原生动画
-   🎚️ 配备专业调音台模块，让导播人员全程掌控多视频的音响度
-   📑 支持PDF单页全屏或最大化显示，并支持翻页.
-   🛜 支持在线网站（包括 Youtube 等需要验证登录的网站），同时也支持本地网页.
-   🌍️ 多语言支持：简体、繁体、英文.
-   ⌨️ 全局键盘钩子：支持USB及蓝牙翻页器控制，支持键盘 Page Up/ Down 导播控制，不抢焦点
-   📺️ 双屏模式：主屏控制端 + 外屏纯净播出端（投影 / LED 墙 / 副屏）
-   💯 UI 设计参考剪映和OBS，界面简洁，易于上手

<img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Stage_UI.png" width="100%" style="text-align: center"/>

## 软件说明

-   前往 [Releases](https://github.com/Paulsxb/StageX/releases) 页面下载最新安装包.
-   本软件需要ffmpeg、VLC、Office等环境支持，内存在8G以上，如果是4K甚至以上视频，建议16G内存以上
-   此版本为天使尝鲜版，最多支持10个ACT幕
-   本软件为闭源软件。详见 LICENSE 文件（随安装包附带）.
-   如有问题或建议，欢迎来信：<a href="mailto:paulsxb@gmail.com?subject=StageX_Feedback" target="_blank">paulsxb@gmail.com</a>

## 应用场景

### 场景一：婚宴、生日派对、主题活动等

将多个视频和图片串联起来，通过翻页器直接控制播放

### 场景二：培训会、分享会

以PPT文件为主，但不再需要启动PowerPoint，直接通过StageX软件控制PPT的完美播放，所有PPT内嵌效果及动画均能复现。并且还能播放视频、图片甚至是网页端的操作演示。通过手中的翻页器，主讲人自己就能操控全程演示。每一个ACT幕还能单独添加备注作为提示。

### 场景三：培训及分享会小型活动、或发布会

同样以PPT文件为主，把需要展示的图像、视频包括PDF认证或调研文档直接展示，除了主持人或发言人可以自行操控外，导播台的人员也能协助控制。在播放视频、PPT或PDF时，导播员可以在本机上直观地看到视频文件当前播放时间，还有多久播放结束？PDF和PPT还有几页？整个播放过程尽在掌控之中。

## 支持 StageX

💖 如果StageX对你的生活和工作有帮助，你喜欢它的话，也请支持StageX，给我一点鼓励和认可，非常感谢！

<table style="text-align:center; width: 400px; border-collapse: collapse; border-spacing: 0; border: none;">
    <tr>
        <td style="padding: 0; margin: 0; border: none;"><img src="https://media.giphy.com/media/513lZvPf6khjIQFibF/giphy.gif"/></td>
        <td style="padding: 0; margin: 0; border: none;"><a href="https://buymeacoffee.com/paulsxbe"><img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Buymeacoffee.png" width=200/></a></td>
    </tr>
</table>