# XYZW Local Helper

此仓库仅用于发布 **XYZW Local Helper** 的 Windows 安装包、更新说明和校验文件。

## 下载与安装

请前往 [Releases](../../releases) 页面下载最新版本的 Windows 安装包（`.exe`）。

安装前请先退出正在运行的 XYZW Local Helper，再双击安装程序并按提示完成升级。应用数据和本地配置会保留在原位置。

## 应用内升级

已安装的客户端可使用界面的“检查更新”功能获取新版本。客户端会先校验更新清单的签名和安装包的 SHA-256 值，再提示下载。

下载完成后，请退出客户端并运行下载的安装程序完成更新。

## 校验文件

每个发布版本可能包含以下文件：

- `SHA256SUMS-<version>.txt`：安装包的 SHA-256 校验值；
- `UNSIGNED-WINDOWS-RELEASE-<version>.txt`：未使用 Windows 代码签名证书时的说明；
- `stable.json`：供客户端检查更新使用的已签名更新清单。

请仅从本仓库的 Releases 页面或客户端内置更新功能获取安装包。

## Windows 安全提示

部分预览版安装包尚未使用 Windows 代码签名证书，Windows 可能显示“未知发布者”或 SmartScreen 提示。请确认下载来源为本仓库的 Release，并核对版本号与 SHA-256 校验文件后再继续安装。

## 支持

如遇到安装、更新或激活问题，请通过提供该软件的渠道联系支持人员，并附上客户端版本号和相关错误信息。
