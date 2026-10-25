# MES 图纸转换助手 · 安装包发行仓库

这里只发布 Windows / macOS 安装包、更新说明及签名更新信息，不存放应用源码、CAD 文件或用户数据。

- [Windows 0.1.8-beta.1](https://github.com/goldf2/mes-drawing-converter-releases/releases/tag/win-v0.1.8-beta.1)：AutoCAD 2022 / SolidWorks 2025，本机需要 .NET Framework 4.8。
- [Mac 0.1.2-beta.2](https://github.com/goldf2/mes-drawing-converter-releases/releases/tag/mac-v0.1.2-beta.2)：macOS 13+、Apple Silicon / Intel，本机 AutoCAD DWG 试验版。Mac 不支持 SolidWorks 转换。

新版支持独立选择 DWG / SolidWorks、在软件中检查更新。启动检查与测试版通知默认开启，下载及安装由用户确认。转换中不能安装更新，原图、PDF、转换设置保留。

从不带更新功能的旧便携版迁移，需要先结束任务并退出旧版，再手动安装一次本版。Windows 请使用 Setup 创建的新快捷方式；Mac 请解压并移入“应用程序”。

当前均为测试版：Windows 未作发布者代码签名，Mac 为 ad-hoc 包、未作 Developer ID 签名或公证。自动安装不可用。更新信息和更新包仍使用产品专用 Ed25519 密钥验证。实际 CAD 出图、Windows 实机安装/卸载与跨版本升级需现场验收。当前仅提供本地待上传清单，尚未对接生产 MES。

[问题反馈](https://github.com/goldf2/mes-drawing-converter-releases/issues) · [全部发行版](https://github.com/goldf2/mes-drawing-converter-releases/releases)

`update-feeds` 为供应用读取的标准 NetSparkle / Sparkle 更新元数据，用户应下载所属平台的应用安装包。
