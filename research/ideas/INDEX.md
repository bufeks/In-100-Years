# アイデア・スコアボード（市場価値 × 個人着手レンズ）

全アイデアを2つのレンズで評価：
- **市場価値スコア**（`docs/01_evaluation-framework.md` — 7軸）：「世界にとって意味があるか」
- **個人着手スコア**（`docs/03_personal-accessibility.md` — 5軸）：「自分／小資本で参入できるか」
- **統合スコア**＝市場 × 個人 / 100

> 最終更新：**2026-08-25**。降順は**統合スコア**（個人視点）。
>
> **目的関数別クイックビュー**は `../docs/04_temporal-objective-function.md`（2×2 マトリクス）を参照。

---

## 目的関数別クイックビュー（2×2 マトリクス）

```
              Income（継続 CF）              資産（appreciation）
   短期     Q1 【本命：数年 ¥30M+/年】 | Q2 【短期資産】
   1-5 年   0022 0016 0026 0019       | 0013 0028 0027 0029
            0007ε 0024 0014 0023 0015 | 0018 0021 0002 0006 0003 0001
   長期     Q3 【長期 income 積上】    | Q4 【100 年資産】
   5-100年  0008 0025(賃貸) 0017      | 0025(土地) 0020 0018 0002 0005 0004
```

詳細：[`../docs/04_temporal-objective-function.md`](../docs/04_temporal-objective-function.md)

---

## 個人視点ランキング（統合スコア降順）

| ID | テーマ | 市場 | 個人 | **統合** | ティア | 個人の打ち手 |
|----|--------|:-:|:-:|:-:|:-:|---|
| [0013](0013-post-public-market-infrastructure.md) | ポスト公開市場 | 85 | 88 | **75** | S | BLK／SCHW／HOOD／ONDO／FRGE |
| [0016](0016-meaning-making-infrastructure.md) | 意味の場 | 81 | 92 | **75** | A | Substack／Discord／Patreon／宗教 SaaS |
| [0025](0025-japan-akiya-contrarian.md) | **日本空き家（Kabukicho 型）** | 85 | 88 | **75** | S | 空き家バンク・任意売却・廃業旅館 |
| [0026](0026-succession-msme-search-fund.md) | **後継者難 M&A** | 88 | 84 | **74** | S | TRANBI／BATONZ／サーチャー |
| [0028](0028-rwa-tokenization.md) | **RWA トークン化** | 84 | 80 | **67** | A | ONDO／BUIDL／OUSG／Progmat／COIN・HOOD |
| [0004](0004-provenance-infrastructure.md) | 来歴・真正性 | 83 | 76 | **63** | A | C2PA 系 OSS／業界別認証 SaaS |
| [0019](0019-ai-agent-wealth-management.md) | **AIエージェント運用** | 83 | 72 | **60** | A | Robo SaaS／日本特化 iDeCo/NISA |
| [0022](0022-post-ai-creative-agency.md) | **ポスト AI クリエイティブ AGY** | 72 | 84 | **60** | A | 5–50 人ブティック／AI オーケストレ |
| [0027](0027-bitcoin-l2.md) | **Bitcoin L2 / BTC-fi** | 78 | 76 | **59** | A | STX／Babylon／sBTC DeFi |
| [0020](0020-intergenerational-transfer-infrastructure.md) | **世代間移転** | 90 | 64 | **58** | S | estate SaaS（日本）／信託銀行 |
| [0029](0029-zk-infrastructure.md) | **ZK インフラ** | 81 | 72 | **58** | A | STRK／ZK／Scroll・Linea／Aztec |
| [0014](0014-human-verified-premium.md) | 人間性プレミアム | 83 | 64 | **53** | A | 認証 SaaS／UMG・SONY |
| [0017](0017-cultural-inheritance.md) | 文化継承 | 74 | 72 | **53** | A | 日本方言・口承 |
| [0007](0007-intimacy-economy.md) | 親密性・孤独 | 74 | 72 | **53** | A | ε AIコンパニオン |
| [0015](0015-embodied-experience-economy.md) | 体験・場 | 78 | 64 | **50** | A | 中堅会場ロールアップ |
| [0023](0023-cognitive-warfare-defense.md) | **認知戦防御** | 80 | 64 | **51** | A | 政府・選挙 deepfake 検出 SaaS |
| [0024](0024-creator-ip-custodian.md) | **クリエイター IP カストディアン** | 79 | 64 | **51** | A | AI パーソナ IP |
| [0008](0008-deathcare.md) | 死後ケア | 81 | 60 | **49** | A | ローカル M&A／SCI |
| [0021](0021-longevity-finance.md) | **寿命延伸金融** | 85 | 48 | **41** | S | 大手保険株 |
| [0002](0002-civilizational-data-archive.md) | 超長期アーカイブ | 85 | 44 | **37** | S | TWST |
| [0005](0005-fertility-and-care.md) | 生殖・ケア | 84 | 44 | **37** | A | HIMS |
| [0018](0018-water-assets.md) | 水資産 | 89 | 36 | **32** | S | CDZI／NQH2O |
| [0006](0006-critical-minerals-urban-mining.md) | クリティカルミネラル | 80 | 36 | **29** | A | Redwood／Cirba |
| [0003](0003-waste-heat-economy.md) | 廃熱経済 | 84 | 32 | **27** | A | Carrier／Vertiv |
| [0001](0001-phosphorus-recovery.md) | リン回収 | 81 | 28 | **23** | A | Veolia |

---

## ドメインディープダイブ

- **K ポスト公開市場** → [`../domains/K-post-public-market-deep-dive.md`](../domains/K-post-public-market-deep-dive.md)
- **M クリプト・フロンティア** → [`../domains/M-crypto-frontier-deep-dive.md`](../domains/M-crypto-frontier-deep-dive.md)
- **G 水資産** → [`../domains/G-water-deep-dive.md`](../domains/G-water-deep-dive.md)
- **L 親密性経済** → [`../domains/L-intimacy-deep-dive.md`](../domains/L-intimacy-deep-dive.md)

## 実行プラン

- **0025 空き家 12 ヶ月ロードマップ** → [`../../plans/2026-akiya-execution.md`](../../plans/2026-akiya-execution.md)

## 更新ログ

### 2026-08-25（後半）— 「次の Bitcoin」3 テーマ追加＋ M ドメイン新設
- **0027 Bitcoin L2**（78/76/59）、**0028 RWA トークン化**（84/80/67）、**0029 ZK インフラ**（81/72/58）を新規採点。M クリプト・フロンティア deep dive と plans/2026-akiya-execution.md を新設。

### 2026-08-25 — docs/04 時間軸×目的関数マトリクスを追加

### 2026-08-20 — 0025 空き家・0026 M&A 追加（Kabukicho 型）

### 2026-06-23 — 0024 クリエイター IP 追加

### 2026-06-19 — 0023 認知戦防御 追加

### 2026-06-15 — 0022 kiCk／0019／0020／0021 追加

### 2026-06-08 — 個人着手レンズ・0014-0018・0013/0008/0007 追加
