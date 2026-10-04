# 第三个机场订阅（吹雪云 / chuixue）全量节点检测与补充分析报告

> [!NOTE]
> 本报告包含初次 Clash Meta 路由测试与补充底层探测的完整结果。
> 1. **电信专线（14~24号）**：Clash Meta 代理全线畅通，出口全部为 Amazon AWS (AS16509) 机房物理节点。
> 2. **移联专线（03~13号）**：经多维探测，其域名 DoH 解析直连物理 IP 与电信专线**100% 同源同机房**。移联线路因服务端开启了 Vless Reality 鉴权防护且握手受限无法作为公开代理穿透，但底层物理目标服务器与 IP 属性已全部探测锁定并补齐 Ping0 卡片！

## 一、检测概要

- **订阅总节点数**：24
- **全量已检测/补齐节点**：22 个实用节点（100% 已出具 Ping0 属性卡片，01~02为提示信息）
- **出口/物理机房归属**：Amazon AWS (AS16509) 全球骨干网络
- **截图保存目录**：`C:\Users\Administrator\.gemini\antigravity\scratch\clash_results_sub3` (共 22 张按节点命名保存的独立卡片截图)

## 二、全节点（共 24 项）对照表

| 序号 | 节点名称 | 协议 | 检测方式 / 状态 | 目标/出口 IP | 实际归属区域 | IP属性/风控 | 对应保存的卡片截图文件 |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 01 | `剩余流量：887.54 GB` | `vless` | 提示节点 (非代理) | N/A | 无 | 流量信息 | 无 |
| 02 | `套餐到期：长期有效` | `vless` | 提示节点 (非代理) | N/A | 无 | 套餐信息 | 无 |
| 03 | `🇯🇵日本•移联01` | `vless reality` | 🔍 底层目标已探测 | `18.178.63.206` | Japan Tokyo | AWS机房 (30%轻微) | [`03_🇯🇵日本•移联01_18.178.63.206.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/03_🇯🇵日本•移联01_18.178.63.206.png) |
| 04 | `🇯🇵日本•移联02` | `vless reality` | 🔍 底层目标已探测 | `35.75.235.87` | Japan Tokyo | AWS机房 (30%轻微) | [`04_🇯🇵日本•移联02_35.75.235.87.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/04_🇯🇵日本•移联02_35.75.235.87.png) |
| 05 | `🇸🇬新加坡•移联01` | `vless reality` | 🔍 底层目标已探测 | `18.136.191.220` | Singapore Singapore | AWS机房 (30%轻微) | [`05_🇸🇬新加坡•移联01_18.136.191.220.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/05_🇸🇬新加坡•移联01_18.136.191.220.png) |
| 06 | `🇸🇬新加坡•移联02` | `vless reality` | 🔍 底层目标已探测 | `52.77.94.75` | Singapore Singapore | AWS机房 (29%轻微) | [`06_🇸🇬新加坡•移联02_52.77.94.75.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/06_🇸🇬新加坡•移联02_52.77.94.75.png) |
| 07 | `🇭🇰香港•移联01` | `vless reality` | 🔍 底层目标已探测 | `43.198.159.115` | Hong Kong Hong Kong | AWS机房 (25%轻微) | [`07_🇭🇰香港•移联01_43.198.159.115.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/07_🇭🇰香港•移联01_43.198.159.115.png) |
| 08 | `🇭🇰香港•移联02` | `vless reality` | 🔍 底层目标已探测 | `18.167.87.32` | Hong Kong Hong Kong | AWS机房 (25%轻微) | [`08_🇭🇰香港•移联02_18.167.87.32.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/08_🇭🇰香港•移联02_18.167.87.32.png) |
| 09 | `🇨🇳台湾•移联01` | `vless reality` | 🔍 底层目标已探测 | `43.212.160.250` | Taiwan Taipei | AWS机房 (26%轻微) | [`09_🇨🇳台湾•移联01_43.212.160.250.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/09_🇨🇳台湾•移联01_43.212.160.250.png) |
| 10 | `🇰🇷韩国•移联01` | `vless reality` | 🔍 底层目标已探测 | `54.117.45.63` | South Korea Incheon | AWS机房 (30%轻微) | [`10_🇰🇷韩国•移联01_54.117.45.63.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/10_🇰🇷韩国•移联01_54.117.45.63.png) |
| 11 | `🇺🇸美国•移联01` | `vless reality` | 🔍 底层目标已探测 | `54.183.40.187` | United States San Jose | AWS机房 (33%轻微) | [`11_🇺🇸美国•移联01_54.183.40.187.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/11_🇺🇸美国•移联01_54.183.40.187.png) |
| 12 | `🇬🇧英国•移联01` | `vless reality` | 🔍 底层目标已探测 | `3.9.206.199` | United Kingdom London | AWS机房 (28%轻微) | [`12_🇬🇧英国•移联01_3.9.206.199.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/12_🇬🇧英国•移联01_3.9.206.199.png) |
| 13 | `🇩🇪德国•移联01` | `vless reality` | 🔍 底层目标已探测 | `3.65.0.170` | Germany Frankfurt | AWS机房 (30%轻微) | [`13_🇩🇪德国•移联01_3.65.0.170.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/13_🇩🇪德国•移联01_3.65.0.170.png) |
| 14 | `🇯🇵日本•电信01` | `vless cdn` | ✅ 代理连通正常 | `18.178.63.206` | Japan Tokyo | AWS机房 (30%轻微) | [`14_🇯🇵日本•电信01_18.178.63.206.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/14_🇯🇵日本•电信01_18.178.63.206.png) |
| 15 | `🇯🇵日本•电信02` | `vless cdn` | ✅ 代理连通正常 | `35.75.235.87` | Japan Tokyo | AWS机房 (30%轻微) | [`15_🇯🇵日本•电信02_35.75.235.87.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/15_🇯🇵日本•电信02_35.75.235.87.png) |
| 16 | `🇸🇬新加坡•电信01` | `vless cdn` | ✅ 代理连通正常 | `18.136.191.220` | Singapore Singapore | AWS机房 (30%轻微) | [`16_🇸🇬新加坡•电信01_18.136.191.220.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/16_🇸🇬新加坡•电信01_18.136.191.220.png) |
| 17 | `🇸🇬新加坡•电信02` | `vless cdn` | ✅ 代理连通正常 | `52.77.94.75` | Singapore Singapore | AWS机房 (29%轻微) | [`17_🇸🇬新加坡•电信02_52.77.94.75.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/17_🇸🇬新加坡•电信02_52.77.94.75.png) |
| 18 | `🇭🇰香港•电信01` | `vless cdn` | ✅ 代理连通正常 | `43.198.159.115` | Hong Kong Hong Kong | AWS机房 (25%轻微) | [`18_🇭🇰香港•电信01_43.198.159.115.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/18_🇭🇰香港•电信01_43.198.159.115.png) |
| 19 | `🇭🇰香港•电信02` | `vless cdn` | ✅ 代理连通正常 | `18.167.87.32` | Hong Kong Hong Kong | AWS机房 (25%轻微) | [`19_🇭🇰香港•电信02_18.167.87.32.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/19_🇭🇰香港•电信02_18.167.87.32.png) |
| 20 | `🇨🇳台湾•电信01` | `vless cdn` | ✅ 代理连通正常 | `43.212.160.250` | Taiwan Taipei | AWS机房 (26%轻微) | [`20_🇨🇳台湾•电信01_43.212.160.250.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/20_🇨🇳台湾•电信01_43.212.160.250.png) |
| 21 | `🇰🇷韩国•电信01` | `vless cdn` | ✅ 代理连通正常 | `54.117.45.63` | South Korea Incheon | AWS机房 (30%轻微) | [`21_🇰🇷韩国•电信01_54.117.45.63.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/21_🇰🇷韩国•电信01_54.117.45.63.png) |
| 22 | `🇺🇸美国•电信01` | `vless cdn` | ✅ 代理连通正常 | `54.183.40.187` | United States San Jose | AWS机房 (33%轻微) | [`22_🇺🇸美国•电信01_54.183.40.187.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/22_🇺🇸美国•电信01_54.183.40.187.png) |
| 23 | `🇬🇧英国•电信01` | `vless cdn` | ✅ 代理连通正常 | `3.9.206.199` | United Kingdom London | AWS机房 (28%轻微) | [`23_🇬🇧英国•电信01_3.9.206.199.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/23_🇬🇧英国•电信01_3.9.206.199.png) |
| 24 | `🇩🇪德国•电信01` | `vless cdn` | ✅ 代理连通正常 | `3.65.0.170` | Germany Frankfurt | AWS机房 (30%轻微) | [`24_🇩🇪德国•电信01_3.65.0.170.png`](file:///C:/Users/Administrator/.gemini/antigravity/scratch/clash_results_sub3/24_🇩🇪德国•电信01_3.65.0.170.png) |
