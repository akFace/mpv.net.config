# mpv 和 mpv.net 开箱即用配置文件&精美 UI 主题

## 简要说明

- 两套主题皮肤`modernz`、`uosc`
- 使用原生 mpv.net 播放器
- 集成进度条缩略图预览：[Thumbfast](https://github.com/po5/thumbfast)
- 集成漂亮的 UI 无边框设计：[Samillion/ModernZ]、[tomasklaen/uosc]
- 快捷键优化 `Ctrl + i` 查看和设置所有快捷键
- 支持全网弹幕加载（仅主题皮肤 2），插件:Tony15246/uosc_danmaku

## 使用方法

- 先安装 mpv.net 播放器：[https://github.com/mpvnet-player/mpv.net/releases](https://github.com/mpvnet-player/mpv.net/releases)
- [🎯 点击下载](https://github.com/akFace/mpv.net.config/releases) 你想要的主题皮肤（已包含配置）`modernz`和`uosc`，并解压
- 如图所示，右键>配置>打开配置文件夹或者`Ctrl + f`快捷键打开配置文件夹

  ![image](https://raw.githubusercontent.com/akFace/mpv.net.config/master/preview/Snipaste_2026-03-16_20-34-06.jpg)

- 将不同的主题和配置文件全部复制到配置文件夹(只能共存一个主题配置)，重启播放器即可
- 注意目录结构

```
一般的目录结构如下:
~/.config/mpv
├── fonts
├── scripts
├── script-opts
├── mpv.conf
└── input.conf

```

- 若你使用的并非 mpv.net 播放器，请修改`script-opts/thumbfast.conf`目录中的`mpv_path=mpvnet`改为`mpv_path=mpv`或者播放器安装目录可执行文件 例如：`mpv_path=C:\Program Files\mpv.net\mpvnet.exe`

## 预览效果图：

### 主题皮肤 1（modernz）

![image](https://raw.githubusercontent.com/akFace/mpv.net.config/master/preview/Snipaste_2026-03-16_20-32-59.jpg)

### 主题皮肤 2（uosc）

![image](https://raw.githubusercontent.com/akFace/mpv.net.config/master/preview/Snipaste_2026-03-18_16-51-00.jpg)

- 弹幕默认样式在配置文件夹`script-opts/uosc_danmaku.conf`下
