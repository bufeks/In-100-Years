# アイデア・スコアボード（市場価値 × 個人着手レンズ）

全アイデアを2つのレンズで評価：
- **市場価値スコア**（`docs/01_evaluation-framework.md` — 7軸）：「世界にとって意味があるか」
- **個人着手スコア**（`docs/03_personal-accessibility.md` — 5軸）：「自分／小資本で参入できるか」
- **統合スコア**＝市場 × 個人 / 100：「個人にとっての実効的な機会値」

> 最終更新：**2026-08-25**。降順は**統合スコア**（個人視点）。市場価値だけのランキングも併記。
>
> **目的関数別クイックビュー**は `../docs/04_temporal-objective-function.md`（時間軸×収益タイプの 2×2 マトリクス）を参照。数年で ¥30M+/年 を狙うなら Q1（0022／0016／0026／0019／0007-ε／0024）が主戦力、100 年資産形成なら Q4（0025／0020／0018）。

---

## 目的関数別クイックビュー（2×2 マトリクス）

```
              Income（継続 CF）              資産（appreciation）
            ┌────────────────────────┬────────────────────────┐
   短期     │ Q1 【本命：数年 ¥30M+/年】 │ Q2 【短期資産】            │
   1-5 年   │ 0022 0016 0026 0019       │ 0013 0028 0027 0029       │
            │ 0007ε 0024 0014 0023 0015 │ 0018 0021 0002 0006       │
            │                            │ 0003 0001                  │
            ├────────────────────────┼────────────────────────┤
   長期     │ Q3 【長期 income 積上】    │ Q4 【100 年資産】          │
   5-100年  │ 0008 0025(賃貸) 0017      │ 0025(土地) 0020 0018 0002 │
            │                            │ 0005 0004                 │
            └────────────────────────┴────────────────────────┘
```

目的関数を先に決めて対応象限に集中投下する。詳細：[`../docs/04_temporal-objective-function.md`](../docs/04_temporal-objective-function.md)

---

## 個人視点ランキング（統合スコア降順）

| ID | テーマ | 市場 | 個人 | **統合** | ティア | 個人の打ち手 |
|----|--------|:-:|:-:|:-:|:-:|---|
| [0013](0013-post-public-market-infrastructure.md) | ポスト公開市場 | 85 | 88 | **75** | S | BLK／SCHW／HOOD／ONDO トークン／FRGE 株 |
| [0016](0016-meaning-making-infrastructure.md) | 意味の場 | 81 | 92 | **75** | A | Substack／Discord／Patreon／宗教 SaaS／ファンダム運営 |
| [0025](0025-japan-akiya-contrarian.md) | **日本空き家・地方物理資産（Kabukicho 型）** | 85 | 88 | **75** | S | 空き家バンク・任意売却物件・廃業旅館の逆張り取得 |
| [0026](0026-succession-msme-search-fund.md) | **後継者難中小事業の個人 M&A** | 88 | 84 | **74** | S | TRANBI／BATONZ／サーチャー型で 300 万〜3,000 万で取得 |
| [0028](0028-rwa-tokenization.md) | **RWA トークン化** | 84 | 80 | **67** | A | ONDO／BUIDL／OUSG／RealT／Progmat／COIN・HOOD 株 |
| [0004](0004-provenance-infrastructure.md) | 来歴・真正性 | 83 | 76 | **63** | A | C2PA 関連 OSS／ニッチ業界向け真正性 SaaS |
| [0019](0019-ai-agent-wealth-management.md) | **AIエージェント運用** | 83 | 72 | **60** | A | Robo SaaS／日本特化 iDeCo/NISA 統合 |
| [0022](0022-post-ai-creative-agency.md) | **ポスト AI クリエイティブエージェンシー** | 72 | 84 | **60** | A | 5–50 人ブティック起業／AI オーケストレーション |
| [0027](0027-bitcoin-l2.md) | **Bitcoin L2 / BTC-fi** | 78 | 76 | **59** | A | STX／Babylon BTC ステーキング／sBTC DeFi |
| [0020](0020-intergenerational-transfer-infrastructure.md) | **世代間移転インフラ** | 90 | 64 | **58** | S | estate planning SaaS（日本特化）／信託銀行株 |
| [0029](0029-zk-infrastructure.md) | **ZK インフラ** | 81 | 72 | **58** | A | STRK／ZK／Scroll・Linea エアドロ／Aztec テストネット |
| [0014](0014-human-verified-premium.md) | 人間性プレミアム | 83 | 64 | **53** | A | 人間製造認証 SaaS／IP連動／UMG・SONY 株 |
| [0017](0017-cultural-inheritance.md) | 文化継承の保存 | 74 | 72 | **53** | A | 日本の方言・口承プロジェクト |
| [0007](0007-intimacy-economy.md) | 親密性・孤独経済 | 74 | 72 | **53** | A | ε AIコンパニオン（Chai 型 12人 $30M ARR） |
| [0015](0015-embodied-experience-economy.md) | 体験・場の経済 | 78 | 64 | **50** | A | 中堅会場ロールアップ／地域フェス |
| [0023](0023-cognitive-warfare-defense.md) | **認知戦防御・人間性認証** | 80 | 64 | **51** | A | 政府・選挙特化 deepfake 検出 SaaS |
| [0024](0024-creator-ip-custodian.md) | **クリエイター IP カストディアン** | 79 | 64 | **51** | A | AI パーソナ IP ホールディング／日本特化 |
| [0008](0008-deathcare.md) | 死後ケア・葬儀 | 81 | 60 | **49** | A | ローカル M&A／デジタル遺品 SaaS |
| [0021](0021-longevity-finance.md) | **寿命延伸金融** | 85 | 48 | **41** | S | 大手保険株（日本生命／MET） |
| [0002](0002-civilizational-data-archive.md) | 超長期アーカイブ | 85 | 44 | **37** | S | TWST 株／応用層 0014・0017 で間接参加 |
| [0005](0005-fertility-and-care.md) | 生殖・ケア | 84 | 44 | **37** | A | HIMS／関連スタートアップ周辺 |
| [0018](0018-water-assets.md) | 水資産 | 89 | 36 | **32** | S | CDZI／PHO／FIW／CGW／AWES／NQH2O 先物 |
| [0006](0006-critical-minerals-urban-mining.md) | クリティカルミネラル | 80 | 36 | **29** | A | Redwood／Cirba 周辺株 |
| [0003](0003-waste-heat-economy.md) | 廃熱経済 | 84 | 32 | **27** | A | Carrier／Trane／Vertiv 株 |
| [0001](0001-phosphorus-recovery.md) | リン回収・循環 | 81 | 28 | **23** | A | Veolia／日本水処理大手株 |

---

## 市場価値ランキング（参考）

※上の個人視点ランキングを市場列でソートし直すと参考になる。市場価値最高位は **0020 世代間移転（90）** > 0018 水資産（89） > 0026 後継者難 M&A（88） > 0002／0013／0021／0025（85） > 0028 RWA トークン化・0003・0005（84） > 0029 ZK インフラ・0004・0019・0014（81-83） > 0027 Bitcoin L2（78） > … > 0022 ポスト AI クリエイティブ（72）。

---

## ドメインディープダイブ

- **K ポスト公開市場（0013／0019／0020／0021）** → [`../domains/K-post-public-market-deep-dive.md`](../domains/K-post-public-market-deep-dive.md)
- **M クリプト・フロンティア（0027／0028／0029／Prediction Markets）** → [`../domains/M-crypto-frontier-deep-dive.md`](../domains/M-crypto-frontier-deep-dive.md)
- **G 水資産（0018）** → [`../domains/G-water-deep-dive.md`](../domains/G-water-deep-dive.md)
- **L 親密性経済（0007）** → [`../domains/L-intimacy-deep-dive.md`](../domains/L-intimacy-deep-dive.md)

## 実行プラン

- **0025 空き家取得 12 ヶ月ロードマップ（買い方）** → [`../../plans/2026-akiya-execution.md`](../../plans/2026-akiya-execution.md)
- **空き家・土地活用ビジネス 7 型（稼ぎ方）** → [`../../plans/akiya-business-models.md`](../../plans/akiya-business-models.md)

## 退屈ウォッチリスト

`../exploration/boring-candidates.md`（B01–B12）。

---

## 更新ログ

### 2026-08-25（追補）— 空き家ビジネス 7 型を具体化
- **plans/akiya-business-models.md** 新設：0025 を Q4（寝かせる）から Q1/Q3 の income エンジンに変換する 7 事業モデル（B-1 サブリース再生／B-2 一棟貸し宿泊／B-3 空き家管理／B-4 廃業旅館承継／B-5 土地バンキング転用／B-6 クリエイター拠点／B-7 メディア＆ファンド）。
- 推奨シーケンス：Year1 B-3＋B-1＋B-7 仕込み → Year2 B-2＋B-6 → Year3 B-4 で ¥30M+/年。

### 2026-08-25（後半）— 「次の Bitcoin」3 テーマ追加＋ M ドメイン新設
- **0027 Bitcoin L2 / BTC-fi**（78/76/59・A）、**0028 RWA トークン化**（84/80/67・A）、**0029 ZK インフラ**（81/72/58・A）を新規採点。
- **M クリプト・フロンティア** ディープダイブ新設（0027/0028/0029/Prediction Markets 統合分析）。
- **plans/2026-akiya-execution.md** 新設：0025 の 12 ヶ月実行ロードマップ。
- Q2 短期資産の中核が RWA（0028）＋ Bitcoin L2（0027）＋ ZK（0029）に。

### 2026-08-25 — docs/04 時間軸×目的関数マトリクスを追加
- 100 年統合スコア（世界の観測値、不変）と個人優先順位（目的関数依存）を分離。
- 4 象限：Q1 短期×Income（本命）／Q2 短期×資産（投資）／Q3 長期×Income（積上げ）／Q4 長期×資産（Kabukicho）。

### 2026-08-20 — Kabukicho 型の逆張りポジション追加（0025／0026）

### 2026-06-23 — 0024 クリエイター IP カストディアン 追加

### 2026-06-19 — 0023 認知戦防御 追加

### 2026-06-15 — 0022 kiCk 考察／0019／0020／0021 追加

### 2026-06-08 — 個人着手レンズ・0014-0018・0013/0008/0007 追加

## 読み筋メモ

- **本丸 4 テーマ**（0013／0016／0025／0026）はすべて Q1 または Q1/Q4 に位置する。
- 目的関数によって優先順位が変わるので、`docs/04` を必ず先に見る。

## 新規アイデアの追加手順

1. `templates/idea.md` をコピーして `research/ideas/NNNN-name.md` を作成。
2. 「殺しの質問」に答え、7軸（市場価値）＋5軸（個人着手）で採点。
3. この表に1行追加し、**統合スコア降順**で並べ替え。
4. `docs/04` の 4 象限への分類も漏れなくやる。
