# Clash 机场订阅节点检测与 Ping0 IP 风险分析报告

> [!NOTE]
> 本次检测使用 Clash Meta (Mihomo) 内核对订阅内全部 89 个节点进行了独立的全局代理路由与连通性测试，并将每个节点真实的出口 IP 对应到 [Ping0.cc](https://ping0.cc) 数据库中抓取了与参考样例完全一致的检测卡片截图。

## 一、检测概要

- **订阅总节点数**：89
- **连通成功节点**：88
- **连接异常/离线**：1 (`65: 新加坡-1`)
- **出口独立 IP 数量**：4 个核心 IP 池
- **完整图片保存目录**：`C:\Users\Administrator\.gemini\antigravity\scratch\clash_results_by_node` (共 88 张以各节点名称命名的独立卡片截图)

## 二、4 个出口 IP 详细属性与卡片预览

### IP: `118.104.213.9` (日本 爱知县 濑户市)
- **归属位置**：日本 爱知县 濑户市
- **运营商/ASN**：AS18126 (Chubu Telecommunications Company, Inc.)
- **IP 类型**：`家庭宽带 IP (原生)`
- **风控值**：`7% 极度纯净`
- **业务适用建议**：TikTok / 跨境电商 / 社媒 / AI (非常适合)

![Ping0 检测结果 - 118.104.213.9](C:/Users/Administrator/.gemini/antigravity/brain/c6915dbb-3fc4-4d2b-9db3-b9802b031e83/118.104.213.9.png)

### IP: `119.194.79.177` (韩国 首尔特别市)
- **归属位置**：韩国 首尔特别市
- **运营商/ASN**：AS4766 (Korea Telecom)
- **IP 类型**：`IDC机房 IP (原生)`
- **风控值**：`7% 极度纯净`
- **业务适用建议**：AI 适合 / TikTok、电商可尝试

![Ping0 检测结果 - 119.194.79.177](C:/Users/Administrator/.gemini/antigravity/brain/c6915dbb-3fc4-4d2b-9db3-b9802b031e83/119.194.79.177.png)

### IP: `192.166.82.208` (美国 犹他州 盐湖城)
- **归属位置**：美国 犹他州 盐湖城
- **运营商/ASN**：AS207847 (CloudBlast LLC / UAB Linama)
- **IP 类型**：`IDC机房 IP (广播)`
- **风控值**：`38% 中性`
- **业务适用建议**：不推荐电商与TikTok

![Ping0 检测结果 - 192.166.82.208](C:/Users/Administrator/.gemini/antigravity/brain/c6915dbb-3fc4-4d2b-9db3-b9802b031e83/192.166.82.208.png)

### IP: `192.166.82.226` (美国 犹他州 盐湖城)
- **归属位置**：美国 犹他州 盐湖城
- **运营商/ASN**：AS207847 (CloudBlast LLC / UAB Linama)
- **IP 类型**：`IDC机房 IP (广播)`
- **风控值**：`34% 中性`
- **业务适用建议**：不推荐电商与TikTok

![Ping0 检测结果 - 192.166.82.226](C:/Users/Administrator/.gemini/antigravity/brain/c6915dbb-3fc4-4d2b-9db3-b9802b031e83/192.166.82.226.png)

## 三、全节点与出口 IP / 截图文件对照表

| 序号 | 节点名称 | 协议类型 | 真实出口 IP | 实际归属区域 | IP属性/风控 | 对应截图文件名 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 01 | `🚀提示：延迟显示可能偏高，不影响实际访问速度，请以实测为准` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`01_🚀提示：延迟显示可能偏高，不影响实际访问速度，请以实测为准_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/01_🚀提示：延迟显示可能偏高，不影响实际访问速度，请以实测为准_192.166.82.226.png) |
| 02 | `🚀推荐选最上方靠前节点：选定即用，自动路由支持全部网站加速，无需频繁更换` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`02_🚀推荐选最上方靠前节点：选定即用，自动路由支持全部网站加速，无需频繁更换_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/02_🚀推荐选最上方靠前节点：选定即用，自动路由支持全部网站加速，无需频繁更换_192.166.82.208.png) |
| 03 | `🚀🚀🚀选下方标了[稳定]的节点(无需频繁更换)🚀🚀🚀` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`03_🚀🚀🚀选下方标了[稳定]的节点(无需频繁更换)🚀🚀🚀_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/03_🚀🚀🚀选下方标了[稳定]的节点(无需频繁更换)🚀🚀🚀_192.166.82.208.png) |
| 04 | `推荐-旧协议专线-适配旧软件-1` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`04_推荐-旧协议专线-适配旧软件-1_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/04_推荐-旧协议专线-适配旧软件-1_192.166.82.226.png) |
| 05 | `推荐-旧协议专线-适配旧软件-2` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`05_推荐-旧协议专线-适配旧软件-2_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/05_推荐-旧协议专线-适配旧软件-2_192.166.82.226.png) |
| 06 | `🚀当前软件可能太旧（如果你看不到新协议节点）` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`06_🚀当前软件可能太旧（如果你看不到新协议节点）_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/06_🚀当前软件可能太旧（如果你看不到新协议节点）_192.166.82.226.png) |
| 07 | `🚀当前软件可能太旧（请去官网文档重新下载软件）` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`07_🚀当前软件可能太旧（请去官网文档重新下载软件）_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/07_🚀当前软件可能太旧（请去官网文档重新下载软件）_192.166.82.226.png) |
| 08 | `🚀🚀🚀软件比较旧可以用下面旧协议节点(推荐用官网上的软件，支持全部新协议)🚀🚀🚀` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`08_🚀🚀🚀软件比较旧可以用下面旧协议节点(推荐用官网上的软件，支持全部新协议)🚀🚀🚀_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/08_🚀🚀🚀软件比较旧可以用下面旧协议节点(推荐用官网上的软件，支持全部新协议)🚀🚀🚀_192.166.82.226.png) |
| 09 | `推荐-旧协议专线-vl-稳定-1` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`09_推荐-旧协议专线-vl-稳定-1_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/09_推荐-旧协议专线-vl-稳定-1_192.166.82.226.png) |
| 10 | `推荐-旧协议专线-vl-稳定-2` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`10_推荐-旧协议专线-vl-稳定-2_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/10_推荐-旧协议专线-vl-稳定-2_192.166.82.226.png) |
| 11 | `推荐-旧协议专线-vl-稳定-3` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`11_推荐-旧协议专线-vl-稳定-3_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/11_推荐-旧协议专线-vl-稳定-3_192.166.82.226.png) |
| 12 | `推荐-旧协议专线-vl-ipv6-1` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`12_推荐-旧协议专线-vl-ipv6-1_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/12_推荐-旧协议专线-vl-ipv6-1_192.166.82.226.png) |
| 13 | `推荐-旧协议专线-vl-ipv6-2` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`13_推荐-旧协议专线-vl-ipv6-2_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/13_推荐-旧协议专线-vl-ipv6-2_192.166.82.226.png) |
| 14 | `推荐-旧协议专线-vl-ipv6-3` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`14_推荐-旧协议专线-vl-ipv6-3_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/14_推荐-旧协议专线-vl-ipv6-3_192.166.82.226.png) |
| 15 | `🚀当前软件可能太旧（如果你在最前面看到我）` | `vmess` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`15_🚀当前软件可能太旧（如果你在最前面看到我）_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/15_🚀当前软件可能太旧（如果你在最前面看到我）_192.166.82.226.png) |
| 16 | `推荐-旧协议-1` | `vmess` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`16_推荐-旧协议-1_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/16_推荐-旧协议-1_192.166.82.226.png) |
| 17 | `推荐-旧协议-2` | `vmess` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`17_推荐-旧协议-2_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/17_推荐-旧协议-2_192.166.82.226.png) |
| 18 | `推荐-旧协议-3` | `vmess` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`18_推荐-旧协议-3_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/18_推荐-旧协议-3_192.166.82.226.png) |
| 19 | `以下是旧协议节点需要开启设置里IPv6 (如果用不了，请用官网上的软件，支持全部新协议)` | `vmess` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`19_以下是旧协议节点需要开启设置里IPv6 (如果用不了，请用官网上的软件，支持全部_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/19_以下是旧协议节点需要开启设置里IPv6 (如果用不了，请用官网上的软件，支持全部_118.104.213.9.png) |
| 20 | `美国1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`20_美国1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/20_美国1_192.166.82.208.png) |
| 21 | `美国2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`21_美国2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/21_美国2_192.166.82.208.png) |
| 22 | `日本1` | `vless` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`22_日本1_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/22_日本1_118.104.213.9.png) |
| 23 | `日本2` | `vless` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`23_日本2_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/23_日本2_118.104.213.9.png) |
| 24 | `韩国1` | `vless` | `119.194.79.177` | 韩国 | IDC机房 IP (原生) (7% 极度纯净) | [`24_韩国1_119.194.79.177.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/24_韩国1_119.194.79.177.png) |
| 25 | `韩国2` | `vless` | `119.194.79.177` | 韩国 | IDC机房 IP (原生) (7% 极度纯净) | [`25_韩国2_119.194.79.177.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/25_韩国2_119.194.79.177.png) |
| 26 | `新加坡1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`26_新加坡1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/26_新加坡1_192.166.82.208.png) |
| 27 | `新加坡2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`27_新加坡2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/27_新加坡2_192.166.82.208.png) |
| 28 | `台湾1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`28_台湾1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/28_台湾1_192.166.82.208.png) |
| 29 | `台湾2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`29_台湾2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/29_台湾2_192.166.82.208.png) |
| 30 | `香港1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`30_香港1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/30_香港1_192.166.82.208.png) |
| 31 | `香港2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`31_香港2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/31_香港2_192.166.82.208.png) |
| 32 | `加拿大1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`32_加拿大1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/32_加拿大1_192.166.82.208.png) |
| 33 | `加拿大2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`33_加拿大2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/33_加拿大2_192.166.82.208.png) |
| 34 | `印度1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`34_印度1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/34_印度1_192.166.82.208.png) |
| 35 | `印度2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`35_印度2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/35_印度2_192.166.82.208.png) |
| 36 | `德国1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`36_德国1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/36_德国1_192.166.82.208.png) |
| 37 | `德国2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`37_德国2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/37_德国2_192.166.82.208.png) |
| 38 | `印度尼西亚1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`38_印度尼西亚1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/38_印度尼西亚1_192.166.82.208.png) |
| 39 | `印度尼西亚2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`39_印度尼西亚2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/39_印度尼西亚2_192.166.82.208.png) |
| 40 | `泰国1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`40_泰国1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/40_泰国1_192.166.82.208.png) |
| 41 | `泰国2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`41_泰国2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/41_泰国2_192.166.82.208.png) |
| 42 | `墨西哥1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`42_墨西哥1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/42_墨西哥1_192.166.82.208.png) |
| 43 | `墨西哥2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`43_墨西哥2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/43_墨西哥2_192.166.82.208.png) |
| 44 | `土耳其1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`44_土耳其1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/44_土耳其1_192.166.82.208.png) |
| 45 | `土耳其2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`45_土耳其2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/45_土耳其2_192.166.82.208.png) |
| 46 | `英国1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`46_英国1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/46_英国1_192.166.82.208.png) |
| 47 | `英国2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`47_英国2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/47_英国2_192.166.82.208.png) |
| 48 | `法国1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`48_法国1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/48_法国1_192.166.82.208.png) |
| 49 | `法国2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`49_法国2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/49_法国2_192.166.82.208.png) |
| 50 | `西班牙1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`50_西班牙1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/50_西班牙1_192.166.82.208.png) |
| 51 | `西班牙2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`51_西班牙2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/51_西班牙2_192.166.82.208.png) |
| 52 | `巴西1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`52_巴西1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/52_巴西1_192.166.82.208.png) |
| 53 | `巴西2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`53_巴西2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/53_巴西2_192.166.82.208.png) |
| 54 | `澳大利亚1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`54_澳大利亚1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/54_澳大利亚1_192.166.82.208.png) |
| 55 | `澳大利亚2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`55_澳大利亚2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/55_澳大利亚2_192.166.82.208.png) |
| 56 | `俄罗斯1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`56_俄罗斯1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/56_俄罗斯1_192.166.82.208.png) |
| 57 | `俄罗斯2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`57_俄罗斯2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/57_俄罗斯2_192.166.82.208.png) |
| 58 | `日本-1` | `vmess` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`58_日本-1_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/58_日本-1_118.104.213.9.png) |
| 59 | `日本-2` | `vmess` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`59_日本-2_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/59_日本-2_118.104.213.9.png) |
| 60 | `日本-3` | `vmess` | `118.104.213.9` | 日本 | 家庭宽带 IP (原生) (7% 极度纯净) | [`60_日本-3_118.104.213.9.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/60_日本-3_118.104.213.9.png) |
| 61 | `韩国-1` | `vmess` | `119.194.79.177` | 韩国 | IDC机房 IP (原生) (7% 极度纯净) | [`61_韩国-1_119.194.79.177.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/61_韩国-1_119.194.79.177.png) |
| 62 | `韩国-2` | `vmess` | `119.194.79.177` | 韩国 | IDC机房 IP (原生) (7% 极度纯净) | [`62_韩国-2_119.194.79.177.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/62_韩国-2_119.194.79.177.png) |
| 63 | `韩国-3` | `vmess` | `119.194.79.177` | 韩国 | IDC机房 IP (原生) (7% 极度纯净) | [`63_韩国-3_119.194.79.177.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/63_韩国-3_119.194.79.177.png) |
| 64 | `新加坡-1` | `vmess` | ❌ 超时 | 无 | 离线/不可用 | 无 |
| 65 | `新加坡-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`65_新加坡-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/65_新加坡-2_192.166.82.208.png) |
| 66 | `新加坡-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`66_新加坡-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/66_新加坡-3_192.166.82.208.png) |
| 67 | `台湾-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`67_台湾-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/67_台湾-1_192.166.82.208.png) |
| 68 | `台湾-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`68_台湾-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/68_台湾-2_192.166.82.208.png) |
| 69 | `台湾-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`69_台湾-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/69_台湾-3_192.166.82.208.png) |
| 70 | `香港-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`70_香港-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/70_香港-1_192.166.82.208.png) |
| 71 | `香港-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`71_香港-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/71_香港-2_192.166.82.208.png) |
| 72 | `香港-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`72_香港-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/72_香港-3_192.166.82.208.png) |
| 73 | `加拿大-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`73_加拿大-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/73_加拿大-1_192.166.82.208.png) |
| 74 | `加拿大-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`74_加拿大-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/74_加拿大-2_192.166.82.208.png) |
| 75 | `加拿大-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`75_加拿大-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/75_加拿大-3_192.166.82.208.png) |
| 76 | `荷兰-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`76_荷兰-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/76_荷兰-1_192.166.82.208.png) |
| 77 | `荷兰-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`77_荷兰-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/77_荷兰-2_192.166.82.208.png) |
| 78 | `荷兰-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`78_荷兰-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/78_荷兰-3_192.166.82.208.png) |
| 79 | `印度-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`79_印度-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/79_印度-1_192.166.82.208.png) |
| 80 | `印度-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`80_印度-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/80_印度-2_192.166.82.208.png) |
| 81 | `印度-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`81_印度-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/81_印度-3_192.166.82.208.png) |
| 82 | `德国-1` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`82_德国-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/82_德国-1_192.166.82.208.png) |
| 83 | `德国-2` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`83_德国-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/83_德国-2_192.166.82.208.png) |
| 84 | `德国-3` | `vmess` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`84_德国-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/84_德国-3_192.166.82.208.png) |
| 85 | `🚀🚀🚀如果晚上前面的节点在你的地区比较慢可以连下面的推荐旧协议晚高峰专线🚀🚀🚀` | `vless` | `192.166.82.226` | 美国 | IDC机房 IP (广播) (34% 中性) | [`85_🚀🚀🚀如果晚上前面的节点在你的地区比较慢可以连下面的推荐旧协议晚高峰专线🚀🚀🚀_192.166.82.226.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/85_🚀🚀🚀如果晚上前面的节点在你的地区比较慢可以连下面的推荐旧协议晚高峰专线🚀🚀🚀_192.166.82.226.png) |
| 86 | `旧协议-高峰极速专线-1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`86_旧协议-高峰极速专线-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/86_旧协议-高峰极速专线-1_192.166.82.208.png) |
| 87 | `旧协议-高峰极速专线-2` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`87_旧协议-高峰极速专线-2_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/87_旧协议-高峰极速专线-2_192.166.82.208.png) |
| 88 | `旧协议-高峰极速专线-3` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`88_旧协议-高峰极速专线-3_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/88_旧协议-高峰极速专线-3_192.166.82.208.png) |
| 89 | `旧协议-特殊网络优化专线-1` | `vless` | `192.166.82.208` | 美国 | IDC机房 IP (广播) (38% 中性) | [`89_旧协议-特殊网络优化专线-1_192.166.82.208.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_by_node/89_旧协议-特殊网络优化专线-1_192.166.82.208.png) |