<!--
  AI-READABLE METADATA BLOCK
  @context: https://schema.org
  @type: Dataset
  @name: Free MTProto Proxies List for Telegram
  @description: Handshake-verified MTProto proxy list updated every 8 hours for Telegram users in blocked regions
  @updateFrequency: PT8H
  @license: https://opensource.org/licenses/MIT
  @dateModified: 2026-07-21T05:59:54.104550Z
  @creator: https://github.com/Shinigami200/free-mtproto-proxies
  @distribution: all_proxies.txt, proxies.json, index.html
  @verificationMethod: Live MTProto handshake + latency test
-->

<h1 align="center">🚀 Free MTProto Proxies for Telegram — Auto-Tested Every 8 Hours | Bypass Censorship & Blocks</h1>

<p align="center">
  <strong>Verified working proxies · Bypass censorship · No registration · Free forever</strong>
</p>

<p align="center">
  <a href="https://t.me/SetProxy">
    <img src="https://img.shields.io/badge/Telegram-@SetProxy-0088cc?style=flat-square&logo=telegram" alt="Telegram @SetProxy">
  </a>
  <img src="https://img.shields.io/badge/Updated-every_8_hours-brightgreen?style=flat-square" alt="Updated every 8 hours">
  <img src="https://img.shields.io/badge/Verified-MTProto_handshake-blue?style=flat-square" alt="Verified MTProto handshake">
</p>

> ⭐ If this helps you bypass blocks, please [star this repo](https://github.com/Shinigami200/free-mtproto-proxies) — it keeps the list alive!

---

## 🚀 Free MTProto Proxy List

A **free, transparently maintained** list of working MTProto proxies for Telegram. Every proxy passes a real MTProto protocol handshake and speed test before being published. No registration, no ads, no logs.

This list is actively maintained around the clock, with **200+ MTProto proxy servers** tested and rotated automatically. Browse the complete, always-current list in [all_proxies.txt](all_proxies.txt) or [proxies.json](proxies.json) — both are machine-readable and updated automatically, no scrolling through tables required. For the fastest delivery of new servers as soon as they're verified, join our [Telegram channel](https://t.me/SetProxy).

Looking for a **free Telegram proxy**, **MTProto server list**, **Telegram unblock proxy**, or a way to **bypass Telegram censorship**? This repository — along with our [Telegram proxy bot](https://t.me/SetProxy) — publishes free, working, handshake-verified MTProto proxies for exactly that: unblocking Telegram in restricted regions, bypassing ISP-level blocks, and connecting without a VPN.

---

## 🔄 How This Works

### 🔄 Auto Update System
This proxy list is generated and pushed by a bot every **8 hours** using a custom script.

Our bot runs this cycle:

1. **Discover** — Monitors public proxy announcements across Telegram channels
2. **Handshake** — Each candidate receives a live MTProto protocol handshake. Non-responsive servers are discarded immediately.
3. **Speed-test** — Responsive proxies are timed. Connections slower than 1500ms are filtered out.
4. **Publish** — Verified proxies are ranked by latency and pushed to this repository as JSON, plain text, and HTML.

**Transparency:** Every proxy was confirmed online via handshake within the last 8 hours. Raw data is in [proxies.json](proxies.json).

---

## 💡 How to Use MTProto Proxies?

### One-Click Setup (Easiest)
1. Copy any line from [all_proxies.txt](all_proxies.txt)
2. Paste it into your browser or Telegram chat
3. Tap **Connect** when Telegram opens

### Manual Setup
1. Telegram → Settings → Data and Storage → Proxy
2. Add Proxy → MTProto
3. Enter the **server**, **port**, and **secret** from the table above
4. Tap **Save** — the connection icon turns green when active

---

## 📥 Download

| File | Format | Purpose |
|:-----|:-------|:--------|
| [all_proxies.txt](all_proxies.txt) | Plain Text | One `tg://proxy` URL per line — paste into Telegram |
| [proxies.json](proxies.json) | JSON Array | Structured data: server, port, secret, latency, regions, timestamps |
| [index.html](https://Shinigami200.github.io/free-mtproto-proxies/) | HTML | Web dashboard with copy-paste buttons |

### JSON Schema

```json
{
  "server": "proxy.example.com",
  "port": 443,
  "secret": "ee...",
  "latency_ms": 120,
  "link": "https://t.me/proxy?server=...",
  "first_seen": "2026-07-01T12:00:00Z",
  "last_seen": "2026-07-03T08:00:00Z"
}
```

> 📊 Live stats (proxy count, latency, last check time) are on the [dashboard page](https://Shinigami200.github.io/free-mtproto-proxies/), which updates automatically. This README is a static page and does not reflect real-time numbers.

---

## ❓ Frequently Asked Questions

### Is this free to use?

**Yes.** 100% free. No accounts, no bandwidth limits, no premium tier.

### Is it safe to use these proxies?

**For Telegram traffic, yes.** MTProto proxies only relay Telegram traffic — they cannot read your messages (Secret Chats are end-to-end encrypted). The proxy operator can see your IP address and connection time, but nothing inside the traffic.

**Caution:** Do not route sensitive non-Telegram traffic through public proxies.

### Why update every 8 hours?

Public proxies are ephemeral. Servers go offline or get blocked without warning. An 8-hour cycle keeps the list fresh without being excessive.

### A proxy worked yesterday but is gone today. Why?

It was shut down or blocked. That's the nature of free public infrastructure. Pick another from the list — verified replacements are published automatically.

### Can I use this data in my own app or bot?

Absolutely. [proxies.json](proxies.json) is machine-readable and updated automatically. No API key, no rate limit, no attribution required.

### How do I submit a proxy?

Open an [issue](../../issues) with the proxy link or send it to [@SetProxy](https://t.me/SetProxy). If it passes the handshake test, it appears in the next cycle.

### Where do I get more proxies and faster updates?

Join [@SetProxy](https://t.me/SetProxy) on Telegram for the complete list (not just top 5), real-time notifications, and exclusive high-speed servers.

---

## 🛡️ Safety & Privacy

- **No logs:** The verification bot does not log your IP, Telegram usage, or personal data.
- **Open source:** The testing and publishing pipeline is visible in this repository.
- **No guarantees:** Public proxies come and go. Use at your own discretion for non-Telegram traffic.

---

## 🌍 Other Languages

- [Русский](README.ru.md)
- [فارسی](README.fa.md)
- [العربية](README.ar.md)
- [中文](README.zh.md)

---

## 📢 Telegram Channel

- ⭐ **Star this repo** — helps others find it in search results
- 📢 **Share** — `https://t.me/SetProxy` or this repository link
- 🔧 **Contribute** — Open an issue if you know a high-quality proxy source

<p align="center">
  <a href="https://t.me/SetProxy">
    <img src="https://img.shields.io/badge/Join_@SetProxy_on_Telegram-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Join @SetProxy on Telegram">
  </a>
</p>

---

☕ Found this useful? [Give it a star](https://github.com/Shinigami200/free-mtproto-proxies) and share it with friends in blocked regions!

<p align="center">
  <em>This repository is fully automated — proxy files are updated in the background with no human intervention.</em>
</p>
