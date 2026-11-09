# 科电 Windows 开发工具包

用于 Windows x64 上的 C/C++ 学习和开发。以下链接指向软件发布方提供的下载。

| 软件 | 下载 |
| --- | --- |
| VS Code 1.136.0（Windows x64 用户安装版） | [微软官方下载](https://update.code.visualstudio.com/1.136.0/win32-x64-user/stable) · [其他版本](https://code.visualstudio.com/download) |
| MinGW-w64（GCC 8.1.0，x86_64 POSIX SEH） | [MinGW-w64 项目下载](https://sourceforge.net/projects/mingw-w64/files/Toolchains%20targetting%20Win64/Personal%20Builds/mingw-builds/8.1.0/threads-posix/seh/x86_64-8.1.0-release-posix-seh-rt_v6-rev0.7z/download) |

1. 运行微软提供的安装程序安装 VS Code。
2. 用支持 `.7z` 的工具解压 MinGW-w64，并将解压所得 `mingw64/bin` 的绝对路径加入 Windows 用户的 `Path`。
3. 打开新的终端，运行 `gcc --version` 和 `g++ --version` 检查配置。

软件适用各发布方提供的许可条款。 [VS Code 许可](https://code.visualstudio.com/license) · [MinGW-w64 工具链列表](https://www.mingw-w64.org/downloads/)
