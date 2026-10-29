# Apex Preview Changelog (老板本地预览包)

日期：2026-10-18（Asia/Shanghai）  
工作目录：`/workspace/apex-preview/`（由 `/workspace/exchange-site/` 完整复制，源目录未改）

## 口径锁定

- 受众：海外华人
- 公开价：**详询**（不挂美元/人民币数字）
- 总标题：**四套交易系统**（禁止「四套现货」）
- 对客四套名：
  1. 外汇微盘 / Forex Short-Cycle
  2. 现货系统 / Spot Desk
  3. 旗舰综合 / Flagship Suite
  4. 机构席位 / Institutional Desk
- 禁止对外：OKX / 币安 / Binance 品牌对标、「1:1 OKX」、插针/假单/控盘黑话式卖点
- 软件交付中性表述：ops console / 风控参数 / 做市工具 / 源码交付 / 私有化部署

## index.html 关键文案

| 区域 | 旧 | 新 |
|------|----|----|
| meta title/desc/keywords | 币币综合盘、OKX 1:1 等 | 四套新名 + 源码交付/私有化；公开价详询 |
| systems_title | 四套现货系统 | **四套交易系统** |
| sys0–sys3 标题 | 外汇黄金微盘 / 交易所综合盘 / 旗舰版 / 顶级机构版 | 外汇微盘 / 现货系统 / 旗舰综合 / 机构席位 |
| 卡片副标 | 插针·自发币、1:1 OKX 等 | 短周期模块 / 现货撮合 / 多模块综合 / 多席位后台 |
| sys_desc0–3（中英日德） | 插针点杀、OKX 像素还原等 | 中性能力描述 + EN 正式名 |
| Demo 区 | Admin demo / 123456 假后台 | **详询 / 联系 Telegram 领取演示** |
| mat0–mat3 | 单控点杀、镜像做市（币安/OKX）、永续控盘、深度伪造 | 风控参数、做市工具、行情模块、深度策略（可对接公开行情深度，以合同为准） |
| FAQ1 | 币安与 OKX 实时订单簿 | 可对接主流公开行情深度；做市与风控参数可配置（以合同为准） |
| hero_sub | 外汇·币币·永续 | 四套交易系统 · 源码交付 / 私有化部署 |
| i18n | zh/en/ja/de 字典上述键全部对齐 | 已改齐 |

视觉/CSS/视频结构未动，仅改文案与 i18n。页脚版本标为 `v4.0.0-preview`。

## articles / honors / sitemap

- `08-clone-binance-okx.html` → **`08-institutional-desk-delivery.html`**（机构席位交付说明，去掉 clone OKX）
- `articles/index.html`：03 / 08 列表标题与链接更新
- `03-market-making.html`：标题与正文改为做市工具/公开行情深度中性表述
- `04-exchange-source-guide.html`：四套 SKU 与 FAQ 中 OKX/币安对标句中/英/日/德清理
- `06-perpetual-source.html`：标记价格表述去掉 Binance/OKX 品牌
- `09` / `10`：指向 08 的链接与锚文更新
- `honors.html`：做市软著说明去掉「复刻币安/OKX」
- `sitemap.xml`：08 新文件名

## 第二遍对客口径清洗（2026-10-18 Asia/Shanghai）

商务官/情报官复审补丁 + 四套介绍定稿。源目录 `/workspace/exchange-site/` 未改。

### index.html
| 项 | 旧 | 新 |
|----|----|----|
| nav_matrix | 武器库 / Toolkit 等 | **能力模块**（en Capability Modules / ja 機能モジュール / de Fähigkeitsmodule） |
| matrix_title | 操盘手专属后台 | **运维后台**（en Ops Console 等） |
| faq_title | 操盘手关心的 | **常见问题** / FAQ |
| hero_consult / cta_btn | 立即咨询 | **详询**（en Inquire 等） |
| 交付条 p1 | 验楼跑通后再放款 | **合同约定里程碑验收与付款** |
| 卡片副标 sys0–3_d | 短周期模块 / 现货撮合 / 多模块综合 / 多席位后台 | **短周期外汇 / 现货买卖 / 多业务一套 / 多人分权后台** |
| sys_desc0–3 | 术语版能力句 | 商务官短稿（干什么+适合谁+交付边界+详询），zh/en/ja/de 同步 |
| sys_demo | 详询 / 领取演示 | **看演示 / 详询** |

### articles
- `03`：标题/正文「露馅」→「需要谨慎调校的参数 / 盘口观感」
- `04`：公开价表与 FAQ 价带 → **公开价详询**；CTA → **详询**；FAQ「不做 KYC」→ **合规由买方自行办理；我方仅软件交付**；单控/操盘措辞中性化；ja/de 价带同步
- `05` / `07`：单控点杀、假单补量、胜率控盘段 → **风控参数 / 做市与行情工具 / ops console（以合同为准）**；价码 → 详询
- `06`：深度伪造 → **深度策略**；8–15 万/10–20 万 → 详询
- `01`：撮合文去掉币安/OKX/Bybit 品牌列举
- `08`：负面列举中的插针/假单字样改为「中性软件能力表述」
- `09` / `10`：现货/白标公开价带与月租 $2000–5000、买断 5–15 万 → **公开价详询**；操盘手 → 运营方（10）
- `articles/index.html`：列表摘要去掉单控点杀

### 扫残（第二遍结束）
主禁词（OKX/币安/Binance/插针/假单/单控点杀/123456/不做 KYC/武器库/立即咨询/验楼/公开人民币·美元价带）在 `*.html` 中 **无残留**（CHANGELOG 历史对照除外）。  
保留：`index.html` 统计位 `$0`（资金故障示意，非售价）；文章内「KYC/OTP」作合规模块名（非「不做 KYC」规避口吻）；「100 USDT」链上验真示例。

### 打包
覆盖：`/workspace/apex-preview-zh-sku.zip`


## 本地打开

解压或直接打开：

```text
/workspace/apex-preview/index.html
```

用浏览器本地打开即可预览（含 background.mp4 / poster.jpg）。无需 FTP、不上线。

## 打包

`/workspace/apex-preview-zh-sku.zip`（第二遍覆盖）含：index.html、honors.html、articles/、robots.txt、sitemap.xml、poster.jpg、background.mp4、CHANGELOG.md

### 补丁
- articles/10 底按钮「获取源码报价」→「详询」

### 第三遍小补
- index 运维副标「毫秒级掌控全局」→「毫秒级运维响应」
- articles/06「实际操盘中」→「实际运营中」
- articles/10「获取源码报价」→「详询」（上轮已改，本包确认）

### 锁名更新（老板）
- 「现货系统」→「交易所综合系统」（EN: Exchange Suite）
- 说明：含现货+秒合约+永续；与旗舰综合能力接近，主要是 UI 不同
- 旗舰综合文案同步点明与综合系统的关系

### 对齐商务官定稿大白话
- 副标：短周期外汇｜综合多业务｜同能力新 UI｜多人分权后台
- 综合/旗舰写明同能力、主要 UI 差，非更深交付
