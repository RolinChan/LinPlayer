<img width="580" height="370" alt="image" src="https://github.com/user-attachments/assets/6714947f-6b63-4e13-b722-e5df081074d5" />

# LinPlayer

## 免费 · 简洁 · 易用

LinPlayer是一款Windows媒体播放器，基于[迅雷AplayerIII引擎](http://aplayer.open.xunlei.com/)打造，支持绝大部分媒体格式。以简洁流畅和强大易用为核心设计思想，带来不一样的全新体验。

支持的操作系统：Windows 7及以上版本

最新版本：Beta 1.5.1.572（2025.7.17更新）

## 注意事项

> [!NOTE]  
> 不推荐在更低版本系统或其他模拟环境中使用（如Linux中的Wine），可能导致UI出现问题，无法正常操作。

> [!WARNING]  
> LinPlayer仅供个人使用，以及非营利性组织（如学校等）和开发者以学习交流等非商业目的使用，禁止用于商业目的。

## 开发背景

LinPlayer的前身是LSPlayer（2021-2024），在作者还是个初一学生的时候所完成，最初仅为解决在学校较为古老的低配设备上流畅播放各种格式的视频所设计，后得以延续，共有超过20个发行版本，供学校内以及个人以非商业目的使用。如图为LSPlayer最后版本(1.4.0.497)的界面

<img width="1131" height="755" alt="image" src="https://github.com/user-attachments/assets/880ce424-bf60-4ac8-b9f8-198b3dda60dd" />

## 界面展示

### 主界面

<img width="1345" height="897" alt="image" src="https://github.com/user-attachments/assets/7c3b50e5-ebf7-4d24-8635-9e563d82da91" />


### 播放中

<img width="1344" height="897" alt="image" src="https://github.com/user-attachments/assets/b3988185-43fe-44db-96e0-6676f8b04c62" />

> [!TIP]  
> 现已支持修改主题配色！目前提供有若琳粉（默认，浅粉色）、四氧化三铁（浅蓝）、绿色氧化镍（浅绿）等主题色。
> 来尝试一下不同的感觉！

### 更多颜色

<img width="1829" height="897" alt="image" src="https://github.com/user-attachments/assets/bf15aedf-b762-46f1-9add-1c766ebf802d" />

<img width="1848" height="897" alt="image" src="https://github.com/user-attachments/assets/e0343813-22a4-4c8c-8277-4491523e3a81" />

## 安装方法

### 插件列表查看

安装 [插件列表查看](https://github.com/ltxhhz/LL-plugin-list-viewer) 插件，打开对应设置页面，找到本插件，点击 **安装** - **使用 Release 包**，安装完成之后重启

### PluginInstaller

安装 [PluginInstaller](https://github.com/xinyihl/LiteLoaderQQNT-PluginInstaller) 插件，打开对应设置页面，在安装插件输入框内输入 `https://raw.githubusercontent.com/MUKAPP/LiteLoaderQQNT-MSpring-Theme/v4/manifest.json`，点击确定按钮\
或者也可以同时安装 [Protocio](https://github.com/PRO-2684/protocio) 插件，然后点击 [该链接](https://mukapp.github.io/LiteLoaderQQNT-MSpring-Theme/res/protocio-install.html) 直接拉起 PluginInstaller 安装插件

### 手动安装

将下载的 Zip 文件解压，解压出的文件夹移动至 `LiteLoaderQQNT/plugins/` 内，重启 QQ 即可\
（如果解压之后不是一个文件夹，而是几个文件夹和几个文件，那么请创建一个文件夹，将解压出来的文件夹和文件放进去，然后再移动到上述路径内）

## 插件冲突分析

- **优化消息排版** 功能在 [**Markdown 插件**](https://github.com/d0j1a1701/LiteLoaderQQNT-Markdown) 开启时会失效，Markdown 插件自带了 `pangu.js` 的中英混排优化，开启二者之一就可以了

## 其他

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="
      https://api.star-history.com/svg?repos=MUKAPP/LiteLoaderQQNT-MSpring-Theme&type=Date&theme=dark
    "
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="
      https://api.star-history.com/svg?repos=MUKAPP/LiteLoaderQQNT-MSpring-Theme&type=Date
    "
  />
  <img
    alt="Star History Chart"
    src="https://api.star-history.com/svg?repos=MUKAPP/LiteLoaderQQNT-MSpring-Theme&type=Date"
    style="width: 100%;
      max-width: 600px;
      border-radius: 4px;
      box-shadow: 0 2px 4px 0 rgba(34,36,38,.12),0 2px 10px 0 rgba(34,36,38,.08);"
  />
</picture>
