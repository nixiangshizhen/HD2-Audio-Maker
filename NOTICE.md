# NOTICE — 第三方组件与许可

本项目（HD2 Audio Maker）自身代码由 **火柴木Matchwood** 编写。
发布包里包含以下第三方组件，各自的许可与版权归原作者所有。

| 组件 | 用途 | 许可 | 许可原文 |
|---|---|---|---|
| [hd2-audio-modder](https://github.com/RaidingForPants/hd2-audio-modder)（作者 Evie） | Wwise bank 解析与 patch 打包引擎（本项目的底座，以 vendored 方式内置） | MIT | [third_party/hd2-audio-modder-LICENSE.txt](third_party/hd2-audio-modder-LICENSE.txt) |
| [7-Zip](https://www.7-zip.org/)（`7za.exe`） | 读取 `.zip / .7z / .rar` mod 压缩包 | GNU LGPL + unRAR 限制条款 | [third_party/7zip-License.txt](third_party/7zip-License.txt) |
| [vgmstream](https://github.com/vgmstream/vgmstream)（`vgmstream-cli.exe`） | 解码游戏内的 Wwise Vorbis / 音频源 | ISC 风格（见原文） | [third_party/vgmstream-COPYING.txt](third_party/vgmstream-COPYING.txt) |
| Python 运行时及其依赖（tkinter / PyAudio / numpy / Pillow 等） | 程序运行 | 各自开源许可 | 见各项目主页 |

## 不随包分发的东西

- **Wwise**（Audiokinetic）：只在「打包成 mod」时调用用户本机安装的 `WwiseConsole.exe`，本项目不分发其任何文件。
- **游戏资源**：不包含任何《绝地潜兵 2》的音频、视频、bank 或解包数据；程序只读取用户本机的游戏安装目录。

## 版权声明

《HELLDIVERS™ 2》及其全部音频/视频素材版权归 **Arrowhead Game Studios / Sony Interactive Entertainment** 所有。
本项目是非官方粉丝工具，与上述公司无任何关联。
