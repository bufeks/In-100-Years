# シグナル・ログ

世界中から拾った「弱いシグナル」の蓄積。新しい行を上に追記する（新しい順）。記録方法は `templates/signal.md` を参照。

> 弱いシグナル（まだ誰も騒いでいない兆し）ほど価値がある。一次情報に近いものを優先。

| 日付 | ドメイン | シグナル要約 | なぜ重要か（評価ギャップ仮説） | 関連アイデア | 出典 |
|------|---------|------------|--------------------------|------------|------|
| 2026-05-28 | F 食農 | リン鉱石の可採年数は75〜100年、採掘ピークは2030年頃との指摘。リンは代替不能だが回収・再利用は可能。回収を促す取り組みはまだ少ない | 食料に不可欠なのに「退屈」で過小評価。回収側に参入余地 | [0001](../ideas/0001-phosphorus-recovery.md) | [Scientific American](https://www.scientificamerican.com/article/phosphorus-a-looming-crisis/), [National Geographic](https://www.nationalgeographic.com/science/article/farmers-are-facing-a-phosphorus-crisis-the-solution-starts-with-soil) |
| 2026-05-28 | D 記憶 | DNAデータストレージは 10¹⁹ bits/cm³ の超高密度で、適切に保存すれば数百万年残るとされる。ただし書き込みは高コストで研究段階 | 「腐らない媒体」の需要は構造的だが市場は未成熟＝早すぎて安い | [0002](../ideas/0002-civilizational-data-archive.md) | [NCBI: DNA Data Storage](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10296570/) |
| 2026-05-28 | A 熱 / B 計算 | AIデータセンターの電力需要急増が、天然ガスを「つなぎ燃料」として押し上げているとの市場観測。冷却・電力が制約に | 計算の制約は電力と熱へ移行。廃熱・冷却・熱貯蔵に評価余地 | [0003](../ideas/0003-waste-heat-economy.md) | [Morgan Stanley: Megatrends](https://www.morganstanley.com/Themes/megatrends-future-investment-trends) |
| 2026-05-28 | C 信頼 / K 統治 | BlackRock は5大force（AI・デジタル化／世界の分断／低炭素移行／人口分岐／金融の未来）を提示。いずれも数十年スパン | 機関投資家でも視野は数十年。100年視点は視野外＝構造的な評価ギャップ | [0004](../ideas/0004-provenance-infrastructure.md), [0005](../ideas/0005-fertility-and-care.md) | [BlackRock: Megatrends](https://www.blackrock.com/sg/en/investment-strategies/megatrends-and-thematic-investing) |

## 追記のしかた

1. 一番上の行として日付の新しいシグナルを追加。
2. ドメインは `docs/02_domain-map.md` の記号（A〜L）で統一。
3. 同じテーマのシグナルが溜まったら、`research/domains/<domain>.md` で深掘り（テンプレ：`templates/domain-deep-dive.md`）。
