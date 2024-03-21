## 什么是 Tor 浏览器？

Tor 是一款帮你私密浏览互联网的工具。它不仅能使你免受监控，还能帮你绕过最严格的互联网审查与封锁。

### 在中国怎样获得 Tor 浏览器？

1. 获得 Tor 浏览器桌面版和 Android 版

- Tor 浏览器的官方网站。中国大陆地区不能直接访问这个网站，需要翻墙。https://www.torproject.org/zh-CN/download/
- 如果不能翻墙访问官方网站，也可以从 Tor 官方指定的镜像网站下载。https://tor.calyxinstitute.org/zh-CN/download/
- 如果你能使用 Telegram，可以关注这个机器人 https://t.me/gettor_bot 找它要 Tor 浏览器的下载链接。
- 如果你习惯使用 Email，也可以发邮件给 gettor@torproject.org 索取 Tor 浏览器的下载链接。记得在邮件标题里注明你的电脑操作系统名称，比如 Windows，macOS 或者 Linux。邮件正文留白就行。为了你的安全，不要使用 QQ、163 这些中国的邮件服务。

2. 获得 Onion Browser（Tor 浏览器 iOS 版）

Onion Browser 是运行在 iOS 设备上的 Tor 浏览器。

遗憾的是，如果你使用中国区 Apple ID, 那你可能无法在 App Store 找到 Onion Browser. 你需要想办法先拥有一个【非中国区】的 Apple ID, 才能在 App Store 下载它。

### 在中国怎样连接到 Tor 网络？

Tor 的所有公开节点都已被 GFW 封锁。为了解决这个问题，Tor 提供几种“可插拔式传输器”（Pluggable Transports）用于突破封锁。目前共有四种：obfs4/meek/Snowflake/WebTunnel，其中meek在中国大陆已经几乎无法使用，以下介绍另外三种。

- obfs4 会将上网流量伪装成随机数据流量。如果在 Tor 浏览器的“内置网桥”里选择 obfs4 网桥，在中国大陆可能也很难连上。一般需要手动添加 obfs4 网桥。
- Snowflake 能把用户的 Tor 流量伪装成视频通话。在 Tor 浏览器的“内置网桥”里选择 Snowflake 就行，无须更多配置。
- WebTunnel 使用户的 Tor 流量看上去像普通的 HTTPS 流量。WebTunnel 网桥需要专门获取，手动添加。

以下这些方式可以帮你获得 obfs4 网桥或者 WebTunnel 网桥。

- 从 Tor 的官方网站获取 https://bridges.torproject.org/
- 发邮件给 bridges@torproject.org ，只支持 Gmail 和 Riseup 邮箱。
- 添加 Telegram 机器人 https://t.me/GetBridgesBot 获取

手动添加网桥的位置：进入 Tor 浏览器，找到【设置】→【连接】→【网桥】→【添加新网桥】→【手动添加网桥】。把前面复制的网桥地址完整地粘贴在这里，点击“确认”即可。

**如果以上途径获得的网桥无法正常连接，请发邮件给 frontdesk@torproject.org ，索取专门针对中国用户的网桥。你只需在邮件标题里写上“private bridge cn”即可收到回复。**

### 怎样可以获得帮助支持？

你有任何关于 Tor 浏览器的疑问和困难，都欢迎与我们联系。

- 电子邮件: frontdesk@torproject.org.
- 社区论坛：https://forum.torproject.org/
- Mastodon：https://mastodon.social/@tor4zh
- Telegram: https://t.me/torprojectsupportbot
- WhatsApp: https://wa.me/447421000612 
- Signal: https://signal.me/#p/+17787431312
