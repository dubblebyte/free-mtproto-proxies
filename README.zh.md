<!-- README.md 的翻译版本。此文件为静态文件，不会每个周期自动重新生成——实时数据请查看 all_proxies.txt、proxies.json 和 index.html。 -->

<h1 align="center">免费 Telegram MTProto 代理 — 每 8 小时自动测试 | 突破审查与封锁</h1>

<p align="center">
  <strong>已验证的可用代理 · 突破审查 · 无需注册 · 永久免费</strong>
</p>

<p align="center">
  <a href="https://t.me/SetProxy">
    <img src="https://img.shields.io/badge/Telegram-@SetProxy-0088cc?style=flat-square&logo=telegram" alt="Telegram @SetProxy">
  </a>
  <img src="https://img.shields.io/badge/更新频率-每8小时-brightgreen?style=flat-square" alt="每8小时更新">
  <img src="https://img.shields.io/badge/已验证-MTProto_handshake-blue?style=flat-square" alt="已通过 MTProto handshake 验证">
</p>

> ⭐ 如果这份列表帮你突破了封锁，请为[这个仓库加星](https://github.com/Shinigami200/free-mtproto-proxies) —— 这能让项目持续维护下去！

---

## 🚀 免费 MTProto 代理列表

这是一份**免费、透明维护**的 Telegram MTProto 可用代理列表。每个代理在发布前都会经过真实的 MTProto 协议握手测试和速度测试。无需注册，无广告，不记录日志。

本列表全天候持续维护，目标是自动测试并轮换 **200 多个 MTProto 代理服务器**。完整且始终最新的列表请查看 [all_proxies.txt](all_proxies.txt) 或 [proxies.json](proxies.json)，或加入我们的 [Telegram 频道](https://t.me/SetProxy) 以最快速度获取新代理。

正在寻找**免费 Telegram 代理**、**MTProto 服务器列表**、**Telegram 解锁代理**，或者**翻墙访问 Telegram** 的方法？本仓库与我们的 [Telegram 机器人](https://t.me/SetProxy) 正是为此而生：提供免费、经过握手验证的 MTProto 代理，帮助在网络受限地区解锁 Telegram，无需 VPN。

---

## 🔄 工作原理

我们的机器人每 **8 小时**执行一次以下流程：

1. **发现** — 监控各个 Telegram 公开频道中发布的新代理
2. **握手测试** — 每个候选代理都会收到一次真实的 MTProto 协议握手。无响应的服务器会被立即剔除。
3. **速度测试** — 对响应成功的代理进行延迟测速，延迟高于 1500 毫秒的连接会被过滤掉。
4. **发布** — 通过验证的代理按延迟排序，以 JSON、纯文本和 HTML 格式发布到本仓库。

**透明度：** 每个代理在发布时的过去 8 小时内都通过了握手验证。原始数据见 [proxies.json](proxies.json)。

---

## 💡 使用方法

### 一键设置（最简单）
1. 从 [all_proxies.txt](all_proxies.txt) 复制任意一行
2. 粘贴到浏览器或 Telegram 聊天框中
3. Telegram 打开后点击 **Connect**

### 手动设置
1. Telegram → 设置 → 数据和存储 → 代理
2. 添加代理 → MTProto
3. 从列表中输入**服务器**、**端口**和**密钥**
4. 点击**保存** —— 连接成功后图标会变绿

---

## 📥 下载

| 文件 | 格式 | 用途 |
|:-----|:-------|:--------|
| [all_proxies.txt](all_proxies.txt) | 纯文本 | 每行一个 `tg://proxy` 链接 —— 直接粘贴到 Telegram |
| [proxies.json](proxies.json) | JSON | 结构化数据：服务器、端口、密钥、延迟、地区 |
| [index.html](https://Shinigami200.github.io/free-mtproto-proxies/) | HTML | 带一键复制按钮的网页面板 |

---

## ❓ 常见问题

### 这是免费的吗？
**是的。** 100% 免费。无需账号，无流量限制，没有付费套餐。

### 使用这些代理安全吗？
**对于 Telegram 流量来说是安全的。** MTProto 代理只转发 Telegram 流量，无法读取你的消息内容（秘密聊天采用端到端加密）。代理运营者能看到你的 IP 地址和连接时间，但看不到流量内容。

**注意：** 请勿通过公共代理传输与 Telegram 无关的敏感流量。

### 为什么每 8 小时更新一次？
公共代理的寿命通常很短，服务器可能随时下线或被封锁而不会提前通知。8 小时的更新周期能让列表保持新鲜,同时不会造成不必要的负担。

### 我可以在自己的应用或机器人中使用这些数据吗？
当然可以。[proxies.json](proxies.json) 是机器可读格式，会自动更新，无需 API 密钥，也没有请求次数限制。

### 如何提交一个代理？
提交一个带代理链接的 [issue](../../issues)，或直接发送给 [@SetProxy](https://t.me/SetProxy)。只要通过握手测试，就会出现在下一个周期中。

---

## 🛡️ 安全与隐私

- **不记录日志：** 验证机器人不会记录你的 IP、Telegram 使用情况或个人数据。
- **开源透明：** 测试与发布流程在本仓库中公开可见。
- **不做任何保证：** 公共代理来来去去。请自行承担使用非 Telegram 流量的风险。

---

## 🌍 其他语言

- [English](README.md)
- [Русский](README.ru.md)
- [فارسی](README.fa.md)
- [العربية](README.ar.md)

---

## 📢 Telegram 频道

- ⭐ **为本仓库加星** —— 帮助其他人在搜索结果中找到它
- 📢 **分享** —— `https://t.me/SetProxy` 或本仓库链接
- 🔧 **贡献** —— 如果你知道优质的代理来源，欢迎提交 issue

<p align="center">
  <a href="https://t.me/SetProxy">
    <img src="https://img.shields.io/badge/加入_@SetProxy-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="在 Telegram 上加入 @SetProxy">
  </a>
</p>

---

☕ 觉得这个项目有用？[加个星标](https://github.com/Shinigami200/free-mtproto-proxies)，分享给身处受限地区的朋友吧！

<p align="center">
  <em>本仓库完全自动化运行——代理文件在后台自动更新，无需人工干预。</em>
</p>
