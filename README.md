## 如何在中国大陆绕过 GFW 防火长城连接到 Tor？

中国用户需额外步骤绕过防火长城连接到 Tor 网络。

要获得 Tor 浏览器的更新版本，先试试 Telegram 自动程序：https://t.me/gettor_bot。 如果不起作用，可以发送邮件至 gettor@torproject.org，并根据相应的操作系统，在邮件主题上写明“Windows”、“Macos”或“linux”操作系统。

安装后，Tor 浏览器将尝试连接 Tor 网络。 如果所在地屏蔽了 Tor，链接助手将试图通过网桥或者 Snowflake 连接。 但是如果这样也无法连接，第二步是获得在中国可以使用的网桥。

在中国使用 Tor 有三种选项：

1. Tor Snowflake：使用临时代理连接到 Tor 网络。 它可以在 Tor 浏览器和其他由 Tor 驱动的应用程序中使用，如Orbot。 你可以从 Tor 浏览器的内置网桥菜单中选择 Snowflake。
2. 未公开的私密 obfs4 网桥：找到我们的 Telegram 机器人 [@GetBridgesBot](https://t.me/GetBridgesBot) 并发送 /bridges 来获取网桥。 或者发送邮件到 frontdesk@torproject.org，并且邮件主题需要包含“private bridge cn”。 如果你懂些计算机技术，可以自己在中国境外搭建并运行 obfs4 网桥。 需要注意的是，通过 BridgeDB 获取的网桥以及 Tor 浏览器内置的 obfs4 网桥，很可能无法使用。
3. meek-azure：能让你伪装成访问微软的网站，而不是 Tor。 不过，因带宽限制这种网桥连接较慢。 你可以在 Tor 浏览器的内置网桥下拉菜单中选择 meek-azure。

如果以上某个选项无法使用，请查看 [Tor](https://support.torproject.org/zh-CN/connecting/connecting-2/) 日志并尝试其他方法。

如果需要帮助，可以从 Telegram [https://t.me/TorProjectSupportBot](https://t.me/TorProjectSupportBot) 和 [Signal](https://signal.me/#p/+17787431312) 上得到帮助。
