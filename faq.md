---
redirect_from: /FAQ
---

## 常见问题解答

> 常见问题，一网打尽

<br>

**为什么 [光速启动](/launcher) 和 [光速切换](/multitask) 没起作用？**

- 因为你没有正确设置键盘的 [**Fn**](https://www.baidu.com/s?wd=Fn键) 模式。你必须能在不按 **`Fn`** 键的情况下使用 **`F1` ~ `F12`** 原本的功能，才能正常使用光速启动和光速切换。

<br>

**为什么 [空格编辑](/space) 某些键位的功能与帮助文档不相符？**

- 因为当前窗口的某些快捷键并不常规。在使用快捷键并不常规的窗口时，你应该只使用功能表现正常的空格编辑键位。

<br>

**为什么 Windows 版 Power Keys 每次运行都需要管理员权限？**

- 因为只有这样才能确保 Power Keys 的快捷键在任何软件下生效，从而为你带来最连贯的使用体验。

<br>

**为什么 Windows 版 Power Keys 的运行表现与帮助文档不相符？**

可能是因为：

- 你在不了解游戏模式的同时启用了它。请在 [了解游戏模式](/game) 后禁用它。

- 你使用了旧版本的 Power Keys。请将 Power Keys 更新到 [下载页面](/download) 所示的最新版本。

- 你的杀毒软件干扰了 Power Keys 的正常运行。请将 Power Keys 主程序添加到杀毒软件的白名单后重启 Power Keys。

  > 如果你使用 360 安全软件，你必须额外禁用 360 驱动防护。

  > 左击 Power Keys 的任务栏托盘图标即可重启 Power Keys，下同。

- 某些软件的快捷键与 Power Keys 相冲突。请关闭与 Power Keys 相冲突的软件后重启 Power Keys，或者临时启用 Power Keys 的 [游戏模式](/game)。

- Power Keys 的快捷键出现了内部错乱。这是所有键盘脚本软件的通病，重启 Power Keys 即可解决。

<br>

**如何彻底卸载 Windows 版 Power Keys？**

1. 在 Power Keys 的任务栏托盘菜单中取消勾选「开机自启」

2. 退出 Power Keys

3. 删除以下项目：

- Power Keys 主程序

- `HKEY_CURRENT_USER\Software\szzhiyang\Power Keys` 注册表项

- `%LocalAppData%\Power Keys` 文件夹

> 该文件夹存放着你亲自配置的 [光速启动](/launcher) 项，请注意备份。

<br>

**如何彻底卸载 macOS 版 Power Keys？**

1. 打开 Karabiner-Elements，切换到 Complex Modifications 页面，移除 Power Keys

2. 如果你不再使用 Karabiner-Elements，则切换到 Uninstall 页面，然后卸载它

3. 在终端执行 `sudo rm /Applications/.powerkeys` 命令

4. 删除 `~/Library/Application Support/Power Keys` 文件夹

> 该文件夹存放着你亲自配置的 [光速启动](/launcher) 项，请注意备份。
