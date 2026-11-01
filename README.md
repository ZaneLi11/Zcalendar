# Zcalendar

一款面向 Apple Silicon Mac 的本地个人日历，用来安排日程、整理优先级，以及查看和分享时间安排。支持中文和英文界面。

## 下载 Zcalendar

### [⬇ 下载 macOS 安装包 · v0.8.6（DMG）](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/Zcalendar-0.8.6-macOS-arm64.dmg)

[ZIP 备用下载](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/Zcalendar-0.8.6-macOS-arm64.zip) · [版本说明与全部文件](https://github.com/ZaneLi11/Zcalendar/releases/tag/v0.8.6) · [所有版本](https://github.com/ZaneLi11/Zcalendar/releases)

**适用于 Apple Silicon Mac（M 系列），应用声明最低 macOS 13.0。** 当前安装包不适用于 Intel Mac 或 Windows；最低系统版本及其他电脑的兼容性尚未实机验收。DMG 和 ZIP 各约 129 MB，包含相同版本，任选一个即可。

## 可以做什么

- **安排日程**：创建、编辑日程，设置提醒，以及按周、月、年重复。
- **查看时间**：切换月、周、日视图，在日／周轨道视图中浏览和调整安排。
- **整理重点**：设置高、中、低优先级，自定义颜色，搜索日程并进行批量操作。
- **分享与备份**：导出 PDF、PNG、JSON 或 Markdown；创建和恢复完整日历备份。
- **按需接入 AI**：通过本地 MCP 接入支持的 AI 客户端，或导入 AI 生成的日程提案并预览确认。

日历数据保存在本机。使用 AI 接入时，请按需授权，并自行确认所用 AI 客户端的数据处理方式。

## 安装

1. 下载上方的 **DMG 安装包**。
2. 双击打开，将 **Zcalendar** 拖到 **Applications（应用程序）**。
3. 从应用程序文件夹打开 Zcalendar。更新时，请先完全退出正在运行的旧版本，再替换应用。

如果使用 ZIP，解压后将 `Zcalendar.app` 拖到应用程序文件夹即可。

### 首次打开

当前版本使用 ad-hoc 签名，尚未进行 Developer ID 签名或 Apple 公证，首次下载后可能被 macOS 拦截。确认下载来源后，请按照 [Apple 官方说明](https://support.apple.com/en-us/102445)，在“系统设置 → 隐私与安全”中查看“仍要打开”选项。

### 校验下载文件

下载 [SHA256SUMS.txt](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/SHA256SUMS.txt)，与安装包放在同一文件夹，在该文件夹中运行：

```sh
shasum -a 256 -c SHA256SUMS.txt
```

校验文件列出了 DMG 和 ZIP；如果只下载其中一个，另一项会提示文件不存在，已下载文件应显示 `OK`。

[完整安装说明（中英文）](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/INSTALL.md) · [打包检查记录](https://github.com/ZaneLi11/Zcalendar/releases/download/v0.8.6/release-info.json)

## 关于此仓库

此仓库用于发布 Zcalendar 安装包、版本说明及使用信息，暂不提供项目工程源码。安装包保留应用运行所需的 JavaScript、原生库、第三方依赖与许可证；运行代码仍可被提取。
