# 科电 Windows 开发工具包

这里整理了 VS Code 和 MinGW-w64 的下载入口，适合使用 Windows x64 学习 C/C++ 的同学。

## 获取软件

### VS Code

VS Code 由微软提供下载，可以前往 [VS Code 官方下载页面](https://code.visualstudio.com/download)，选择适合自己电脑的版本。Windows x64 用户也可以直接下载 [VS Code 1.136.0 用户安装版](https://update.code.visualstudio.com/1.136.0/win32-x64-user/stable)。

### MinGW-w64

MinGW-w64 编译器包放在本仓库的 [Releases 发布页面](https://github.com/kedian-club/vscode-windows-toolchain/releases/tag/mingw-w64-8.1.0-rt-v6-rev0) 中。打开页面，找到 **Assets**，点击 `x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z` 下载；也可以[直接点击下载编译器包](https://github.com/kedian-club/vscode-windows-toolchain/releases/download/mingw-w64-8.1.0-rt-v6-rev0/x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z)。

该版本适用于 Windows x64，使用 GCC 8.1.0。页面上的 `src-8.1.0-release-rt_v6-rev0.tar.7z` 是对应的源代码，日常安装编译器不需要下载。若 GitHub 下载不方便，也可以尝试[上游下载页面](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-posix/seh/)。

下载后，用支持 `.7z` 的工具解压，将解压得到的 `mingw64/bin` 文件夹的完整路径添加到 Windows 用户的 `Path` 环境变量中。重新打开终端，分别运行 `gcc --version` 和 `g++ --version`，如果显示版本信息，说明终端已经能够找到编译器。

## VS Code

作者：智官超（Loren-zzi）

> **Visual Studio Code（VS Code）** 是一款由微软开发的免费代码编辑器，支持 Windows、macOS 和 Linux。它体积较轻、启动速度快，可以用来编写和阅读 C、Python、Java 等多种编程语言的代码。
>
> VS Code 的一大特点是可以安装扩展。比如，安装 Python 扩展后，编辑器可以提供代码补全和运行辅助；安装中文语言包后，界面也可以切换为中文。它还内置终端，方便大家在同一个窗口中编写代码和运行命令。
>
> 对于刚开始学习编程的大一新生来说，VS Code 界面简洁、资料丰富，是我本人非常非常喜欢的一款开发工具。需要注意的是，VS Code 本身是一个编辑器，学习某些语言时还需要另外安装对应的编译器或运行环境。

安装 VS Code 和 MinGW 工具链，以及配置 C/C++ 环境，可以参考下面的视频：

[VS Code 安装和 C/C++ 配置教程（Bilibili）](https://www.bilibili.com/video/BV1tyAtetEd1/)

## 许可与来源

各软件适用其发布方提供的许可条款。[VS Code 许可](https://code.visualstudio.com/license) · [MinGW-w64 工具链列表](https://www.mingw-w64.org/downloads/) · [本仓库对应的 MinGW-w64 源代码](https://github.com/kedian-club/vscode-windows-toolchain/releases/download/mingw-w64-8.1.0-rt-v6-rev0/src-8.1.0-release-rt_v6-rev0.tar.7z)
