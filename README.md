# CodexUsageManager

macOS 菜单栏 Codex 多账号与额度管理工具，第三方项目，与 OpenAI 无从属关系。

此仓库仅发布安装包、更新清单和版本说明。源码在独立私有仓库维护。

支持 Apple Silicon / macOS 14+。从 Releases 下载 DMG，将应用复制到 Applications。
测试版本暂未完成 Apple Developer ID 签名和公证；Sparkle 更新包及更新清单使用独立 Ed25519 签名验证。

0.3.0 起可在设置中检查更新、开关自动检查；安装更新由用户确认。
0.2.x 尚无内置更新，需要先手动安装一次 0.3.0 或更高版本。
更新只替换应用，账号与设置保存在 `~/Library/Application Support/CodexUsageManager/`。

账号推荐不自动切换，重置券只读。自动激活额度窗口为可选设置，会消耗额度。
问题反馈请使用 Issues；请勿上传认证文件、登录码、聊天记录或未脱敏日志。

安装包中包含第三方许可与上游 MIT 许可，位于应用的 `Contents/Resources/licenses/`。
