# 净启 · 好友体验版

Android 开屏广告跳过工具。需要 Android 8.0 或以上，并手动启用无障碍服务；部分识别模式需要额外授权。不同手机及应用的效果会有差异，不能保证跳过所有广告。

## 下载与安装

直接下载 [净启 0.1.28 APK](https://zyc3047-tech.github.io/jingqi-releases/jingqi-0.1.28.apk)，或前往 [版本下载页](https://github.com/zyc3047-tech/jingqi-releases/releases/tag/v0.1.28)，下载 `jingqi-0.1.28.apk`，按系统提示安装。已经安装旧版的用户直接覆盖安装即可，请勿先卸载，以免丢失设置。

应用内「操作教程」提供权限设置、规则和排查方法。当前是好友体验测试版，采用现有开发签名以支持旧版覆盖升级。

## 更新方式

0.1.28 起，在打开净启时每天最多检查一次更新，也可以从首页「检查更新」手动检查。发现新版后，由你选择下载，再经 Android 安装器确认安装。不会静默安装，不会后台持续轮询。

0.1.27 及更早版本需要先手动安装一次本版。GitHub 下载速度及可达性受手机网络影响；检查失败不会影响广告跳过。

## 校验与数据

安装包校验 SHA256、大小、包名、版本及签名；摘要文件位于每个 Release。广告识别在手机本地处理，更新请求不附带设备标识或广告记录。本仓库仅发布安装包、版本清单和说明，不含个人手机数据。

更新清单：[latest.json](https://raw.githubusercontent.com/zyc3047-tech/jingqi-releases/main/latest.json)

## 规则来源

部分内置规则整理自 MIT 许可的 [ganlinte/GKD_subscription](https://github.com/ganlinte/GKD_subscription)，保留原始归属和许可；社区规则仍需逐机逐应用验证。
