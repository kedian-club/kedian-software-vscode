# 科电 Windows 开发工具包

这里整理了 VS Code 和 MinGW-w64 的下载入口，适合使用 Windows x64 学习 C/C++ 的同学。

## 获取软件

### VS Code

VS Code 由微软提供下载，可以前往 [VS Code 官方下载页面](https://code.visualstudio.com/download)，选择适合自己电脑的版本。Windows x64 用户也可以直接下载 [VS Code 1.136.0 用户安装版](https://update.code.visualstudio.com/1.136.0/win32-x64-user/stable)。

### MinGW-w64

MinGW-w64 编译器包放在本仓库的 [Releases 发布页面](https://github.com/kedian-club/vscode-windows-toolchain/releases/tag/mingw-w64-8.1.0-rt-v6-rev0) 中。打开页面，找到 **Assets**，点击 `x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z` 下载；也可以[直接点击下载编译器包](https://github.com/kedian-club/vscode-windows-toolchain/releases/download/mingw-w64-8.1.0-rt-v6-rev0/x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z)。

该版本适用于 Windows x64，使用 GCC 8.1.0。页面上的 `src-8.1.0-release-rt_v6-rev0.tar.7z` 是对应的源代码，日常安装编译器不需要下载。若 GitHub 下载不方便，也可以尝试[上游下载页面](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-posix/seh/)。

下载后，用支持 `.7z` 的工具解压，将解压得到的 `mingw64/bin` 文件夹的完整路径添加到 Windows 用户的 `Path` 环境变量中。重新打开终端，分别运行 `gcc --version` 和 `g++ --version`，如果显示版本信息，说明终端已经能够找到编译器。

## 许可与来源

各软件适用其发布方提供的许可条款。[VS Code 许可](https://code.visualstudio.com/license) · [MinGW-w64 工具链列表](https://www.mingw-w64.org/downloads/) · [本仓库对应的 MinGW-w64 源代码](https://github.com/kedian-club/vscode-windows-toolchain/releases/download/mingw-w64-8.1.0-rt-v6-rev0/src-8.1.0-release-rt_v6-rev0.tar.7z)
