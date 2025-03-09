<div align="center" id="madewithlua">
  <img
    src="https://raw.githubusercontent.com/wezterm/wezterm/main/assets/icon/wezterm-icon.svg"
    width="110"
    ,
    height="100"
  />
</div>

<h1 align="center">WezTerm</h1>

[![GitHub Release](https://img.shields.io/github/v/release/QianSong1/wezterm-config?style=flat-square&logo=starship&logoColor=D9E0EE&labelColor=302D41&color=c0109f)](https://github.com/QianSong1/wezterm-config/releases)
[![GitHub Repo stars](https://img.shields.io/github/stars/QianSong1/wezterm-config?style=flat-square&logo=apachespark&logoColor=D9E0EE&labelColor=302D41&color=8bd5ca)](https://github.com/QianSong1/wezterm-config/stargazers)
[![GitHub Issues or Pull Requests](https://img.shields.io/github/issues/QianSong1/wezterm-config?style=flat-square&logo=issuu&logoColor=D9E0EE&labelColor=302D41&color=dcdf03)](https://github.com/QianSong1/wezterm-config/issues)
[![GitHub License](https://img.shields.io/github/license/QianSong1/wezterm-config?style=flat-square&logo=gitbook&logoColor=D9E0EE&label=license&labelColor=302D41&color=df03c6)](https://github.com/QianSong1/wezterm-config/blob/main/LICENSE)
[![Static Badge](https://img.shields.io/badge/QQ-1725099638-d583c7?style=flat-square&logo=qq&logoColor=D9E0EE&label=QQ&labelColor=302D41&color=d583c7)](https://github.com/QianSong1/wezterm-config)

<p align="center" style="font-weight: bold;">
A GPU-accelerated cross-platform terminal emulator and multiplexer written by <a href="https://github.com/wez">@wez</a> and implemented in <a href="https://www.rust-lang.org">Rust</a>
</p>
<p align="center">
User facing docs and guide at: <a style="font-weight: bold;" href="https://wezterm.org">wezterm.org</a>
</p>



# 我的WezTerm配置

**截图一**

![screenshot](./screenshots/screenshot-1.png) 

**截图二**

![screenshot](./screenshots/screenshot-2.png) 



## 相关链接

- <https://github.com/rxi/lume>
- <https://github.com/catppuccin/wezterm>
- <https://github.com/wezterm/wezterm/discussions/628#discussioncomment-1874614>
- <https://github.com/wezterm/wezterm/discussions/628#discussioncomment-5942139>
- <https://github.com/wezterm/wezterm/discussions/628#discussioncomment-3649195>



## 原作者仓库

- <https://github.com/KevinSilvester/wezterm-config>



## 前提条件

**1、安装`wezterm`终端**

[WezTerm终端](https://github.com/wezterm/wezterm/releases)

安装目录：C:\soft\WezTerm-windows

**2、安装`nerdfont`字体**

[MesloLGM Nerd Font](https://github.com/ryanoasis/nerd-fonts/blob/v3.2.1/patched-fonts/Meslo/M/Regular/MesloLGMNerdFont-Regular.ttf)

[JetBrainsMono NF](https://github.com/ryanoasis/nerd-fonts/blob/v3.2.1/patched-fonts/JetBrainsMono/Ligatures/Regular/JetBrainsMonoNerdFont-Regular.ttf)

字体版本 `v3.2.1` ，注意了，版本很重要，如果某些图标弃用了或更新了，那么就需要更新字体版本，或者更新图标，**总而言之：必须让字体版本与图标对应上，否则就会出现奇怪的乱码**

[图标 icon 搜索网站](https://www.nerdfonts.com/cheat-sheet)



## 使用方法

1、下载本储存库压缩包

2、解压压缩包

3、将解压的文件放入：`$HOME/.config/wezterm`目录底下

Windows目录：`C:\Users\Fizz\.config\wezterm`



## 快捷键

```bash
#快捷键
Ctrl+shift+c    --复制
Ctrl+shift+v    --粘贴
Ctrl+shift+r    --重命名标签栏
Ctrl+alt+[\]    --水平拆分窗格，即左右拆分
Ctrl+alt+[/]    --垂直拆分窗格，即上下拆分
Ctrl+alt+[-]    --关闭当前窗格
Ctrl+alt+z      --最大化/最小化当前窗格
F11             --全屏
Ctrl+alt+[↑]    --向上扩展窗格
Ctrl+alt+[↓]    --向下扩展窗格
Ctrl+alt+[←]    --向左扩展窗格
Ctrl+alt+[→]    --向右扩展窗格
Alt+[↑]         --放大字体
Alt+[↓]         --缩小字体
Alt+r           --重置字体大小
```
