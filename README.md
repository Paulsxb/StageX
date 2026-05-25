<h4 align="right"> 
<a href="README_cn.md">简体中文</a> 
<span href="README.md">English</span> 
<a href="README_tw.md">繁体</a>
</h4>  
<p align="center">
    <img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Logo_animat.svg" width=400/>
</p>
<h1 align="center">StageX</h1>  
<p align="center"><strong>A Tribute to Watchout: StageX, the Entry-Level Multimedia Show Control Software</strong>
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

<div align="left">StageX is a lightweight stage show control tool designed for small-scale press conferences, training sessions, and educational scenarios. It seamlessly supports external display playback and orchestration across five major media formats: video, images, PDFs, web content, and PowerPoint presentations.</div>  
<br>

> **The Pain Point 😅:** By a stroke of coincidence, a friend of mine was holding a small-scale solo concert and tasked me with the show control. There were 20 high-definition 4K videos that needed to be played sequentially. My initial thought was to embed them into PowerPoint, but with twenty massive 4K files, the native video embedding would make the final PPT file size astronomical. Would it even run? I then experimented with conventional video players, but the reality of a live concert demands switching to generic concert backdrops during intermissions, looping warm-up videos before the opening act (while track videos are strictly single-play), and achieving seamless zero-gap transitions between cues. Realizing that no consumer software fit the bill, the inspiration to develop an entry-level, dead-simple show control app was born...

## Key Features

- 💎 **5-in-1 Multimedia Support**: Videos, Images, PDFs, Web Content, and PowerPoint.
- 🎬 **The "ACT Scene" Architecture**: Chain different media files into a cohesive playback sequence effortlessly.
- 🎥 **Video Formats**: MP4 / MKV / AVI / M4V / TS / MOV.
- 🖼️ **Image Formats**: PNG / JPG / JPEG / BMP / GIF / SVG / WebP / Static SVG.
- 💻 **PowerPoint Native Support**: Supports `.pptx` and `.ppt`. This is NOT static screenshot rendering; it perfectly reproduces PowerPoint's native animations and transitions.
- 🎚️ **Professional Audio Mixer**: Integrated audio slider module allows operators to fully monitor and master multi-video loudness throughout the gig.
- 📑 **PDF Optimization**: Supports single-page full-screen or maximized layout, with smooth page flipping.
- 🛜 **Web Content**: Supports live websites (including platforms like YouTube that require authentication/login) as well as local HTML packages.
- 🌍 **Multi-Language Support**: Simplified Chinese, Traditional Chinese, and English.
- ⌨️ **Global Keyboard Hook**: Fully compatible with USB and Bluetooth clickers/presenters; supports `Page Up` / `Page Down` for show control without hijacking window focus.
- 📺 **Dual-Display Workflow**: Main operator control terminal + completely clean external output screen (for projectors, LED walls, or secondary displays).
- 💯 **Clean UI Design**: Modeled after the streamlined layouts of CapCut and OBS—clean, modern, and zero learning curve.

<img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Stage_UI.png" width="100%" style="text-align: center"/>

## Software Notice

- Navigate to the [Releases](https://github.com/Paulsxb/StageX/releases) page to download the latest installation package.
- This software relies on underlying runtime dependencies (FFmpeg, VLC, Microsoft Office, etc.). A minimum of 8GB RAM is required; for 4K or higher video playback, 16GB+ RAM is highly recommended.
- This current build is the **Angel Beta Version**, which caps creation at a maximum of **10 ACT Scenes**.
- This is a **Closed-Source** application. For detailed legal frameworks, please refer to the `LICENSE` file bundled with the installation package.
- For bug reports or feature suggestions, feel free to drop us a line at: <a href="mailto:paulsxb@gmail.com?subject=StageX_Feedback" target="_blank">paulsxb@gmail.com</a>

## Use Cases

### Scenario 1: Banquets, Birthday Parties, & Theme Events
Chain a collection of nostalgic videos and photo slideshows together into a single timeline, and control the entire sequence smoothly with a standard presentation clicker.

### Scenario 2: Training Sessions & Corporate Workshops
Keep your PowerPoint at the core of the presentation, but eliminate the need to launch PowerPoint separately. Run everything directly inside StageX to enjoy flawless native slide animations, while seamlessly interweaving track videos, image galleries, or live technical web demos into the same workflow. Speakers can self-manage the stage using a hand-held remote, with the added benefit of checking customized cues/prompts for each individual ACT Scene.

### Scenario 3: Press Conferences, Product Launches, & Small Shows
Centered on PPT files, this setup lets you seamlessly integrate image assets, product reels, or official PDF certification and research documents into the main sequence. Beyond presenter self-control, the dedicated backend operator station provides full visibility. While a video, slide, or PDF is live on the big screen, operators can precisely track playback timers down to the second, monitor upcoming file durations, and see exactly how many pages remain. The entire live production is kept strictly under control.

## Support StageX

💖 If StageX has brought value to your work or life and you enjoy using it, please consider backing the project. A little encouragement and recognition goes a long way. Thank you so much!

<table style="text-align:center; width: 400px; border-collapse: collapse; border-spacing: 0; border: none;">
    <tr>
        <td style="padding: 0; margin: 0; border: none;"><img src="https://media.giphy.com/media/513lZvPf6khjIQFibF/giphy.gif"/></td>
        <td style="padding: 0; margin: 0; border: none;"><a href="https://ko-fi.com/stagex"><img src="https://raw.githubusercontent.com/Paulsxb/StageX/refs/heads/main/Buymeacoffee.png" width=200/></a></td>
    </tr>
</table>