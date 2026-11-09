# 科电 Windows 开发工具包

在 [Releases](https://github.com/kedian-club/vscode-windows-toolchain/releases) 下载完整 ZIP。工具包包含 Windows x64 的 VS Code 安装包及 MinGW-w64 工具链。

| 内容 | 文件 |
| --- | --- |
| VS Code 1.136.0 | `VSCodeUserSetup-x64-1.136.0.exe` |
| MinGW-w64 工具链 | `mingw64/`，GCC 8.1.0 |

解压后，将 `mingw64/bin` 的绝对路径加入 Windows 用户的 `Path`，再打开一个新终端运行 `gcc --version` 与 `g++ --version` 检查是否配置成功。

VS Code 也可从 [微软官方下载页](https://code.visualstudio.com/download) 获取。安装程序和编译器随附各自的许可条款。

发布包 `vscode-windows-toolchain-2026-11-09.zip`，约 363.2 MiB，共 13,204 个文件。

SHA-256

```text
22503cb01cbaffecd5a6d8b78ef292c1713cc6cee97543ebc5c0fedbe1278b0d
```
