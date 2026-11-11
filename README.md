# SSO Mac

SSO Mac 是 macOS 上的门户网站 SSO 单点登录客户端。点击兼容门户中的远程应用后，浏览器会唤起 SSO Mac，由它读取本次登录配置并通过 Microsoft Windows App 打开远程应用。

## 系统要求

- macOS 13 或更高版本，支持 Intel 和 Apple 芯片。Windows App 的系统要求以 App Store 页面为准。
- 必须另行安装 [Microsoft Windows App](https://apps.apple.com/app/windows-app/id1295203466)。
- 门户需支持通过 SSOLogin 协议唤起客户端。

## 安装与使用

1. 从 [Releases](https://github.com/XuNanbo/sso-mac/releases/latest) 下载 `SSO-Mac-1.0.0-Universal.dmg`，打开后将 SSO Mac 拖入「应用程序」。
2. 打开 SSO Mac。首次使用时，根据提示在「系统设置 → 隐私与安全性 → 辅助功能」中允许 SSO Mac，以便自动填写 Windows App 的凭证窗口。
3. 在浏览器中登录门户并点击目标远程应用。浏览器询问时，允许打开 SSO Mac。
4. SSO Mac 使用门户在本次请求中传入的账号，由 Windows App 建立远程连接。

当前安装包尚未通过 Apple 公证。首次从 GitHub 下载后，macOS 可能显示安全提示。
