# qzone-auto-login-helper
“QZone自动登录脚本，可独立使用或与自动点赞脚本结合，确保登录不中断
# QZone Auto Login Helper

这个脚本是QZone自动点赞脚本的辅助工具，也可以独立使用。主要功能是自动保持QZone登录状态：当登录失效或离线后，自动检测并触发浏览器密码自动填充，确保自动点赞等工作流不会停止。

## 安装
- 首先，确保您已安装Tampermonkey或Violentmonkey浏览器扩展（推荐Tampermonkey）。
- 从本仓库下载脚本文件 `qzone-auto-login-helper.user.js`（点击文件 > Raw > 右键保存，或直接下载ZIP并解压）。
- 打开Tampermonkey扩展面板（浏览器工具栏图标 > Dashboard）。
- 点击“+”图标创建新脚本，或使用“Utilities” > “Import from file”导入下载的文件。
- 保存后，脚本将自动启用（匹配QZone相关页面）。

## 使用
- 点击浮动“控制面板”按钮自定义设置。
- 与自动点赞脚本结合使用最佳（见另一个仓库：[您的自动点赞仓库链接]）。

## 注意
- 脚本不存储密码，仅依赖浏览器autofill。
- 作者：llulun | 版本：1.5 | 许可证：MIT
