# CardPass — releases

**English** | [中文](#中文)

Downloads and release notes for **CardPass**, an open-source Android NFC card wallet and reader.

## What it is

CardPass turns an Android phone into a reader for transit smart cards and a safe place to keep them:

- Reads China T-Union / City Union / Shenzhen Tong / Yangcheng Tong / Suzhou / Tianjin / Octopus and many other transit cards.
- Prices the whole chip: composite cards (for example T-Union + City Union + PBOC) are read application by application, and each application gets its own details block.
- Keeps ride history, monthly statistics, station names resolved offline from bundled station databases, and per-city discount progress.
- Reads bank cards (EMV) read-only, with masked storage.
- Reads and writes NDEF tags (Text, URI, vCard, Wi-Fi, Bluetooth, Smart Poster, custom MIME), including formatting blank NT2 tags.
- Shows a tag information card (type, chip, technologies, UID, ATQA, SAK, data format, capacity, writable, NDEF records).
- Checks for updates inside the app.

## Privacy

- Cards, rides and settings stay on the device in an encrypted store.
- No account, no analytics, no ads. The network is used only for update checks and optional map data.
- Plaintext read logs are written only when the developer switch is enabled, and can be exported as a zip on demand.

## Install

1. Download `CardPass-<version>.apk` from [Releases](../../releases).
2. Allow "Install unknown apps" for your browser/file manager.
3. Install over an older version — every release uses the same signing key.

## Links

- Source code: <https://github.com/star-picker/cardpass-Android>
- License: MIT

---

## 中文

**中文** | [English](#cardpass--releases)

这里是 **CardPass** 的下载与发布说明。CardPass 是一个开源的 Android NFC 卡片钱包与读卡器。

## 它能做什么

- 读取交通联合 / 城市一卡通 / 深圳通 / 岭南通 / 苏州通 / 天津通 / 八达通等交通卡;
- 按应用解析整张芯片:复合卡(例如 交通联合 + 城市一卡通 + PBOC)逐个应用读取,每个应用单独一块详情;
- 保留乘车记录、月度统计,离线站点库解析站名,并按城市显示优惠消费进度条;
- 只读读取银行卡(EMV),敏感信息加密保存;
- 读写 NDEF 标签(文本、链接、名片、Wi-Fi、蓝牙、智能海报、自定义 MIME),支持格式化空白 NTAG;
- 显示标签详情卡(类型、芯片、技术、UID、ATQA、SAK、数据格式、容量、可写、NDEF 记录);
- 应用内检查更新。

## 隐私

- 卡片、行程与设置都保存在设备本地的加密库中;
- 没有账号、没有统计、没有广告;联网只用于检查更新与可选的地图数据;
- 只有打开开发者开关时才写明文读卡日志,并且可以随时打包导出。

## 安装

1. 从 [Releases](../../releases) 下载 `CardPass-<版本>.apk`;
2. 给浏览器/文件管理器打开“安装未知应用”权限;
3. 覆盖安装旧版本即可 —— 所有版本使用同一签名。

## 链接

- 源码:<https://github.com/star-picker/cardpass-Android>
- 许可证:MIT
